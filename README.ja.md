# init-for-mysql

[Click here for English version.](./README.ja.md)

## 概要

MySQLを環境変数から初期化する。

実は[こちらの記事](https://qiita.com/t0w4/items/e886a514559cdb295600)の~~丸パクリ~~リスペクトだったりする。

## 環境変数

|    環境変数    |                  説明                  |  初期値   |
| :------------: | :------------------------------------: | :-------: |
| MYSQL_DB_HOST  |         SQL server IP address          | localhost |
|   MYSQL_PORT   |         SQL server port number         |   3306    |
|   MYSQL_USER   |          User name to use SQL          |   root    |
| MYSQL_PASSWORD |   Password of the user who uses SQL    |           |
|    MYSQL_DB    | The name of the database to connect to |           |
| MYSQL_PROTOCOL |   SQL server communication protocol    |    tcp    |
|  MYSQL_DBARGS  |     Sorry, I can't understand it.      |           |
