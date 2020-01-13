# init-for-mysql

[日本語版はこちら](./README.ja.md)

## Overview

Initialize MySQL from environment variables.

Actually, I ~~stole~~ respected code from [the article (written in Japanese)](https://qiita.com/t0w4/items/e886a514559cdb295600).

## Environment Variables

| Environment Variables |              Description               | Initial Value |
| :-------------------: | :------------------------------------: | :-----------: |
|     MYSQL_DB_HOST     |         SQL server IP address          |   localhost   |
|      MYSQL_PORT       |         SQL server port number         |     3306      |
|      MYSQL_USER       |          User name to use SQL          |     root      |
|    MYSQL_PASSWORD     |   Password of the user who uses SQL    |               |
|       MYSQL_DB        | The name of the database to connect to |               |
|    MYSQL_PROTOCOL     |   SQL server communication protocol    |      tcp      |
|     MYSQL_DBARGS      |      Query to connect to database      |               |
