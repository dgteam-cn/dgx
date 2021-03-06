---
lang: zh-CN
title: 介绍
---

# 介绍

## 什么是 DGX

DGX 是一套运用于前端的数据模型概念。为前端开发提供数据提取、数据维护、前后端数据交互等方案。

   。。。这里放图片。。。

### 可以用在什么地方
DGX 理论上可以用于各大现代前端架构上，目前本框架在基于 vue、vuex 的环境下进行实现，支持 vue2、vue3、nuxt2、uniapp(全端) 等项目引用。 

### 对后端的要求
DGX 要求后端严格遵守 RESTful 规范暴露接口，在非标准接口环境下使用 DGX 会要求前端写大量的兼容性代码去满足接口规范，使得使用框架失去意义。 
请参考 [接口规范要求](./restful.md) 去确认后端是否满足条件，若满足度不高可以考虑使用以下方案:

<!-- ### 接口格式不同、参数不匹配
通过[封装网络适配器](./http-adapter.md)，对请求、返回进行拦截，手动调整接口结构  -->

## 为什么要基于 Vuex 进行实现
+ 对于数据管理，开发者更倾向于 Vuex 的方案，基于 Vuex 开发有利于开发者进行过度
+ Vuex 在社区中有完善的支持，且官方提供 GUI 调试工具 (vue devtools)
+ 但是同时也会带来一些问题，一些关键字的占用与命名冲突的风险，

## 对比传统方案
文档编写中

## 对比 GraphQL
文档编写中