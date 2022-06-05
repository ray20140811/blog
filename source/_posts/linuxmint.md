---
title: linuxmint-安裝Node.js 14
date: 2022-06-05 16:03:22
tags:
---

## Step 1: 更新

``` bash
$ sudo apt update 
```

## Step 2: 創建apt sources list

``` bash
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
```

## Step 3: 安裝

``` bash
$ sudo apt -y install nodejs
```

## Step 4: 檢查版本

``` bash
$ node -v
```


