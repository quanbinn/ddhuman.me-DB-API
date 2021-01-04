# remove((query))

```javascript
use <db>

db.collection.deleteMany()
db.collection.deleteOne()
```

```javascript
db.inventory.insertMany( [
   { item: "journal", qty: 25, size: { h: 14, w: 21, uom: "cm" }, status: "A" },
   { item: "notebook", qty: 50, size: { h: 8.5, w: 11, uom: "in" }, status: "P" },
   { item: "paper", qty: 100, size: { h: 8.5, w: 11, uom: "in" }, status: "D" },
   { item: "planner", qty: 75, size: { h: 22.85, w: 30, uom: "cm" }, status: "D" },
   { item: "postcard", qty: 45, size: { h: 10, w: 15.25, uom: "cm" }, status: "A" },
] );

db.inventory.deleteMany({})

// { <field1>: <value1>, ... }
// { <field1>: { <operator1>: <value1> }, ... }
db.inventory.deleteMany({ status : "A" })

db.inventory.deleteOne( { status: "D" } )
```
## Reference

1. [Delete Documents](https://docs.mongodb.com/manual/tutorial/remove-documents/)
2. [MongoDB 删除文档](https://www.mongodb.org.cn/tutorial/12.html)


