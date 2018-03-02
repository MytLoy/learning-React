## JSX

## 一、什么是JSX
JSX ： JavaScript XML
基于ECMAScript的一种新特性
一种定义带属性树结构的语法
JSX不是XML或者HTML

## 二、JSX的特点
类XML语法容易接受
增强JS语义
结构清晰
抽象程度高
代码模块化

## 三、如何使用JSX
*  首字母大小写（大写：自定义组件，小写：DOM的自带元素）
*  嵌套
*  求值表达式可以用（大括号中不可以使用语句）
*  驼峰命名
*  htmlFor和className(html属性，class)
*  条件判断的四种写法
    *  三元表达式（{this.props.name ? this.props.name : "World"}）
    *  使用变量（使用函数给变量赋值）
    *  直接在大括号中调用函数（函数调用本来就是一种表达式）
    *  比较运算符（{this.props.name || "World"}）
*  万能的函数表达式

## 四、非DOM标准属性
*  dangerouslyInnerHTML（在JSX中直接插入HTML代码）
*  ref（父组件引用子组件）
*  key（提高渲染性能，给每个节点添加唯一标识）