今天是2026/2/22我又开始从新看JavaScript了.这是从新的第三遍<br>
javascript是一种运行在客户端的编程语言,实现人机交互<br>
javascript的组成分为ecmascript(规定了js基础语法)语言和web apis<br>
而web apis分为DOM(操控文档,页面元素移动大小添加操作)和BOM(操作浏览器页面创空检测窗口宽度，存储数据到浏览器)<br>
javscript书写位置<br>
1.直接写在html文档里用<script>套在里头写在body里头<br>
//js基础指令alert(``)页面弹出警示框<br>
2，代码写到以.js结尾的文件中<br>
<script sre=文件位置></script>外部js<br>
3.内联javascript代码写在标签内部<br>
javascript单行注释//<br>
作用在这一行中全部注释<br>
javascript多行注释<br>
/*内容*/在中间的内容全部注释<br>
javascript的结束符号可以写也可以不写,结束符号为;<br>
<img width="506" height="456" alt="QQ_1771900177690" src="https://github.com/user-attachments/assets/12abe5d0-651c-47ef-a1c4-a477bb9726a8" /><br>
<h3>输出文档语法基础document,write(`你要写的内容`)</h3><br>
<h3>基础警示框基础语法alert(`要输出内容`)</h3><br>
<h3>控制台输入语法console.log(`控制台打印输出`)</h3><br>
<h3>基础输入基础语法prompt(`请输入名字`)</h3>
在以后的javascript中尽量用let,var出现的问题.主要可以先试用在声明.var声明过的变量可重复声明不是很合理.<br>
变量一次只能取一个值,如果想多次取值用数组[]<br>
数组是一组数据存储在单个变量名下的方式<br>
<h3>声明数组基础指令let 数组名 = [数据1，数据2，数据3]</h3>
数组是有序号有序的每一个数组元素都有一个编号，从0开始计算<br>
使用数组 数组名字[索引号]，从0开始<br>
元素；数组中保存每个数据都叫数组元素<br>
下标；数组中数组的编号<br>
长度；数组中数据的个数；可以用length查看<br>
<h3>常量<br>
使用const声明的变量叫做常量<br>
当某个变量永远不会改变的时候，可以使用const来声明而不是let<br>
使用const声明的变量叫常量<br>
<h3>数据类型</h3><br>
number数字型<br>
string字符串型<br>
boolean布尔型<br>
undefined未定义型<br>
null空类型
<h3>引用数据类型</h3>
object对象<br>
带有数字的统一成为数字型<br>
 <h3>算数运算符</h3>
<img width="777" height="327" alt="image" src="https://github.com/user-attachments/assets/817a7d32-4b90-4200-a2c8-684b32ff5912" /><br>
算数运算符号优先级先乘除后加减，有小括号先算小括号<br>
<H3>数据类型NaN</H3><br>
NaN代表一个计算错误他是一个不正确或者未定义的数学操作所得到的结果，任何对于NaN的操作都是错误<br>
<h3>数据类型字符串类型</h3>
字符串类型string//通过``和""包括起来的数据都叫字符串，单引号和双引号没有区别.<br>
转义符/的意思是后面那个命令正常打印出来<br>
字符串连接+运算符可以实现字符串的拼接<br>
<h3>模版字符串</h3>
<img width="776" height="395" alt="QQ_1772111164732" src="https://github.com/user-attachments/assets/e61e6b1c-90c2-4c20-8757-e6e356ff7f29" /><br>
外名用``包含，内部${变量名}<br>
<h3>数据类型布尔型(boolean)</h3>
表示肯定或者否定是在计算机对应的就是布尔类型.<br>
他用两个固定的值true和false，表示真的true，假的就是false<br>
<h3>>数据类型未定义型(undefined)</h3><br>
未定义是比较特殊类型只有一个undefined<br>
在声明变量下不给值的情况下默认就是undefined<br>
<h3>数据类型null</h3>
null属于空的<br>
undefined表示没有赋值<br>
null表示赋值了，但是内容为空。<br>
<h3>检测数据类型</h3>
使用typeof关键字检测数据类型
作为运算符 typeof x 检测类型<br>
函数类型 typeof(x)<br>
有没有括号都是结果一样的<br>
<h3>类型转换</h3>
 prompt转换过来的数据默认是字符串型，此时不能直接进行加法运算<br>
<h3>隐式转换</h3><br>
某些字符被执行时，系统内部自动将数据类型进行转换。
只要加号2边有字符串，会默认把另外一个转换成字符串。
除加号以外的算数运算符比如-,*,/等会默认将数据转换成数字类型<br>
+号作为正号解析可转换成数字型<br>
任何数据和字符串相加结果都是字符串<br>
<h3>显示转换</h3><br>
过度依赖隐式转换是不严谨的<br>
概念自己写代码告诉系统该转换成什么代码<br>
<h3>运算符</h3><br>
赋值运算符；对变量进行赋值的运算符<br>
=把右边给左边<br>
其他运算符<br>
+=赋值例子<br>
let num =1<br>
num += 1或者num = num + 1<br>
<h3>一元运算符</h3>
所需表达式个数，分为一元二元，三元运算符<br>
二元运算符 let num = 10 + 20<br>
一元运算符 正号负号 ++（自增）--（自减）<br>
前置自增<br>
++num 和 num++（）++在前先加，++在后后加<br>
前置自增靠计算先自能加一，后置自增先计算后加一。<br>
前置加加和后置加加单独使用没有区别<br>
<img width="458" height="240" alt="QQ_1772192202293" src="https://github.com/user-attachments/assets/f5e9c22a-76af-4498-aaba-d0e42373f86e" /><br>
<h3>比较运算符</h3><br>
<img width="343" height="256" alt="QQ_1772192365466" src="https://github.com/user-attachments/assets/c0333340-a256-4758-b1b7-b2c38aa827ae" /><br>
===全等需要所有东西都相等类型也要相等，==相对等于<br>
NaN不等于任何人包括他自己<br>
<h3>逻辑运算符</h3>
逻辑运算符解决多重条件判断<br>
正确写法nun > 5&& nub > 100 
 <h3>逻辑符号</h3>
&&逻辑与 叫法并且  要求两边都为true结果才是true <br>
||逻辑或 叫法或者 符号两边有一个是true 才是true <br>
!逻辑非 叫法取反 true变false false变true<br>
<h3>运算符的优先级</h3>
<img width="629" height="290" alt="QQ_1772196069293" src="https://github.com/user-attachments/assets/18a8ce68-3139-4b49-9aaf-ef1d86fdbc67" /><br>
先&&再||<br>
<h3>语句</h3>
表达式是可以被求值的代码,javascript会计算出一个结果,<br>
<h3>语句</h3>
是一段可执行的代码<br>
表达式可以求值，语句不一定用值。<br>
<h3>分支语句</h3>
有时候要根据条件选择执行代码,这种叫做分支结构<br>
某段代码被重复执行叫做循环结构<br>
分支语句包含if分支,三元运算符,switch语句<br>
<h3>if分支语句</h3>
if语句有三种使用方法；单；双；多分支<br>
if（条件）{<br>
满足代码条件}<br>
括号里头条件为true时候，进入大括号执行代码。<br>
小括号结果不是布尔类型，小括号会隐形转换为布尔<br>
除了0所有数字都为真,空字符串也为flase<br>
<h3>双分支if语法</h3>
if(条件){满足条件要求执行代码<br>
}<br>
else{不满足条件执行代码}<br>
<h3>if多分支</h3><br>
<img width="899" height="439" alt="QQ_1772198876788" src="https://github.com/user-attachments/assets/d0961c21-048e-4f9f-83fc-b4b0d730f7ad" /><br>
<h3>三元运算符</h3><br>
条件?满足条件执行的代码:不满足条件执行的代码<br>
<h3>switch语句</h3>
switch(数据){<br>
case 值1:<br>
     代码1<br>
     break<br>
case 值2:<br>
     代码2<br>
     break<br>
default:<br>
      代码n<br>
      break<br>
}<br>
找到小括号里头数据全等的case值，并执行相当于对应的代码<br>
若没有全等===的则default执行<br>
break的意思是终止/穿透<br>
<h3>循环结构</h3>
断点调试<br>
打开浏览器摁f12<br>
点到sour一栏<br>
选择代码文件<br>
while循环<br>
 while:在期间，所以while循环在满足条件期间，重复执行某些代码。<br>
 while循环基础指令<br>
while(循环条件){<br>
要重复执行代码(循环体)<br>
 }<br>
 只要满足循环条件为true才会进行循环体执行代码<br>
 while代码执行完不会退出，而是回到小括号判断条件是否满足，满足又去执行大括号代码，然后回到小括号判断条件<br>
 <h3>while循环三要素</h3>
 1.变量起始值<br>
 2.终止条件<br>
 3.变量变化量<br>
 <h3>循环退出</h3>
 break退出循环<br>
 continue结束本次循环，接着下一次循环下面接着来<br>
 <img width="323" height="189" alt="QQ_1772340423237" src="https://github.com/user-attachments/assets/dc10f70c-51f7-4b9a-856d-0ad2bdebaef0" /><br>
 continue死循环图<br>
 <h3>for循环</h3>
 作用；重复执行代码<br>
 for(变量起始值；终止条件；条件变化量){循环体}<br>
 continue退出本次循环,break退出整个for循环<br>
 while(true)来构造无线循环<br>
 for(;;)也可以来制造无线循环用break退出循环<br>
 for(外部声明记录次数变量；循环条件；变化值){<br>
 for (内部声明记录循环次数变量;循环条件;变化值){循环体}<br>
 }<br>
 <h3>数组</h3><br>
 数组（Array）是一种按顺序保存数据，数据类型<br>
 声明数组let 数组名 = [数据1，数据2，数据3]<br>
 使用new Array构造函数声明<br>
 let arr =New Array(1,2,3,4)<br>
 通过下标获取数据<br>
 一些术语：元素数组中每个保存的数据叫数组元素，下标，数组中数据编号。长度，数据中数据的个数，通过数组length获得<br>
 <h3>遍历数组</h3>
 ~~~css
 
 
  

 
 
 













 










 










