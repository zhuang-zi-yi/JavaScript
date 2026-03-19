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
 <h3>数组增删改查</h3>
 查：加上数字下标<br>
 改：数组加下标 = 赋值<br>
 增:数组.push()可以将一个和多个元素添加到数组末尾，并返回该数组新长度<br>
 push基础语法数组.push(元素1.2,3)<br>
 数组.unshift将一个或者多个元素加到数组的开头，并返回数组新长度。<br>
 数组.unshift(数据1,2,3)<br>
 删：数组.pop()方法可以删除最后一个元素，并返回元素的值<br>
 数组.pop()<br>
 数组.shift()此方法可以删除第一个元素，并返回元素的值<br>
 数组.shift()<br>
 数组.splice(起始位置,删除几个元素)删除指定元素<br>
 数组.spilce(起始位置,删除几个元素)如果不写删除几个元素会把后面写的全部删掉<br>
 arr.splice(1,1)这个代码意思是从索引号1位置开始删，只删一个<br>
 <h3>函数</h3>
 函数是一个代码块，被设计成为执行特定任务代码块<br>
 基础指令function(){}<br>
 函数可以把相同逻辑打包起来，有利于精简代码复用<br>
 函数调用指令函数名（）<br>
 函数不调用，函数不执行<br>
 function get (nub,nub1){document.write(nub+nub1)}<br>这个nub，nub1叫形参<br>
 get(10,20)这个数字叫实参<br>
 函数的返回值<br>
 return 数据<br>
 在函数内使用return能将内部执行结果交给外部使用<br>
 return后面代码不会在执行，会结束当前函数<br>
 return函数可以没有return，形参是undefined这种情况是undefined<br>
 如果函数名字启用后面覆盖前面<br>
 如果形参过多会undefined，实参多形参，剩下的实参被忽略<br>
 break不能结束循环只能结束循环<br>
 <h3>函数作用域</h3><br>
 一段代码程序中所用的名字并不是有效和可用的，而限定这个名字的可用性代码范围就是这个名字作用域<br>
 作用域提高了程序逻辑的局部性，增强了程序的可靠性<br>
 全局有效是在所有代码执行环境和局部有效在函数代码环境就是局部作用域，因为跟函数相关，所以叫函数作用域<br>
 <h3>变量的坑！！如果函数内部，变量没有声明，直接赋值，也能当全局变量看</h3><br>
 函数里头形参也算局部变量<br>
 在函数中找作用域，在能够访问到的情况下，先局部，局部没有再找全局作用域<br>
变量访问原则取决于就近原则<br>
 <h3>匿名函数</h3>
 基础语法function(){}<br>
 没有函数名字的函数<br>
 没有名字的函数是无法直接使用<br>
 使用方法函数表达式<br>
 立即执行函数<br>
 函数表达式：将匿名函数赋值给一个变量，并通过变量名称调用，叫做函数表达式<br>
 变量名字（实参，实参）<br>
 具名函数的调用可写到任何位置，匿名函数函数表达式不可以<br>
  立即执行函数<br>
  避免全局变量之间的污染<br>
  基础语法(function(){})()<br>
  立即执行函数必须加分号：立即执行函数可以拥有名字<br>
  <h3>逻辑中断</h3><br>
  <img width="419" height="239" alt="QQ_1772596175046" src="https://github.com/user-attachments/assets/9f75790b-60f7-4e32-a452-ea220dc38284" /><br>
逻辑运算符的短路<br>
短路值存在&&和||中，满足一定条件让右边代码不执行<br>
&&左边为false短路，||左边为true就短路<br>
如果&&2个都是真则返回最后一个值，||两个都是真返回第一个<br>
<h3>转换成boolean型</h3>
0，undefined，null，flase，Nan,转换成布尔值为false其他都是true<br>
null字符转换0，减法会将空字符串变成0,nudefined 加上 1会出现NaN<br>
null + 1 == 1<br>
<h3>对象</h3>
对象（object）是JavaScript的一种数据类型<br>
可以理解成一种无序的数据集合，数组是有序的数组集合<br>
对象基础语法let obj = {}<br>
对象本质是无序数据集合，操作数据是增删改查<br>
查询对象;对象.属性<br>
简单理解就是获得对象里面的属性值<br>
修改对象基础语法；对象名.属性=新值<br>
增入属性基础语法；对象名.新属性 =新值<br>
删除对象基础语法；delete 对象.属性名<br>
查询的另外一种写法<br>
对象名称[`属性名`]<br>
对象名,属性名<br>
对象的使用方法<br>
方法的调用对象名.方法名<br>
<h3>遍历对象</h3>
for (let k in obj){}<br>
for in 不推荐遍历数组原因是因为k拿到是是字符串<br>
<img width="274" height="202" alt="QQ_1772635449268" src="https://github.com/user-attachments/assets/238ede24-9b0a-4a1f-b696-7f2b53cdf83d" /><br>
 k存的是属性名在变量里头，在数组里面存着是下标<br>
遍历变量需要console,log(obj[k])<br>
<h3>内置对象</h3>
JavaScript内部提供的对象，保安各种属性给开发者用<br>
内置对象Math<br>
math对象是JavaScript提供的数学对象<br>
math对象包含方法有：
random；生成0-1之间的随机数（包含0不包含1）<br>
ceil；向上取整<br>
floor；向下取整<br>
max；找最大数<br>
min；找最小值<br>
pow；幂运算<br>
abs；绝对值<br>
round:四舍五入<br>
null是一个空对象<br>
<h3> 内置对象生成随机数范围</h3><br>
<img width="785" height="386" alt="4be89974-fc8f-44a6-8065-22d4bd4e0418" src="https://github.com/user-attachments/assets/4dc56611-66f3-4a82-aa1d-a5e4cb48dc49" /><br>
简单类型又叫基本数据类型或值类型，复杂类型又叫做引用类型<br>
栈；由操作系统自动分配释放存储放函数参数值。局部变量值。其操作方式类似于数据结构中的栈，简单数据类型存放到栈里<br>
堆；存储复杂类型（对象），一般由程序员不释放，由垃圾回收机制回收，引用数据类型放到堆里头<br>
<h3>web api</h3><br>
尽量用const原因是<br>
const语义化更好<br>
实际开发中react基本const<br>
web api作用就是用js操作HTML和浏览器<br>
分类为bom（操作浏览器）和dom（操作文档）<br>
dom作用开发网页内容特效和实现用户交互<br>
dom树<br>
将HTML以树状态直观表达，我们称之为文档树或这个dom树<br>
ddom对象根据html标签生成js对象<br>
document对象<br>
是dom的最大对象<br>
获取dom对象<br>
 选择匹配第一个标签<br>
document，queryselector（`css选择器`）<br>
包含一个或者多个css选择器字符串<br>
css匹配第一个元素，如果没有匹配到返回null<br>
匹配多个元素document.quertselectorAll(css元素)<br>
得到是伪数组<br>
有长度有索引号的数组<br>
但是没有pop和push<br>
其他获得dom方式<br>
document,getElementById(`nav`)<br>
根据id获取一个元素<br>
document,getElementsByTagName(`div`)<br>
根据标签获得一个元素<br>
document,getElementsByClassName(`w`)
根据元素名称获取元素<br>
<h3>操作元素内容</h3><br>
 对象.innerText属性<br>
 对象.innerText = 新值<br>
 innertext不解析标签<br>
 元素.innerHTML<br>
 inner.HTML会解析标签<br>
<h3>操作元素属性</h3><br>
还可以通过js设置修改元素标签，比如说src更换图片
常见属性href,title,src等<br>
对象.属性=值<br
<h3>操作元素样式属性</h3>
通过style属性操作css<br>
通过类名操作css<br>
通过classList操作css<br>
<h4>通过style操作css</h4>
 对象.style.样式属性=值（一定情况下后面值要加<h4>字符串</h4>）<br>
backgroundColor采取小驼峰命名方案，多组单词小驼峰方案<br> 
<h3>操作类名</h3>
如果修改样式比较多直接通过style修改比较繁琐可以修改css类名
元素.className = `类名`<br>
class是使用新值换旧值，如果要求添加个类需要保留之前类名，会覆盖原来的属性<br>
div.classnam = `老值，新值`要之前的老值<br>
 操作元素样式属性<br>
 通过className容易覆盖以前的类名，我们可以通过classList方式<br>
 追加一个类：元素.classList.add(`类名`)<br>
 删除一个类:元素.classList.remove(`类名`)<br>
 切换一个类:元素.classList.toggle(`类名`)<br>
 classlist追加一个类名<br>
 parseInt向下取整<br> 
 <h3>操作表单元素</h3>
 表单很多时候也要修改属性，比如说点击眼睛可以看见密码本质是把表单变成文本框<br>
 获取dom对象，属性名<br>
 设置dom对象.属性名=新值<br>
 表单.value =`用户名字`<br>
 表单.type = `password`<br>
 狼途t88感觉手感挺好，就是打字确认感不强<br>
 获取表单内容只有`value`<br>
  <h3>自定义属性</h3><br>  
  <img width="1094" height="531" alt="image" src="https://github.com/user-attachments/assets/218113fc-da58-49f3-94e6-d7734dc2dba8" /><br>
  <h3>间歇函数</h3><br>
setinterval(函数,间隔时间)<br>
每间隔一段时间执行一次函数<br>
1000毫秒等于1秒<br>
定时器其实返回的是一个id数字<br>
let 变量名 =setinterval(函数,间隔时间)<br>
clearinterval(变量名)<br>
获取button元素用的是innerHTML<br>
<h3>btn.disabled = false禁用按钮</h3><br>
这种返回值是true<br>
<h3>事件监听</h3>
事件是再编程时系统内发生的动作或发生的事情<br>
比如是用户在网页上单机一个按钮<br>
事件监听基础语法：元素对象.addEventListener(`事件类型`，要执行的函数)<br>
事件监听三要素：
事件源：那个dom元素被事件触发了，要获得dom元素<br>
事件类型：用什么方法触发，比如鼠标单击click，鼠标经过mouseover<br>
调用的函数：要做什么事情<br>
事件类型要加引号<br>
鼠标点击click<br>
<h3>事件类型</h3>
click鼠标点击<br>
mouseenter鼠标经过<br>
mouseleave鼠标离开<br>
<h3>表单获得光标</h3>
docus获得焦点<br>
blur失去焦点<br>
<h3>键盘触发</h3>
Keydown键盘按下触发<br>
Keyup键盘抬起触发<br>
<h3>表单输入触发</h3><br>
 input<br>
 next.click()调用函数<br>
<h3>事件对象</h3>
事件对象是个对象，这个对象里有事件触发时的相关信息<br>
列如鼠标点击事件中，事件对象就存了鼠标点哪里位置的等信息<br>
使用场景<br>
可以判断用户按下哪个键，比如按下回车键可以发布新闻<br>
可以判断鼠标点击了哪个元素 ，从而相应操作<br>
获取事件对象<br>
在事件绑定的回调函数中第一个参数就是事件对象<br>
一般命名event，ev，e<br>
元素.addEventListenere(`click`,fuction(e){})<br>
只有在事件监听里头才能是事件对象<br>
获取事件对象<br>
type获取当前事件类型<br>
clientX/clientY获取光标相对于浏览器可见窗口左上角的位置<br>
offsetX/offsetY获取光标相对于当前dom元素左上角的位置<br>
key用户按下键盘的值k eycode已经废弃<br>
去除两边内容空格<br>
const str =`         pink     `<br>
console.log(str.trim())<br>
输出pink<br>
trim清除内容中空格<br>
HTML的最大显示cols = `30`,rows=`10`<br> textarea<br>
<h3>环境对象</h3><br>
指的是函数内部变量this，它代表函数运行所处环境<br>
搞清this指向能让代码简洁<br>
普通函数里面this指向的是window<br>
this指向的是函数调用者<br>
谁调用，this就是谁<br>
直接调用函数，其实相当于window，使用this变成window<br>
<h3>回调函数</h3>
如果将函数A作为参数传递给函数B时，我们称函数A为回调函数<br>
我的发为什莫不能插入图片了<br>
css:ck.checked选择被点击确认的表单<br>
<h3>事件流</h3>
从大往小找，捕获<br>
事件流指的是事件完整执行过程中的流动路径<br>
冒泡是子到父亲<br>
<h3>事件捕获</h3>
事件捕获就是从dom的根元素开始执行对应事件<br>
捕获要用对应代码看见<br>
基础代码DOM.addEventListener(事件类型，事件处理函数，是否使用捕获机制（true）默认是false)<br>
<h3>事件冒泡</h3><br>
当一个元素事件被触发时候，同样的事件将会在该元素的所有祖先元素依次触发，这一过程被称为事件冒泡<br>
当一个元素触发事件后，会依次向上用所有父级元素同名事件<br>
<h3>事件冒泡</h3>
因为默认有冒泡模式的存在，会导致父元素<br>
想要把事件就限制在元素内，就要组织事件冒泡<br>
组织传播：：事件对象.stopPropagation（）<br>
组织传播能阻止冒泡和捕获<br>
事件对象.stopropagation<br>
<h3>解绑事件</h3>
on事件方式直接用null覆盖解绑事件<br>
移除事件btn.removeEventListener(事件类型，函数)//匿名函数无法移除<br>
鼠标经过的事件的区别<br>
mouseover和mouseout会有冒泡事件<br>
mouseenter和mouseleave没有冒泡事件<br>
<h3>二种注册事件的区别</h3>
传统on注册(L0)<br>
同一个对象，后面注册的事件会覆盖前面注册（同一个事件）<br>
直接使用null覆盖偶就可以实现事件的解绑<br>
都是冒泡阶段执行的<br>
事件监听注册（L2）
语法addEventListener(事件类型，事件处理函数，是否使用捕获)<br>
后面注册的事件不会覆盖前面注册的事件<br>
可以通过第三个参数去确定是在冒泡或者捕获阶段执行<br>
必须使用removeEventListener(事件类型，事件处理函数，获取捕获或者冒泡阶段)<br>
匿名函数无法解绑<br>
<h3>事件委托</h3><br>
事件委托就是利用事件流的特性解决一些开发需求的知识技巧<br>
我们给父亲元素注册事件，当我们触发子元素时候，会冒泡到父元素身上，从而触发父亲元素的事件<br>
tagName标签名字<br>
<h3>我们可以实现：：事件对象.target.tagName可以获得真正触发事件元素</h3><br>
 data-id = `0`,div.dataset.id <br>
<h3>阻止默认行为</h3>
e.preventDefault阻止默认行为<br>
 <h3>其他事件</h3><br>
 页面加载事件<br>
 可以加载外部资源，加载完毕时触发的事件<br>
 有些时候需要等页面资源全部处理完了做一些事情<br>
 老代码喜欢把script写在head中，使dom元素找不到<br>
 事件名：load<br>
 监听页面所有资源加载完毕：
 给window添加load事件<br>
 window.addEventListener(`load`,function(){})等待页面所有资源加载完毕，就回去执行回调函数<br>
 页面加载事件<br>
 当初始HTML文档被完全加载和解析完成之后，DOMContentLoaded事件被触发，而无需等待样式表。图片等完全加载<br>
 事件名称DOMContentLoaded<br>
 给document添加DOMContentLoaded<br>
 基础写法document.addEventListener(`DOMContentLoaded`,fuction(){})<br>
 <h3>元素滚动事件</h3>
 滚动条在滚动的时候持续触发的事件<br>
 事件名称scroll<br>
 监听整个页面滚动<br>
 window.addEvemt;osyemer(`scroll`,function(){})<br>
 scrollLeft（被卷的左）和scrollTop(被卷去的头)的区别
 获取被卷进去的大小<br>
 获取元素内容往左，往上滚动出去看不到的距离<br>
 这两个值是可以读写的<br>
 overflow:scroll1创建滚动条让css<br>
 拿到HTML标签写法document,documentElement返回的是数字型不带单位<br> 
 可给这个HTML赋值，需要给数字型不带单位<br> 
 scrollTo()方法可以把内容滚动到指定的坐标<br> 
 window.scrollTo(0,1000)<br> 
 元素.scrollTo(x,y)<br> 
 <h3>页面尺寸事件</h3><br> 
 会在窗口尺寸改变时候触发事件：
 resize<br> 
 window.addEventListener(`resize`,function)<br> 
 检测屏幕宽度<br> 
 window.addEventListener(`resize`,function(){<br> 
 let w = document.documentElenment.clientWidth<br> 
 })<br> 
 获取宽高<br> 
 获取元素的可见部分宽高（不包括边框，margin，滚动条等）<br> 
 clientWideth和clientHeight<br> 
 <h3>元素尺寸</h3>
 元素尺寸与位置<br> 
 offsetWidth和offsetHeight获取位置（包含边框，padding和border）<br> 
 获取出来的是数值<br> 
 offsetLeft和offsetTop是只读属性<br> 
 加入定位的祖先元素 获取受到父亲的影响<br>
 <h3>总结各个定位</h3><br>
 <img width="1021" height="324" alt="image" src="https://github.com/user-attachments/assets/5bafd2c2-005e-468d-a2dd-5379c12de4e7" /><br>
  自定义属性使用e,target.dataset.name<br>
  专门滑动属性让页面滑动html{scroll-behavior: smooth}<br>
 属性选择器：类名[属性名]<br>
 <h3>日期对象</h3><br>
 日期对象，可以让网页显示日期<br>
 可以得到当前系统时间<br>
 <h4>实例化</h4><br>
 在代码中获得new关键字时，一般这个操作称为实例化<br>
 创建一个事件对象<br>
 const date = new Date（）<br>
 获得指定时间<br>
 const date = new Date(`2008-8-8`)<br>
 日期对象方法<br>
 <img width="1046" height="526" alt="image" src="https://github.com/user-attachments/assets/092f16b7-f059-4218-9ed4-d79396f482df" /><br>
 getMonth数值要加一因为取值为0到11<br>
 getDay星期天取值为0<br>
 date.toLocaleString()自动补0函数<br>
<h3>时间戳</h3><br>
是指1970年01月01日00时00分00秒起至现在的毫秒数，他说一种特殊的计量时间方式<br>
能够获得当前时间戳<br>
1000ms就是一秒<br>
算法：将来的时间戳 - 现在的时间戳 = 剩余时间毫秒数<br>
三种方法获取时间戳<br>
getTime()方法<br>
const date = new Date()<br>
-----------------------------<br>
简写+mew Date()无需实例化（`2022-4-1 18：30：00`）<br>
---------------------------------<br>
使用Date.now()只能获得当前的时间戳，而前两种可以返回指定时间的时间戳<br>
<h3>节点操作</h3><br>
dom节点<br>
dom树里面的每一个内容都称为节点<br>
<img width="1109" height="514" alt="image" src="https://github.com/user-attachments/assets/2021fd0d-4f73-4189-a56a-8b1b83eb5b49" /><br>
所有属性比如href。class就是属性节点<br>
文本节点就是所有文本<br>
 <h3>查找节点</h3><br>
 父节点查找parentNode属性<br>
 返回近一级的父节点，找不到返回null<br>
 子元素.parentNode<br>
 ------------------------<br>
 查找结点<br>
 子节点查询<br>
 childNods获取所有子节点包括文本节点（空格换行）.注释节点等<br>
 children属性获取所有元素节点，返回的是一个伪数组<br>
 父元素.children<br>
 查找节点<br>
 兄弟关系查找：下个一个兄弟nextElementSibling属性<br>
 上一个兄弟节点previousElementSibling属性<br>
 <h3>增加节点</h3>
 很多情况下需要在页面新增元素<br>
 一般情况下新增节点<br>
 先创建新节点<br>
 把创建的新节点放入指定的元素内部<br>
 创造节点方法：document，createElement(`标签名`)<br>
 <h3>追加节点</h3>
 想要在界面看到，还需要插入到某个父元素中<br>
 插入到父元素的最后一个子元素<br>
 父元素.appendChild(要插入的元素)<br>
 插入到父元素中某个子元素的前面<br>
 父元素.insertBefore(要插入的元素，在哪个元素前面)<br>
 children[0]//insertBefore获得的数组<br>
<h3>追加节点</h3><br>
特殊情况下，我们新增节点按照如下操作<br>
复制一个原有的节点<br>
把复制节点放入指定元素内部<br>
克隆节点元素.cloneNode(布尔值)<br>
clonNode会克隆出一个根原标签一样的元素，括号传入布尔值<br>
若为true则代表克隆时会包含后代节点一起克隆<br> 
若是false则代表克隆不包括后代节点<br>
默认值是false<br>
<h3>删除节点</h3><br>
在一个节点在页面中不需要的时候，可以删除他<br>
在JavaScript原生dom操作中要删除元素通过父元素<br>
语法父元素.removeChild(要删除元素)<br>
删除节点和隐藏节点dsiplay：none有区别，一个是隐藏，删除是在HTML移除<br>
<h3>M段事件</h3><br>
移动端有特殊事件<br>
触屏事件touch（触屏事件），Android和ios都有<br>
touch对象代表一个触摸点。触摸点可能是一根手指也有可能是一根触摸笔。
触屏touch事件<br>
touchstart手指触摸dom元素时触发<br>
touchmove手指在一个dom元素上滑时触发<br>
touchend手指从一个dom元素上移开触发<br>
<h3>js插件</h3><br>
swiper插件<br> 
<img width="836" height="365" alt="image" src="https://github.com/user-attachments/assets/06042996-b2ed-4b32-8a86-440137d5520e" /><br>

 






  

 
 









 
 

 

 
 
 
 
  
  
      
  
 
 
 
 
 
 
 
 
 
  
 
 
  
 
 
 
 
  
 
  
 
 












  
   
  
    
 

 
   




 

                          
 

      

 
 
 


                                                                          










 










