---
title: "Linux git clone TLS error"
date: 2022-03-07T11:30:00+08:00
draft: true
tags: ["linux","git"]
series: ["linux开发"]
categories: ["环境搭建"]
hidden: true
type: posts
---
报错

`fatal: unable to access '': GnuTLS recv error (-110): The TLS connection was non-properly terminated.`

解决方法:

```
apt-get install gnutls-bin
git config --global http.sslVerify false
git config --global http.postBuffer 1048576000
```