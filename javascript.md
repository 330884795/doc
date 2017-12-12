<h1>Javascript


<pre>
5种基本类型: 只用声明变量  不用声明变量类型 
   字符串：'qweasd' (包括字母,数字,标点符号,空格 但是内容必须包含在单引号 或者双引号之间)
   数字: 1234 整型或者浮点型
   布尔: true false
   数组: Array(size)  var t=Array(4|''); t[index]
   对象：Object()  对象有属性  有方法 var tt=Object() tt.name=xxx  tt.age=xx tt.face(){ alert('no face') }
</pre>
<pre>
语句:  语句分号结尾 ;  多条语句可以放在同一行 分号结尾
注释:  // 单行注释   /* */多行之间的注释
变量:  会发生变化  先声明在引用 var varname=value; 
操作:
	算数操作符:
	+，-，*，/   var a=(1+5)*2
	自加 var++ var-- --var ++var
	支持拼接 var aa="tt"+"cc"
	比较操作符:
	> < >= <= = == === !=  eq ne lt le gt ge 
	= 赋值  == 非严格比较 ===严格比较 类型相同 值相同
	逻辑操作符:
    &&   ||  ！
    
条件语句:
	if(condition){
	statements;  //当条件为真时执行;
	} else{} //当条件为假时执行;
    
循环语句:
	while循环:
		while(condition){
		statements;
		}  // 先判断在执行
        do {
		statements;
		} while(condition); //先执行在判断
	for循环:
		for(inital;condition;letadd;){
		statements;
		}
函数:
	function funname(args){
	statements;
	}
作用域:    var定义为内部 
          直接赋为全局 坑！！
对象:
	var newO=Object()
	有属性和方法 很low了 不要让我在记录了
</pre>
每一个变量就是一个对象,有属于自己的方法和属性. 



