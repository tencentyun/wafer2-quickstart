# Wafer2 腾讯云一站式小程序解决方案

## 简介

开发者工具方案（以下简称 Wafer2）是 2017 年腾讯云基于原来的 Wafer 解决方案（以下简称 Wafer1）并与微信团队深度定制合作的一站式小程序解决方案，Wafer 团队基于腾讯云强大的 IaaS 能力搭建了一个 PaaS 小程序解决方案，用户只需要开通，即可使用开发者工具上传、部署、调试小程序后端代码，无需了解服务器运维、数据库部署搭建即可使用。

Wafer1，使用 Wafer2 用户不需要自行对服务器进行操作部署和上传代码，只需要下载安装微信开发者工具，并通过微信开发者工具一键上传、部署、调试小程序后端代码，即可通过腾讯云分配的域名访问。

Wafer2 还区分开发环境和生产环境，开发环境是由腾讯云默认分配的 `qcloud.la` 域名，在开发环境中，Node.js 版本可以对代码进行远程调试，用户可以在开发环境对代码进行开发调试，开发完成之后再部署到生产环境，以免开发影响线上代码运行。

## Wafer1 和 Wafer2

Wafer1 是由腾讯云封装好两个服务器，并将域名解析到分配的负载均衡上，最后分配给用户。Wafer1 的整体架构十分成熟，适合中大型公司或者有开发能力的小型公司或个人进行使用，但对于初级开发者来说有着相对高的进阶门槛。

Wafer 团队在内部分析这个问题之后，推出了 Wafer2 解决方案。Wafer2 抛弃了原先直接将服务器所有权交给用户的方式，由腾讯云统一部署和托管服务器，基于服务器封装多种语言运行环境（目前支持 Node.js 和 PHP），将运行环境的使用权限交给用户，并和微信团队合作，让用户可以直接使用微信开发者工具一键上传、部署、调试小程序后端代码，免去操作和部署服务器的烦恼。

## SDK 和 Demo

Wafer 团队丰富了 Wafer1 的 SDK，并针对 Wafer2 设计了更加简洁的入门 Demo，同时也在开发并将提供更加高级 Demo，让用户能更加容易的使用腾讯云的其他服务。

###### 以下 Demo 包括了小程序端代码和服务端代码

#### Node.js

[Wafer2 Node.js 环境开通指引文档](https://github.com/tencentyun/wafer2-quickstart-nodejs/blob/master/README.md)

[Wafer2 Node.js 服务端 Demo](https://github.com/tencentyun/wafer2-quickstart-nodejs)

[Wafer2 Node.js 服务端 SDK](https://github.com/tencentyun/wafer2-node-sdk)

[Wafer2 Node.js 聊天室 Demo](https://github.com/tencentyun/wafer2-startup)

#### PHP

[Wafer2 PHP 环境开通指引文档](https://github.com/tencentyun/wafer2-quickstart-php/blob/master/README.md)

[Wafer2 PHP 服务端 Demo](https://github.com/tencentyun/wafer2-quickstart-php)

[Wafer2 PHP 服务端 SDK](https://github.com/tencentyun/wafer-php-server-sdk)

##### 更多语言即将支持

## 文档

欢迎进入[腾讯云文档中心](https://cloud.tencent.com/document/product/619)查看 Wafer2 文档。

## 咨询通道

对于微信小程序新解决方案带来的更多疑问，您可以直接登录[腾讯云问答](https://cloud.tencent.com/developer/ask)提问，Wafer 团队的工程师将会及时为您解答疑问。