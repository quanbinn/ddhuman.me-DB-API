# DDHuman.me API

## 典型Documents

| 互联网用户 | 文本 | 实体物品 | **Multimedia** |
|---------|--------|---------|--------|
|[普通用户]|[实验文章]|[学习用品]|[演示视频]|
|[商家用户]|         |[工作用品]|[演示音频]|
|    	  |         |[锻炼用品]|         |

[普通用户]: /chapters/典型Documents/普通用户.md
[商家用户]: /chapters/典型Documents/商家用户.md

[实验文章]: /chapters/典型Documents/实验文章.md

[学习用品]: /chapters/典型Documents/学习用品.md
[工作用品]: /chapters/典型Documents/工作用品.md
[锻炼用品]: /chapters/典型Documents/锻炼用品.md

[演示视频]: /chapters/典型Documents/演示视频.md
[演示音频]: /chapters/典型Documents/演示音频.md

## 数据库操作

| Databases | Collections | **CRUD** | 
|---------|--------|--------|
|[create a database]|[create a collection]|[JSON->BSON]|
|[drop a database]|[drop a collection]|[insert(document)]|
|				  |					  |[find((query))]|
|				  |					  |[update((query),(update))]|
|				  |					  |[remove((query))]|

[create a database]: /chapters/数据库操作/create-a-database.md
[drop a database]: /chapters/数据库操作/drop-a-database.md

[create a collection]: /chapters/数据库操作/create-a-collection.md
[drop a collection]: /chapters/数据库操作/drop-a-collection.md

[JSON->BSON]: /chapters/数据库操作/JSON-BSON.md
[insert(document)]: /chapters/数据库操作/insert(document).md
[find((query))]: /chapters/数据库操作/find((query)).md
[update((query),(update))]: /chapters/数据库操作/update((query),(update)).md
[remove((query))]: /chapters/数据库操作/remove((query)).md

| Shell Methods | **Image/Multimedia** | 
|---------|--------|
|[ObjectId]|[Image]|
|		   |[Video]|
|		   |[Audio]|

[ObjectId]: /chapters/数据库操作/ObjectId.md

[Image]: /chapters/数据库操作/Image.md
[Video]: /chapters/数据库操作/Video.md
[Audio]: /chapters/数据库操作/Audio.md

## 对用户的CRUD
- CREATE
  - [createUser](/chapters/对用户的CRUD/createUser.md)
- READ
  - [loggingIn](/chapters/对用户的CRUD/loggingIn.md)
  - [logout](/chapters/对用户的CRUD/logout.md)
  - [findUserByUsername](/chapters/对用户的CRUD/findUserByUsername.md)
  - [findUserByPhonenumber](/chapters/对用户的CRUD/findUserByPhonenumber.md)
- UPDATE

| Password | Cellphone | 
|---------|--------|
|[changePassword]|[addCellphone]|
|[forgotPassword]|[verifyPhonenumber]|
|[resetPassword] |					 |
|[setPassword]   |					 |					 
|[sendResetPasswordEmail]|			 |

[changePassword]: /chapters/对用户的CRUD/changePassword.md
[forgotPassword]: /chapters/对用户的CRUD/forgotPassword.md
[resetPassword]: /chapters/对用户的CRUD/resetPassword.md
[setPassword]: /chapters/对用户的CRUD/setPassword.md
[sendResetPasswordEmail]: /chapters/对用户的CRUD/sendResetPasswordEmail.md

[addCellphone]: /chapters/对用户的CRUD/addCellphone.md
[verifyPhonenumber]: /chapters/对用户的CRUD/verifyPhonenumber.md

## 对广告的CRUD

| **C** | **R** | **U** | **D** |
|---------|--------|---------|--------|
|[createAdvertisement]|[findAdvertisementById]|[editAdvertisement]|[deleteAdvertisement]|

[createAdvertisement]: /chapters/对内容的CRUD/createAdvertisement.md
[findAdvertisementById]: /chapters/对内容的CRUD/findAdvertisementById.md
[editAdvertisement]: /chapters/对内容的CRUD/editAdvertisement.md
[deleteAdvertisement]: /chapters/对内容的CRUD/deleteAdvertisement.md

## 对内容的CRUD

- Experiment

| **C** | **R** | **U** | **D** |
|---------|--------|---------|--------|
|[createExperiment]|[findExperimentById]|[editExperiment]|[deleteExperiment]|

[createExperiment]: /chapters/对内容的CRUD/createExperiment.md
[findExperimentById]: /chapters/对内容的CRUD/findExperimentById.md
[editExperiment]: /chapters/对内容的CRUD/editExperiment.md
[deleteExperiment]: /chapters/对内容的CRUD/deleteExperiment.md

- Truth

| **C** | **R** | **U** | **D** |
|---------|--------|---------|--------|
|[createTruth]|[findTruthById]|[editTruth]|[deleteTruth]|

[createTruth]: /chapters/对内容的CRUD/createTruth.md
[findTruthById]: /chapters/对内容的CRUD/findTruthById.md
[editTruth]: /chapters/对内容的CRUD/editTruth.md
[deleteTruth]: /chapters/对内容的CRUD/deleteTruth.md

- Danger

| **C** | **R** | **U** | **D** |
|---------|--------|---------|--------|
|[createDanger]|[findDangerById]|[editDanger]|[deleteDanger]|

[createDanger]: /chapters/对内容的CRUD/createDanger.md
[findDangerById]: /chapters/对内容的CRUD/findDangerById.md
[editDanger]: /chapters/对内容的CRUD/editDanger.md
[deleteDanger]: /chapters/对内容的CRUD/deleteDanger.md

## 站内搜索
- [功能3](/chapters/站内搜索/功能3.md)

## 推荐系统

## 常用页面
- [首页](/chapters/常用页面/首页.md)