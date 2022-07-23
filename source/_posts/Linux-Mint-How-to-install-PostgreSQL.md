---
title: Linux Mint - How to install PostgreSQL
date: 2022-07-23 11:32:16
tags:
---


## Step 1: 更新

``` bash
$ sudo apt update -y
```

## Step 2: 安裝

``` bash
$ sudo apt install postgresql postgresql-contrib
```

## Step 3: 確認

``` bash
$ sudo systemctl status postgresql
```

## Step 4: 登入

``` bash
$ sudo -i -u postgres
$ psql
# \q
```

### 參考資料:[How to Install PostgreSQL with pgAdmin4 on Linux Mint 20](https://www.tecmint.com/install-postgresql-with-pgadmin4-on-linux-mint/)

