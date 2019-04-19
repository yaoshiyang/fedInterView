# 主要面对的对象是初中级以及以上 Vue 相关的前端职业

> 选择题相关

1. ["1", null, "1.1"].map(Number)，请问输出结果是( )

   A: [“1”, “0”, “1.1”]

   B: [1, 0, 1 ]

   C: [1, 0, 1.1]

   D: other

2) Var name =”Geek+”  
   (function(){  
    if( typeof name === ” undefined”){  
    var name= “Programmer”  
    console.log(‘Goodbye’ + name);  
    } else {  
    console.log(‘Hello’+ name);  
    }  
   })()
   请问输出结果是( )

   A: Goodbye Programmer

   B: Hello Programmer

   C: Hello undefined

   D: Hello Geek+

3. Const b = “5”  
   b =”4”  
   console.log(b)  
   请问输出结果是( )

   A: “5”

   B: “4”

   C: 4

   D: 报错

4) Var a = { a: 1};  
   var b= a;  
   b = a; b.a=2;  
   console.log(a);  
   请问输出结果是( )

   A: {a: 1}

   B: {a: 2}

   C: {a: 3}

   D: 报错

5. 以下那一个是 Vue 封装的数组更新检测方法？请选择（）

   A:map

   B:slice

   C:splice

   D:some

6) String.prototype.transform = function(){ return String(this).replace(“-”,”\_”)}  
   console.log(“Hello-Geek+”.transform());  
   请问输出结果（）

   A: undefined

   B: Hello-Geek+

   C: Hello_Geek+

   D:其他

7. for(var i=0; i<5, i++){  
   setTimeout(function(){  
   console.log( i );  
   }, 100);  
   }  
   请问如下程序输出的结果是（ ）

   A: 0;1;2;3;4

   B: 0;0;0;0;0

   C: 5;5;5;5;5

   D: 4;3;2;1;0

8) var string = “string”;  
   var number = 0;  
   var bool = true;  
   console.log(number || string);  
   console.log( number && string );  
   console.log( bool || number );  
   console.log( bool && number );  
   请问如下程序输出的结果是（ ）

   A: ‘string’, 0, true, 0

   B: ‘string’, true, 0, 0

   C: ‘string’, ‘string’, true, 0

   D: ‘string’, 0, true, true

9. JavaScript 进行表单验证的目的是（ ）;

   A 把用户的正确信息提交给服务器

   B 检查提交的数据必须符合后台定义类型

   C 使得页面变得美观、大方

   D 减轻服务器压力

10) 以下不属于 JQuery 提供的方法（ ）

    A \$.get

    B \$.param

    C \$.Deferred

    D \$.deepClone

> 简单题

1. 某 JAVA 后台程序开发要求 content-type:multipart/form-data，请问前端如何封装请求头? 如果后台开发要求 content-type:application/x-www-form-urlencoded，请问前端如何封装请求头？

2) 哪些操作会造成浏览器的内存泄漏？

3. 在 Vue-router 框架下，动态路由规则 xxxx/:id，现存在 xxxx/1 跳转到 xxxx/2，问如何获取 xxxx/2 的页面数据。

4) 发送异步 C 需要依赖异步 A 和异步 B 的结果， 请问如何实现。

5. 请写出至少 3 种方式实现 CSS 中垂直居中， 请描述 CSS 中的 BEM 规范。

6) 在 Vue 框架下，某个组件 A，被组件 B 引用， 组件 B 被组件 C 引用，如果组件 A 依赖外部数据渲染动态 slot， 此时组件 C，传递给组件 B 一些组件 A 需要的 slot, 问组件 B 如何传递给组件 A？
