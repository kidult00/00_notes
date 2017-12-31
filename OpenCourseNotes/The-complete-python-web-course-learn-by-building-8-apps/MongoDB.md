# MongoDB

安装

``brew install mongodb``

Create the data directory

``sudo mkdir -p /data/db && sudo chown `whoami` /data/dbm``

``sudo chown `whoami` /data/dbm/``

- 启动服务端  ``mongod``
- 启动客户端  ``mongo``
- 查看数据库  ``show dbs``
- 新建/启动数据库  ``use %dbname%``
- 查看数据集  ``show collections``
- 插入数据  ``db.student.insert({"name":"Kidult", "mark":90})``
- 查找数据  ``db.student.find({})``
- 删除数据  ``db.student.remove({})``

[Install MongoDB Community Edition on macOS — MongoDB Manual 3.6](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/) 

在 python 中使用

安装 pymongo