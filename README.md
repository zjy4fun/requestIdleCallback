演示 requestIdleCallback 的作用

native GUI 和 v8引擎的渲染是互斥的，requestIdleCallback 可以利用浏览器的空余时间去执行任务
