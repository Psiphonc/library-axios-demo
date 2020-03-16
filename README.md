- 图书相关的操作基于后台接口数据进行擦欧总
- 需要调用接口的功能点

|            接口名             |  方式  |                  URL                   |
| :---------------------------: | :----: | :------------------------------------: |
|       图书列表数据加载        |  GET   |      http://localhost:3000/books       |
|           添加图书            |  POST  |      http://localhost:3000/books       |
|       验证书名是否存在        |  GET   | http://localhost:3000/books/book/:name |
| 编辑图书-根据 ID 查询图书信息 |  GET   |    http://localhost:3000/books/:id     |
|     编辑图书-提交图书信息     |  PUT   |    http://localhost:3000/books/:id     |
|           删除图书            | DELETE |    http://localhost:3000/books/:id     |
