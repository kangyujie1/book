#十月份泥巴学习总结
##安装Ubuntu系统
>自己学习安装ubuntu系统，配置源，初步了解认识linux系统开源的便利性;同时每天在英语流利说app上练习提高英语水平，打卡监督。
>学习ubuntu系统终端常用命令

##Github
* 了解Github是什么？
GitHub是一个代码托管平台，使用起来非常方便。
* 注册账号，创建库
##W3CSchool
####HTML5+CSS
>开始在w3cschool上面学习编程入门教程实战训练。  
>学习HTML5+CSS的语法知识，练习闯关的同时加深自己对于HTML5的框架的理解，和对于CSS样式使用的熟练度。主要学到新的内容有：  

* border-radius 增加圆角边框
* a href="#" 使用#符合设置固定链接
* CSS的样式继承和先后执行顺序或者单独定义class进行样式覆盖  
* CSS 多个class处理样式覆盖
* CSS 通过ID的样式属性覆盖class类的声明
* CSS 通过内联样式覆盖class类的声明，id可以覆盖掉class的声明，在style中用#+id名字来定义  
* CSS 通过使用Important覆盖所有其他样式,使用！importint来保证不给覆盖掉
####JavaScript  
1.  七种不同的data types(数据类型):      undefined（未定义）, null（空）, boolean（布尔型）, string（字符串）, symbol(符号), number（数字）, and object（对象）。
2.  JavaScript定义变量：
 中所有的变量都是大小写敏感的。这意味着你要区分大写字母和小写字母。
3.  Javascript变量：
在驼峰命名法 中，变量名的第一个单词的首写字母小写，后面的单词的第一个字母均为大写。
4.  JavaScript索引：
 使用中括号索引查找字符串中的第N个字符,计算机是从 0 开始计数，所以获取第一个字符的索引实际上是[0]。
5.  JavaScript 使用索引操作多维数组:可以把多维数组理解成是一个数组中的数组。当使用[]去访问数组的时候，第一个[i]访问的是该数组中的第N个子数组，第二个[i]访问的是第N个子数组的第N个元素。
6.  添加数组数据.push()：
var arr = [1,2,3];
arr.push(4);
返回值：
[1,2,3,4]
7.  pop() 函数：
用来“抛出”一个数组最后一个数据。
var oneDown = [1, 4, 6].pop();
现在 oneDown 的值为 6 ，数组变成了 [1, 4]
8.  shift()函数：
移出数组第一个数据
var ourArray = ["Stimpson", "J", ["cat"]];
removedFromOurArray = ourArray.shift()
返回值：
["J","cat"]
9.  unshift()函数：
移入数据到数组第一位
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();
myArray.unshift(["Paul",35]);
返回值：[["Paul",35]，["John", 23], ["dog", 3]];
10. JavaScript 函数局部变量定义
这是在函数 myTest内声明局部变量loc 的例子：function myTest() {
var loc = "foo";
console.log(loc);
}
myTest();
console.log(loc);
11. JavaScript 函数使用返回值进行赋值
12. JavaScript 队列，队列（queue）是一个抽象的数据结构，队列中的数据条目都是有秩序的。新的条目会被加到 队列 的末尾，旧的条目会从 队列 的头部被移出。
写一个函数 queue ，用一个数组arr和一个数字item作为参数。数字item添加到数组的结尾，然后移出数组的第一个元素，最后队列函数应该返回被删除的元素。
13. JavaScript 布尔boolean数据类型
布尔 值要么是true 要么是false。它非常像电路开关， true 是“开”，false 是“关”。这两种状态是互斥的。
Boolean 值绝不会写作被引号包裹起来的形式。字符串 的 "true" 和 "false" 不是 布尔值，在 JavaScript 中也没有特殊含义。（布尔值不是字符串）
14. JavaScript if语句
if(条件为真){
语句被执行
}
15. JavaScript else语句
当if语句的条件为真，大括号里的代码执行，那如果条件为假呢？
这时候需要写一个else语句，当条件为假时执行相应的代码。
16. JavaScript else if语句
举个栗子：
function myTest(val) {
if (val > 10) {
return "Greater than 10";
}
else if (val < 5) {
return "Smaller than 5";
}
else{
return "Between 5 and 10";
}
}
myTest(7);
返回值：
Between 5 and 10
17. JavaScript if、else if语句中代码的执行顺序：初始化语句只会在执行循环开始之前执行一次。它通常用于定义和设置你的循环变量。
条件判断语句会在每一轮循环的开始执行，只要条件判断为 true 就会继续执行循环。当条件为 false的时候，循环将停止执行。这意味着，如果条件在一开始就为 false，这个循环将不会执行。
计数器是在每一轮循环结束时执行，通常用于递增或递减。
if、else if语句中代码的执行顺序是很重要的。
在条件判断语句中，代码的执行顺序自上而下，所以必须区分清除代码的执行顺序。
18. JavaScript 使用switch语句进行多选项选择
function myTest(val) {
switch (val){
    case 1 :
        return "alpha"
        break;
    case 2:
        return  "beta"
        break;
    case 3:
        return "gamma"
        break;
    case 4:
        return  "delta"
        break;
}
return answer;
}
myTest(2);
返回值：
beta
19. JavaScript 在switch语句中添加default语句。
在switch 语句中你可能无法用case来指定所有情况，这时你可以添加default语句。当再也找不到case匹配的时候default语句会执行，非常类似于if/else组合中的else语句
举个例子：
function myTest(val) {
    switch(val){
        case "a":
            return "apple"
            break;
         case "b":
             return  "bird"
            break;
        case "c":
            return  "cat"
            break;
        default:
            return "stuff"
            break;
    }
return answer;
}
myTest(1);
返回值：
stuff
20. JavaScript 使用for语句循环迭代：
for ([初始化]; [条件判断]; [计数器])
21. JavaScript 循环语句综合实战
function multiplyAll(arr) {
var product = 1;
for (var i=0; i < arr.length; i++) {
for (var j=0; j < arr[i].length; j++) {
console.log(arr[i][j]);
  product *= arr[i][j];
}
}
return product;
}
code
multiplyAll([[1,2],[3,4],[5,6,7]]);
返回值：
5040
22. JavaScript 使用正则表达式操作字符串：
Regular expressions 正则表达式被用来根据某种匹配模式来寻找strings中的某些单词。
23. JavaScript 使用正则表达式选取数值：
字选择器类似于: /\d/g
/\d+/g，它允许这个正则表达式匹配一个或更多数字。
24. JavaScript 使用正则表达式选取空白字符：
空白正则表达式类似于：/\s+/g
25. JavaScript 使用正则表达式反转匹配：
\s 匹配任何空白字符，\S 匹配任何非空白字符。
####Bootstrap
1.  概述：
Bootstrap会自动获取使用者屏幕的大小,并根据屏幕的大小自动调整HTML元素的宽度和高度来适配屏幕,因此称之为--响应式布局。
2. 通过Bootstrap使图片适配手机显示：
给图片添加img-responsive的class属性,图片的宽度就能自动适配手机屏幕的宽度。
3.  通过Bootstrap添加一个按钮：
给button添加btn的class属性。
4.  添加一个Bootstrap块级元素按钮：
这些按钮仍然需要 btn class。
5.  尝试给一个Bootstrap按钮添加颜色：
为按钮添加btn-primaryclass属性且仍然需要 btn 和 btn-block 来两个属性。
6.  Bootstrap按钮多种颜色属性设定：
Bootstrap带有几个预定义的按钮颜色。其中btn-info 通常被用在用户比较可能会点击的操作上。
7.  添加一个Bootstrap警告按钮：
Bootstrap带有几个预定义的按钮颜色。
btn-danger这个按钮的颜色是用来告诉用户,该操作具有一定的危险性，比如删除键。
8.  使用Bootstrap做页面布局；为Bootstrap定义自定义CSS；
9.  使用Bootstrap span标签来创建行内元素：
通过使用span 标签，可以将多个标签放在一起，甚至可以对同一标签的不同部分进行不同的样式设置。
[块级元素的区别](https://i.imgur.com/O32cDWE.png)
10. 使用Bootstrap设计一个头部导航。
11. 在按钮上使用Font Awesome图标：
Font Awesome是一个方便的图标库。 这些图标都是矢量图形，以.svg文件格式存储。 这些图标可以像字体一样被处理,你可以使用像素设置字体大小一样指定这些图标的大小，并且这些图标可以继承父类HTML标签的字体大小。
12. 使用Bootstrap 响应式单选按钮：
在form 表单上使用Bootstrap的col-xs-*！ 这样，无论屏幕分辨率有多宽，我们的单选按钮将均匀分布在页面上。在<div class="row"> 元素中嵌入所有单选按钮。 然后将它们嵌入到<div class="col-xs-6"> 标签中。
13. 使用Bootstrap 响应式复选框：
操作方法和单选按钮一样。
14. 使用Form Controls设置输入框样式：
在button 标签中添加<i class="fa fa-paper-plane"></i>来为按钮添加fa-paper-plane的Font Awesome图标。
15. 使用Bootstrap水平排列的表单:
我们把表单中的提交按钮 button 和输入框 input 放在同一行上。我们将按照我们之前惯用的相同的方式：使用一个 div 标签,class属性为 row ，按钮和输入框则使用 col-xs-* 类定义宽度。
16. 使用Bootstrap设置一个div容器为响应式的:
将 h（n） 标签元素嵌入到一个 div 元素中，并为 div 添加一个container-fluid 的class属性。
17. 添加一个Bootstrap行容器：
现在我们将为我们的内联元素创建一个Bootstrap行。
在 h（n） 标签下创建一个带有row class属性的 div 标签。
18. 分割Bootstrap行容器：
将一个Bootstrap行分为两列显示。
在刚才添加的div 内添加两个带col-xs-6class 属性的div 标签。
19. 添加Bootstrap well容器：
Bootstrap 有一个well属性,它能是你创建的列有一种视觉深度的层次感。
20. 除了给标签元素添加class作为标识以外,还可以给标签元素添加一个ID作为唯一标识。
每个ID对于特定元素必须是唯一的，并且每页仅使用一次。
####jQuery
1.  学习jQuery和准备工作：
 是以scriptk开头，$(document).ready(function() ，以/script结束。
2.  jQuery使用addClass()方法给元素加class:
给按钮做弹回效果;
$("button")来选择按钮，然后用.addClass("animated bounce")给按钮加CSS class。
3.  jQuery根据id属性来获取元素:
使用$("#target3")选择器来选择id为target3的button元素。
4.  使用jQuery删除HTML元素的class:
可以通过jQuery的addClass()方法给元素添加class，同样的，也可以通过jQuery的removeClass()方法删除元素的class。
以下是对button元素执行的操作：
$("#target2").removeClass("btn-default");
5.  使用jQuery改变HTML元素的CSS样式：
Query用.css()的方法，能让你改变元素的CSS样式。
以下代码显示如何将颜色改变成蓝色：
$("#target1").css("color", "blue");
6.  使用jQuery设置元素不可用:
jQuery用.prop()的方法，可以让你来调整元素的属性。
以下代码显示如何禁用所有按钮：
$("button").prop("disabled", true);
7.  使用jQuery改变元素中的文本：
jQuery用.html()方法，可以让你在元素中添加HTML标签和文字，而元素中之前的内容都会被方法中的内容所替换掉。
以下代码显示如何重写和强调标题文本（使用em标签）
$("h3").html("<em>jQuery Playground</em>");
8.  使用jQuery删除一个HTML元素：
jQuery 用.remove()的方法，可以彻底删除一个HTML元素。
9.  jQuery使用appendTo()移动HTML元素:
jQuery用appendTo()方法，可以让你把选中的HTML元素附加到其他元素中。
让target4从right-well移动到left-well，我们用以下代码：
$("#target4").appendTo("#left-well");
10. jQuery使用clone()方法复制元素:
把target2从left-well复制到right-well，用以下代码：
$("#target2").clone().appendTo("#right-well");
11. 使用jQuery修改整个页面:
获取body元素。让整个body有淡出效果：
$("body").addClass("animated fadeOut");
####初级脚本算法
1.  阶乘算法挑战:
function factorialize(num) {
var n=1;
  for(var i=1;i<=num;i++){
    n=n*i;
  }
  return n;
}
factorialize(7);
运行结果：5040
2.  回文算法挑战：
function palindrome(str) {
            var newstr = str.replace(/[^0-9a-z]/gi, "");
            newstr = newstr.toLowerCase();
            for (var i = 0, j = newstr.length - 1; i < j; i++, j--) {
                if (newstr.charAt(i) !== newstr.charAt(j)) {
                    return false;
                }
            }
            return true;
        }
console.log(palindrome("eye"));
3.  设置首字母大写算法挑战:
function titleCase(str) {
            var arr = str.toLowerCase().split(" ");//全部换成小写，并且全部拆分
            var i = 0;
            for (; i < arr.length; i++) {
                var Update = arr[i].charAt(0).toUpperCase();//选中第一个字符换成大写
                 arr[i] = arr[i].replace(arr[i].charAt(0), Update);//替换成选中的一个大写字符
            }
             return arr.join(" ");//连接起来
}
titleCase("I'm a little tea pot");
4.  确认末尾字符算法挑战:
function confirmEnding(str, target) {
    var flag =true;
    for(i = str.length-1 , j = target.length-1; i>=0,j>=0;i--,j--){ //从俩个数组的最后一位开始比较
        if(str[i]!= target[j]){
            flag = false;//如果不一样就返false 且退出循环
            break;
        }
    } 
 return  flag;
}
confirmEnding("Bastian", "n");
##vscode
1.  安装vscode
2.  配置git
3.  最后学习了把vscode和github的库关联进行数据推送
4.  安装Markdown Preview Enhanced插件实现Html预览
##gitbook
1.  在Gitbook官网注册账号，新建书，再将Gitbook上的书和Github新建的库互相关联。
2.  在官网下载安装Node.js和npm
3.  安装gitbook
  
