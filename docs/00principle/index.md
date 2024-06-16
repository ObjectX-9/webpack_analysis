---
nav:
  title: 🎉 构建&原理解析
  order: 1
group:
  title: 00更新日志
  order: 0
title: 1.更新日志
order: 1
---
<Alert type="error">
  <span style="color: red">通过理解react核心概念、工作流程、工作关键、相关算法深入理解react的工作原理，因为react18默认并发模式，所以我们后续的讲解都是以并发模式为基准的</span>
</Alert>

## 01源码环境
- ✅ 1.源码调试环境搭建
- ✅ 2.源码调试流程

## 02前置概念
- ✅ 1.JSX运行原理
- ✅ 2.图解几个核心包之间的关联
- ✅ 3.react的启动流程&三大全局对象

## 03render阶段-scheduler调度
- ✍️ 1.概念：位运算&lane模型
- ✍️ 2.概念：update是如何统一的？
- ✍️ 3.流程：scheduler调度流程
- ✍️ 4.关键：scheduler调度关键
- ✍️ 5.算法：scheduler调度算法

## 04render阶段-reconciler调和
- ✍️ 1.概念：可中断
- ✍️ 2.概念：增量渲染
- ✍️ 3.概念：时间分片
- ✍️ 4.概念：双缓冲树
- ✍️ 5.流程：reconciler流程
- ✍️ 6.关键：reconciler关键
- ✍️ 7.算法：diff算法

## 05commit阶段
- ✍️ 1.概念：离屏DOM树
- ✍️ 2.流程：commit的三大阶段
- ✍️ 3.关键：DOM的渲染&回调处理

## 06组件的渲染流程
- ✍️ 1.类组件的渲染流程
- ✍️ 2.函数的渲染流程

## 07Hooks原理


<Alert type="success">
  <span style="color: green">
  暂时实现了这些，如果问题可以在github提<a src="https://github.com/ObjectX-9/react18_analysis_book/issues">issue</a>
  </span>
</Alert>
