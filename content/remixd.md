---
title: "设置Remix连接到本地"
date: 2022-03-07T11:30:00+08:00
draft: true
tags: ["remix","solidity"]
series: ["solidity开发"]
categories: ["环境搭建"]
hidden: true
type: posts
---

### 1 set Node path
### 2 uninstall the old one
`npm uninstall -g remixd`
### 3 install the new
`npm install -g @remix-project/remixd`
### 4 set remix local server
`remixd -s <absolute-path> --remix-ide https://remix.ethereum.org`
