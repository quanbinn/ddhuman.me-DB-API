# insert(document)

```javascript
use <db>
db.collection.insertOne({})
db.collection.insertOne([{},{},{}])

/* 
use ddhumanMe
ddhumanMe.users.insertOne({
  username: 'DDHumanMe_user_N',
  password: '758bcdb63252d8589ee75f2b7d1e3d6a', // MD5(userNpassword)
  email: { address: 'ddhumanme@example.com', verified: true },
  createdAt: 'Wed Sep 23 2020 17:22:29 GMT+0800 (中国标准时间)', // new Date()
  cellphone: { number: '180****6666', verified: false }
})


*/
```

## Reference

1. [Insert Documents](https://docs.mongodb.com/manual/tutorial/insert-documents/)
2. [MongoDB 插入文档](https://www.mongodb.org.cn/tutorial/10.html)

