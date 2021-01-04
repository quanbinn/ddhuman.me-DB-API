# find((query))

```javascript
use <db>
db.collection.find({})
db.collection.find({ <field1>: <value1>, ... })
```

```javascript
db.inventory.insertMany([
   { item: "journal", qty: 25, size: { h: 14, w: 21, uom: "cm" }, status: "A" },
   { item: "notebook", qty: 50, size: { h: 8.5, w: 11, uom: "in" }, status: "A" },
   { item: "paper", qty: 100, size: { h: 8.5, w: 11, uom: "in" }, status: "D" },
   { item: "planner", qty: 75, size: { h: 22.85, w: 30, uom: "cm" }, status: "D" },
   { item: "postcard", qty: 45, size: { h: 10, w: 15.25, uom: "cm" }, status: "A" }
]);

db.inventory.find( {} )

// { <field1>: <value1>, ... }
db.inventory.find( { status: "D" } )

// { <field1>: { <operator1>: <value1> }, ... }
db.inventory.find( { status: { $in: [ "A", "D" ] } } )

db.inventory.find( { status: "A", qty: { $lt: 30 } } )

db.inventory.find( { $or: [ { status: "A" }, { qty: { $lt: 30 } } ] } )

db.inventory.find( {
     status: "A",
     $or: [ { qty: { $lt: 30 } }, { item: /^p/ } ]
} )
```

## Reference

1. [Query Documents](https://docs.mongodb.com/manual/tutorial/query-documents/)
