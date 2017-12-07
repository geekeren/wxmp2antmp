# wxmp2antmp

<p align="center">
  <a href="https://www.npmjs.com/package/wxmp2antmp"><img src="https://img.shields.io/npm/v/wxmp2antmp.svg" alt="Version"></a>
  <a href="https://www.npmjs.com/package/wxmp2antmp"><img src="https://img.shields.io/npm/l/wxmp2antmp.svg" alt="License"></a>
  <br>
</p>

## 什么是 wxmp2antmp？

> wxmp2antmp 是一个微信小程序转支付宝小程序的命令行工具

## 安装

`npm i -g wxmp2antmp`

## 使用

`w2a 微信小程序目录 支付宝小程序目录`

## 注意事项

* 支付宝小程序中的路径解析和微信小程序中的路径解析是不同的,路径必须为相对路径，如： import a from './a'，wxml中的路径会被自动处理，js 和 css 中需要自行处理。
* js 中的 wx 变量会被赋值为 my
* 微信小程序和支付宝小程序的 api 存在差异，建议自行写一套兼容库，暂无 todo 计划

## 分享交流

打赏|加小助手进微信群
:---:|:---:
<img src="https://fddcn.cn/wp-content/uploads/2017/12/WechatIMG117.jpeg" width="200"/>  |  <img src="https://fddcn.cn/wp-content/uploads/2017/12/WechatIMG116.jpeg" width="200"/>
