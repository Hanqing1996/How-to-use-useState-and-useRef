#### useState 和 useRef 的简介如下，不做赘述
* [useState](https://github.com/Hanqing1996/useState-demo)
* [useRef](https://github.com/Hanqing1996/useRef-demo)

#### 用法
* useRef 作为全局变量（在A函数中变化后在B函数中立即能读取）
> useRef相当于全局变量，但是注意这个全局变量是在组件外部定义的全局变量（如果是组件内部定义的，那每次组件重新render都会导致该变量被重置）
* useState 作为UI数据（useState 的值，更新后一定触发 render）
