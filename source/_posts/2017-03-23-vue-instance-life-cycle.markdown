---
layout: post
title: "Vue Instance Life Cycle"
date: 2017-03-23 13:30:27 +0800
comments: false
categories: Vue
---

Vue的生命周期钩子有:  
1. `beforeCreate`  
2. `created`  
3. `beforeMount`  
4. `mounted`  
5. `beforeUpdate`  
6. `updated`  
7. `beforeDestroy`  
8. `destroyed`  
9. `activated`  
10. `deactivated`  

![Vue实例生命周期](https://cn.vuejs.org/images/lifecycle.png)

`activated`: keep-alive 组件激活时调用,在服务器端渲染期间不被调用。   
`deactivated`: keep-alive 组件停用时调用,在服务器端渲染期间不被调用。  
