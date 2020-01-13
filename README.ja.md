# init-for-mysql

[Click here for English version.](./README.ja.md)

## 概要

MySQLを環境変数から初期化する。

実は[こちらの記事](https://qiita.com/t0w4/items/e886a514559cdb295600)の~~丸パクリ~~リスペクトだったりする。

## 環境変数

|    環境変数    |               説明               |  初期値   |
| :------------: | :------------------------------: | :-------: |
| MYSQL_DB_HOST  |      SQLサーバのIPアドレス       | localhost |
|   MYSQL_PORT   |      SQLサーバのポート番号       |   3306    |
|   MYSQL_USER   |      SQLを使用するユーザ名       |   root    |
| MYSQL_PASSWORD | SQLを使用するユーザのパスワード  |           |
|    MYSQL_DB    |      接続するデータベース名      |           |
| MYSQL_PROTOCOL |    SQLサーバの通信プロトコル     |    tcp    |
|  MYSQL_DBARGS  | データベースへ接続する際のクエリ |           |
