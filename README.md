# vue_mvvm
手动实现vue的双向数据绑定
实现原理：在vue2.0中是利用了Object.defineProperty()这个方法重新定义了对象的获取属性值(get)和设置属性值(set)的操作来实现的。
但是在vue3.0中，是利用了es6的Proxy对象来实现的。