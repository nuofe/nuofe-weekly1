<!--
 * @Description:
 * @Author: wangfuyuan
 * @Email: wangfuyuan@nnuo.com
 * @Date: 2022-06-12 14:51:06
 * @LastEditors: wangfuyuan
 * @LastEditTime: 2022-12-30 10:48:08
 * @FilePath: \nuofe-weekly1\2022\weekly-51.md
-->

# 诺诺前端周刊：2022-51 期

Add:2022-12-23

Update:2022-12-23

![202251](../images/2022/202251.jpg)

## 前端消息

- [vite项目为什么可以直接使用NODE_ENV？](https://mp.weixin.qq.com/s/mHsDAn9slvf7PnC7MM4ztA)

  > 在process.env中并没有NODE_ENV这个变量，但是我们却可以在项目的代码中使用process.env.NODE_ENV这个值来判断当前是development环境还是production环境，然后进行后续的逻辑操作。

- [一些常见的移动端适配方案，你了解吗？](https://mp.weixin.qq.com/s/NDdAOyxmnK6Ln-Yb1JhVRw)

  > 移动端设备的尺寸很多，而 UI 设计稿一般只会基于一个尺寸（一般是 375px 或 750px ）进行设计。

- [图解浏览器的多进程渲染机制](https://mp.weixin.qq.com/s/tz9wyjKHDC6GNB8fFfgtUw)

  > 观察浏览器的任务管理器可以发现，打开浏览器的一个页面需要多个进程，包括浏览器进程、GPU 进程、网络进程、渲染进程等。

## 技术解析

- [这10种神级性能优化手段，你用过几个？](https://mp.weixin.qq.com/s/HyaWlxeBgqQJPdP7qg_uPw)

  > 关于性能方面，就像建筑设计成抗震9度需要额外的成本一样，高性能软件系统也意味着更高的实现成本，有时候与其他质量属性甚至会冲突，比如安全性、可扩展性、可观测性等等。

- [这些手写JavaScript你都会吗？](https://juejin.cn/post/7137961562794852383)

  > 学会手写常见的 JS 模块好像已经快变为一个基本技能了。

- [一文搞定 Base64 编码原理足矣](https://juejin.cn/post/7168809452508807182)

  > 把图片丢进浏览器，打开sources能看到一长串字符串，这是图片的Base64编码。

## 其他

- [关于无感刷新 Token，我是这样子做的](https://juejin.cn/post/7170278285274775560)

  > JWT是全称是JSON WEB TOKEN，是一个开放标准，用于将各方数据信息作为JSON格式进行对象传递，可以对数据进行可选的数字加密，可使用RSA或ECDSA进行公钥/私钥签名。
