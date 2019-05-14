---
layout: post
title: Sqrt Data Structures
tags: [data-structures]
---

blocked. 

## 分块

### 块状链表

好东西啊. 有时候对块的总数没有要求的时候重构可以将每个点视为一个块以减小常数. 

## 莫队

### 第十四分块 (二次离线)

如果莫队的每次询问可以拆成两个前缀和的形式, 那么是可以二次离线的. 

注意**优化空间**, 这样时间也会顺便被优化掉, 就跑得飞快了. 

## 字符串

* 后缀自动机

* AC 自动机

由于多个字符串不同长度只有 $$O(\sqrt n)$$ 种, 所以很多时候以上两者暴力向上跳一次是 $$O(\sqrt n)$$ 的. 