# react #
> react [中文网](https://react.docschina.org/ "react中文网")

1. react核心技术
    - 响应式 UI
    - 虚拟 DOM
    - 组件
2. JSX简介。
	   ----------
 JSX，是一个 JavaScript 的语法扩展。我们建议在 React 中配合使用 JSX，JSX 可以很好地描述 UI 应该呈现出它应有交互的本质形式。JSX 可能会使人联想到模版语言，但它具有 JavaScript 的全部功能。
 JSX 可以生成 React “元素”。

 1.在 JSX 中嵌入表达式

	HTML文件 
	<div id="root"></div>
	
	`const name = 'Josh Perez';`
	`const element = <h1>Hello, {name}</h1>;`
	`ReactDOM.render(
	  element,
	  document.getElementById('root')
	);`
	
	输出  Hello, Josh Perez

2.JSX 也是一个表达式  
  在编译之后，JSX 表达式会被转为普通 JavaScript 函数调用，并且对其取值后得到 JavaScript 对象。  
  也就是说，你可以在 if 语句和 for 循环的代码块中使用 JSX，将 JSX 赋值给变量，把 JSX 当作参数传入，以及从函数中返回 JSX：

3.JSX 特定属性
  
	1.使用引号，将属性值指定为字符串字面量：
	 `const element = <div tabIndex="0"></div>;`   
	2.大括号性值中插入一个 JavaScript 表达式:  
	 `const element = <img src={user.avatarUrl}></img>;`  
	*注意：不要在大括号外面加上引号*

	
    警告：  
	因为 JSX 语法上更接近 JavaScript 而不是 HTML，所以 React DOM 使用 camelCase（小驼峰命名）来定义属性的名称，而不使用 HTML 属性名称的命名约定。
	例如，JSX 里的 class 变成了 className，而 tabindex 则变为 tabIndex。
 4.使用 JSX 指定子元素
	
   





  
   
