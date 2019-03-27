---
title: Android获取打气筒的三种方式
date: 2018-04-27 16:06
tags: 
categories:
    - Android
---

## 什么是打气筒？

把我们自己定义的布局转换成一个view对象，就会用到打气筒

## Android中获取打气筒的三种方式

- view = View.inflate(getApplicationContext(), R.layout.item, null);
- view = LayoutInflater.from(getApplicationContext()).inflate(R.layout.item, null);  
- LayoutInflater inflater = (LayoutInflater) getSystemService(LAYOUT_INFLATER_SERVICE);  
                view = inflater.inflate(R.layout.item, null);  