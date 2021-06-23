---
layout: post
title: React-18-所需要知道的
date: 2021-06-23 15:29:35
tags: React
categories: 前端相关
---
# 自动的批量更新

批量更新：React 会尝试将同一上下文中触发的多个更新合并为一个更新
好处是：
	
1. 避免页面的重复渲染
2. 状态按顺序处理，不会出现竞争态问题，最终出发渲染的是异步流程

但值得注意的是，在一个异步的方法回调中，React 并不能进行批量更新。

```js
// this code will be re-render-twice
const handleClick =()=> {
  fetch().then().catch(()=> {
    setCount(c => c+1)
    setF(f=> !f)
  })
}
```

这是因为 React 的批量更新只在浏览器的 event 中生效（比如点击时间）。但是上面的代码更新状态是事件已经处理完成，在 fetch 的回调中。
