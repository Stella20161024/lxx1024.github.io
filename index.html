# JS模块化
## 由于没有使用到模块化的思想,两个程序员在开发过程中发生了变量污染

### 使用单独作用域来防止变量污染
   定义一个对象:利用键值对的方式添加方法----方法成为对象的属性
1. 优点:使用对象添加作用域的方法虽然防止变量全局污染
2. 缺点:. 如果在这个对象中有一些属性不希望被外界访问到,不能实现这个效果.
*  比如定义一个变量,用来记录当前计算器使用的次数,这个变量不希望被外界改变

### 使用函数的形式来完成对象属性的私有化
1. var calc = function(){
    将里面的方法一对象的形式返回
    }
2. 使用的时候要new 一个对象
    var calcObj = new calc();
3. 问题:每次使用的时候都要重新创建对象


### 使用沙箱模式(使用函数的自执行模式代替new操作)

### 在原来的对象上扩展方法
* calc是单独一个js文件里面的单独作用域的函数???
1.  var calcObj = (function (calc){ calc.方法 = function的形式添加方法并返回calc })(window.calc || {})
* 主意点:将来自执行的时候要进行传参,这个参数需要做一个处理
* 如果将来要通道第三方模块,我们需要将模块名写在自执行函数的参数上

## 程序设计中有一个思想:开闭原则
### 开:对扩展开放
### 闭:对修改闭合



## 第三方模块化管理工具
### seajs
1. 什么是seajs?   第三方模块化管理工具
* seajs.org  官网
2. 特点:
    1. 与nodejs一般书写模块代码
    2. 依赖的自动加载,配置简介清晰
    3. 兼容所有主流浏览器  IE5.5+
3. 使用步骤:
    1. 要定义一个单独的模块:
    * 关键字 define
    2. 要在模块中返回一些方法/属性/对象:
    * 关键字 exports/module.exports
    3. 如果要引用一个第三方模块
    * 关键字 require
    4. 使用seajs定义好的模块
    * 关键字 seajs.use
4. 在一个页面中引用两个以上模块,只需要将use中的第一个参数变为一个数组

# CMD规范
* seajs遵循的规范:CMD规范
### CMD规范:规范明确了模块的基本书写格式和基本交互规则
1. define可以传入方法,对象,字符串
  * define(function(require,exports,module){})
  * define({name:'jack',age:18'})
2. require用于接收第三方包提供的接口
3. exports 用来外界提供模块接口
4. module.exports用于外界提供模块的接口  (暴露接口)
* exports和module.exports的区别
1. 所以将来如果只返回一个内容,不能直接复制给exports,可以直接复制给module.exports

## 遵循CMD规范的模块都有一个特点:按需加载(懒加载)

### config  可以将一些文件的信息配置到该属性中
* seajs.config({
    base:'./文件夹',
})
* seajs.use('add.js',function(obj){})    ----- 这里的路径会自动加上面前定义的base路径
* seajs.config({
  alias:{'别名':'路径'}    ----- 将路径存在一个别名里面
})


* 把jquery文件

## requireJS的AMD规范,CMD规范尽量保持简单,并与.......
### 简单实用: 基本与seajs一样
1. define(function(require,exports,module){
    module.exports.sub = function(x,y){
        return x - y;
    }
})
2. define(function(require,exports,module){
    var sub = require('./路径');
    module.exports.sub = sub;
})
3. 引入require.js文件
    1. require(['./路径'],function(obj){
        obj.sub.sub(1,1);
    });
### 区别
1. seajs实用模块时用方法seajs.use 而requirejs直接用require关键字
2. seajs只使用一个模块时可以只传入一个字符串,但是requirejs必须传入数组
* seajs是懒加载
    1. 优点:
    2. 缺点:
* requirejs是预加载 ----  当第一次访问的时候将所有的文件加载出来
    1. 优点:第一次访问完成以后,再次访问速度会很快
    2. 缺点:第一次加载

# cmd是懒加载,amd是预加载

