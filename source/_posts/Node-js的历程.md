---
title: Node.js的历程
date: 2018-03-15 15:24:55
tags: -node
categories: -技术
comment: true
---
## Node相较于其他后台语言的优势
1. 性能优势
2. 跟前台的js配合方便
3. NodeJS便于前端学习

## Nodejs 建立服务器

    const http =require('http'); //http---协议（http rfc）

    var server =  http.createServer(function (req('请求信息') , res('响应信息')) {
    })

    //监听 --
    server.listen(8080)
  #### createServer()中的两个参数
 1. req
 2. res
 3. 文件操作：fs


