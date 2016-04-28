# base.js
计算机中进制之间的快速转换方法,支持1-64位进制之间的转换

~~~ sh
//64位字符转成10位字符
var bases64 = bases.fromBase("Bw==", '64');
var bases10 = bases.toBase(bases64, 10);	//458687
~~~
