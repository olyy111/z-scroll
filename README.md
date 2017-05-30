# z-scroll

主要修改自[better-scroll](https://github.com/ustbhuangyi/better-scroll)
增添一些实用的功能

## 用法
html引入文件变为`zscroll.js`
npm 引入模块变为`z-scroll`
构造函数变为`ZScroll`

## Event
修改以下事件
- scrollEnd 手指离开事件后触发
增加以下事件
- swipeEnd 惯性后触发

上面两个事件对应滑屏的两个阶段

## API
- setDropFlag @param Boolean 取消上下滚动限制, 可以随意的指定下拉刷新的方案

## 计划
- [ ] 添加滚动条接口
