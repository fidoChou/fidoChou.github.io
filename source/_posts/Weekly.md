---
layout: post
title: Weekly
date: 2021-06-19 21:20:31
categories: Weekly
---
#### 2021.06.21 - 2021.06.28

* [关于 React 18 你所需要知道的](/2021/06/23/前端-React-18-所需要知道的/)
* [ES2021 Features!](https://h3manth.com/ES2021/)
*  [Node v16.4.0 (Current) Released ](https://nodejs.org/en/blog/release/v16.4.0/)
	* AsyncLocalStorage 作用，使用场景？
* [28 (And Counting) Node CLI App Best Practices](https://github.com/lirantal/nodejs-cli-apps-best-practices)
* [How to Dynamically Import ECMAScript Modules](https://dmitripavlutin.com/ecmascript-modules-dynamic-import/)
* [PDF generation with Serverless + AWS Lambda and Puppeteer.](https://shubham-pandey.medium.com/pdf-generation-with-serverless-aws-and-puppeteer-cac3442b1c95)

#### 2021.06.14 - 2021.06.20

[JS 内存使用的基准测试](https://blog.webpagetest.org/posts/benchmarking-javascript-memory-usage/)
1. 根据v8 团队的研究：网络上 35% 的内存分配与 JavaScript 相关；10% 用于表示内存中的 DOM 元素；剩下的 55% 是图像。[measureUserAgentSpecificMemory](https://web.dev/monitor-total-page-memory-usage/) API 目前仅限于 JS 和 DOM 相关信息，但确实也占据页面实际内存使用量的很大一部分（约 45%）。

总结
1. 内存仍然是 Web 性能的一个尚未开发的主要领域，但这可能需要改变。随着发布的 JavaScript 数量不断增加，内存使用量也在增加。
2. 我们仍然需要更多信息来完善全貌。在任何时间点，浏览器实际可用的内存有多少？内存与关键业务和用户参与度指标有何关联？什么是内存的使用不与JavaScript和DOM的复杂性？
3. 虽然今天使用真实用户监控为您的站点获取这些数据可能存在挑战，但我在此处进行测试所采用的相同方法（一些 Chrome 标志与自定义指标配对）使您可以开始将内存相关数据提取到您的测试结果今天，我也喜欢看到人们这样做只是所以我们可以更多地了解我们是如何做的今天，其意义是什么，以及如何开始好转。


[memory-inspector for chrome](https://developer.chrome.com/blog/memory-inspector/)

#### 2021.06.07 - 2021.06.11

[Making JavaScript run fast on WebAssembly](https://bytecodealliance.org/articles/making-javascript-run-fast-on-webassembly)
https://jsonmatic.com/
https://domevents.dev/
