# insert(document)

```javascript
use <db>
db.collection.insertOne({})
db.collection.insertMany([{},{},{}])
```

```javascript
use ddhumanMe
ddhumanMe.users.insertOne({
  username: 'DDHumanMe_user_N',
  password: '758bcdb63252d8589ee75f2b7d1e3d6a', // MD5(userNpassword)
  email: { address: 'ddhumanme@example.com', verified: true },
  createdAt: 'Wed Sep 23 2020 17:22:29 GMT+0800 (中国标准时间)', // new Date()
  cellphone: { number: '180****6666', verified: false }
})
```

```javascript
use ddhumanMe
ddhumanMe.goods.insertMany({
  name: 'A2标准坐标纸',
  showImage: '/images/goods/A2标准坐标纸.png',
  buyUrl：{
  	 京东: 'https://item.jd.com/10394620601.html',
	 淘宝：'https://detail.tmall.com/item.htm?id=27142292922&ali_refid=a3_430583_1006:1105863285:N:dZ%20MV6sJ%20YlXqxaoC1QlJw==:77285e2bbcb0cebf9d00068f21bd840f&ali_trackid=1_77285e2bbcb0cebf9d00068f21bd840f&spm=a230r.1.14.1&skuId=3165771512170'
  }
  tag: ['学习用品'],
  createdAt: 'Wed Sep 23 2020 17:22:29 GMT+0800 (中国标准时间)', // new Date()
  creator: 'QwkSmTCZiw5KDx3L6'  // userId()	
},{
  name: '彩铅',
  showImage: '/images/goods/彩铅.png',
  buyUrl：{
  	 京东: 'https://item.jd.com/864681.htmlp',
	 淘宝：'https://detail.tmall.com/item.htm?spm=a230r.1.14.8.7a1b4237sLkqe4&id=10680260235&cm_id=140105335569ed55e27b&abbucket=9'
  }
  tag: ['学习用品'],
  createdAt: 'Wed Sep 23 2020 17:22:29 GMT+0800 (中国标准时间)', // new Date()
  creator: 'QwkSmTCZiw5KDx3L6'  // userId()	
},{
  name: '雕塑泥',
  showImage: '/images/goods/雕塑泥.png',
  buyUrl：{
  	 京东: 'https://item.jd.com/45225868113.html#crumb-wrap',
	 淘宝：'https://item.taobao.com/item.htm?spm=a230r.1.14.16.1c8354f4Ig6vLs&id=595424471145&ns=1&abbucket=9#detail'
  }
  tag: ['学习用品'],
  createdAt: 'Wed Sep 23 2020 17:22:29 GMT+0800 (中国标准时间)', // new Date()
  creator: 'QwkSmTCZiw5KDx3L6'  // userId()	
}])
```

## Reference

1. [Insert Documents](https://docs.mongodb.com/manual/tutorial/insert-documents/)
2. [MongoDB 插入文档](https://www.mongodb.org.cn/tutorial/10.html)

