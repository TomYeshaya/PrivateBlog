---
title: C++ 运算符
date: 2021-01-15 19:00:00
tags: [C++]
categories: [C++]
---
    
	+  -  *  / 		
	解释：运算符 —— 加、减、乘、除 
	
	+= -= *= /= %= 	
	解释：运算符 —— 修改和替代
	
<!-- more -->
	
	． 
	解释：运算符——结构或联合的成员选择  
	
	,  
	解释：逗号运算符 分隔符, 用于分隔函数参数表中的各参数
	
	~  
	解释：运算符 —— 二进码反（按位非）
	
	*  
	解释：分隔符 —— 用于在变量中指明当前的变量是指向某个类型的指针
	
	!  
	解释：运算符 —— 逻辑反(非)
	
	&  
	解释：运算符 —— 1.取变量地址 2.按位与 
	
	&& 
	解释：运算符 —— 逻辑与
	
	%  
	解释：运算符 —— 模除（取整除后的余数）
	
	;  
	解释：分隔符 —— 终止一条语句
	
	： 
	解释：分隔符 —— 指明标号语句
	
	:: 
	解释：作用域运算符, 当局部变量与全局变量同名时, 在局部变量的作用域内, 全局变量前面使用该运算符 
	
	++ 
	解释：运算符 —— 增一
	
	-- 
	解释：运算符 —— 减一
	
	=  
	解释：运算符 —— 赋值
	
	== 
	解释：运算符 —— 等于 
	
	!= 
	解释：运算符 —— 不等于 
	
	>= 
	解释：运算符 —— 大于等于
	
	>  
	解释：运算符 —— 大于
	
	<= 
	解释：运算符 —— 小于等于 
	
	<  
	解释：运算符 —— 小于   
	
	-> 
	解释：运算符 —— 指向结构(C++语言中的类)成员的指针引用  
	
	<< 
	解释：运算符 —— 字位左移 
	
	>> 
	解释：运算符 —— 字位右移   
	
	^  
	解释：运算符 —— 按位异或   
	
	|  
	解释：运算符 —— 按位或   
	
	|| 
	解释：运算符 —— 逻辑或   
	
	[] 
	解释：分隔符 —— 指明数组下标   
	
	() 
	解释：分隔符 —— 用于形成表达式、隔离条件表达式, 以及指明函数调用和函数参数   
	
	{} 
	解释：分隔符 —— 用于指明复合语句（分程序）的开始和及结束   
	
	(类型名) 
	解释：运算符 —— 类型强制转换   
	
	\\ 
	解释：转义（换码）序列 —— 反斜杠（使用时与字符一样要用“”）   
	
	\0 
	解释：转义（换码）序列 —— 空白NULL   
	
	\a 
	解释：转义（换码）序列 —— 响铃   
	
	\b 
	解释：转义（换码）序列 —— 退格   
	
	\n 
	解释：转义（换码）序列 —— 换行   
	
	\r 
	解释：转义（换码）序列 —— 回车   
	
	\t 
	解释：转义（换码）序列 —— 制表符   
	
<!--  -->
	
	％d		
	解释：整型输出 
	
	％ld		
	解释：长整型输出 
	
	％o		
	解释：以八进制数形式输出整数 
	
	％x		
	解释：以十六进制数形式输出整数 
	
	％u		
	解释：以十进制数输出unsigned型数据(无符号数)  
	
	％c		
	解释：用来输出一个字符 
	
	％s		
	解释：用来输出一个字符串 
	
	％f		
	解释：用来输出实数, 以小数形式输出 
	
	％e		
	解释：以指数形式输出实数 
	
	％g		
	解释：根据大小自动选f格式或e格式, 且不输出无意义的零, scanf(控制字符, 地址列表)
	
	格式字符的含义同printf函数, 地址列表是由若干个地址组成的表列, 可以是变量的地址, 或字符串的首地址 如scanf("％d％c％s",&a,&b,str)
	
<!--  -->
	
	abstract	
	解释：Java类修饰符(定义类时用), 表示该类是一个抽象类, 不能直接产生该类的一个对象  
	
	auto       
	解释：存储类区分符（一种说明区分符）   
	
	break  		
	解释：转移语句——终止执行switch语句, 或跳出循环语句   
	
	case 		
	解释：标号 用于开关语句中   
	
	char 		
	解释：数据类型区分符（说明区分符）, 定义单字节变量   
	
	class 		
	解释：C++语言的合成类型区分符（说明区分符）, 说明“类”类型   
	
	const 		
	解释：C++语言的类型区分符（说明区分符）   
	
	continue 	
	解释：转移语句——跳过位于continue后面的语句, 立即开始下一轮循环   
	
	default 	
	解释：（标号）用于开关语句中   
	
	delete 		
	解释：C++语言的释放内存语句   
	
	double 		
	解释：数据类型区分符（说明区分符）, 定义双精度浮点变量, 对于IBM PC机, 双精度数据类型是64位   
	
	enum 		
	解释：合成类型区分符（说明区分符）, 定义一个枚举类型（括号中定义变量数据的允许值）, 然后（或同时）定义枚举变量  
	
	extern 		
	解释：存储类区分符（一种说明区分符）   
	
	f、F			
	解释：浮点常量的浮点后缀（缺省是double）   
	
	far 		
	解释：C语言远指针说明   
	
	final 		
	解释：Java中的类修饰符, 表示定义的类不能被其他类继承  
	
	float 		
	解释：数据类型区分符（说明区分符）, 定义单精度浮点变量, 对于IBM PC机, 浮点数据类型是32位   
	
	for
	解释：循环语句(变量赋初值表达式、循环结束条件表达式、变量增量表达式)  
	
	friend 		
	解释：C++语言的说明区分符, 在类定义时, 加在函数前面, 把一个非成员函数声明为该类的一个友元, 该友元函数就获得了对该类私有部分的访问权 
	
	goto 		
	解释：无条件转移语句, goto后接标识符（命名的标号）  
	
	if(表达式) 	
	解释：条件判别语句 表达式为真则执行随后在{ }中的语句（无{ }则只执行if后面的一句）, 表达式为假, 则执行else后面的语句  
	
	inline 		
	解释：C++语言的函数区分符（一种说明区分符）, 它加在函数前面, 使之被定义成内置函数, 类的函数成员定义成内置函数的简单方法是把它的定义包含在类定义中   
	
	int 		
	解释：数据类型区分符（说明区分符）, 定义整型变量  
	
	interrupt 	
	解释：中断处理函数类型修饰符——建立（定义）中断处理函数 在处理函数入口, 保存所有寄存器的内容（返回前恢复这些寄存器的值）, 并把DS指向C程序的数据段, interrupt函数是通过IRET指令而不是RET指令返回的   l、解释：整形常量长后缀 或浮点常量后缀, 指明long double类型  
	
	long 		
	解释：数据类型区分符（说明区分符）, 对于IBM PC机, 长整型是32位   
	
	new 		
	解释：C++语言的分配内存语句   
	
	operator 	
	解释：C++语言的重载操作符   
	
	private 	
	解释：C++、Java语言类说明中的访问区分符(变量修饰符、方法修饰符) 表示只有本类的对象可以访问该变量或方法, 其他类即使是子类也不行   
	
	protected 	
	解释：C++、Java语言类说明中的访问区分符(变量修饰符、方法修饰符) 表示只有这个类的所有子类和同一Javz程序包中的其他类可以直接存取这个变量(调用方法)   
	
	public 		
	解释： (1)Java中的类修饰符, 表示定义的类是个公共类, 其他Java包内的类也可访问该类的成员变量和方法 
		  (2)C++、Java语言的类说明中的访问区分符(变量修饰符、方法修饰符) public后面的部分（公有部分）可以被使用者访问   
	
	register 	
	解释：存储类型区分符（一种说明区分符）   
	
	return 		
	解释：转移语句——使函数将控制权送回调用函数 return后接（void类型函数、构造函数和析构函数例外）表达式（返回值）   
	
	short 		
	解释：数据类型区分符（说明区分符） 对于IBM PC机, 短整型是16位  
	
	signed 		
	解释：数据类型区分符（说明区分符）   
	
	sizeof(类型名) 
	解释：运算符——取一个目标的字节长度   
	
	static 		
	解释：存储类区分符（一种说明区分符）, 用它说明的对象具有静态生存期  
	
	struct 		
	解释：合成类型区分符（说明区分符）, 定义一个结构类型, 然后（也可同时）定义结构变量（或数组）   
	
	switch(表达式) 
	解释：开关语句 首先对表达式求值, 然后执行与表达式值相同标号的case子句, 如果未找到匹配的case常量, 则执行default子句  
	
	typedef 	
	解释：说明区分符 typedef 语句用来对基本数据类型或导出数据类型赋予新名   
	
	u、U 		
	解释：整形变量无符号后缀  
	
	union 		
	解释：合成类型区分符（说明区分符） 定义一个共用体（联合）类型, 然后（也可同时）定义联合变量 
	
	unsigned 	
	解释：数据类型区分符（说明区分符）   
	
	virtual 	
	解释：C++语言的函数区分符（一种说明区分符） 
	
	void 		
	解释：类型区分符（说明区分符）   
	
	while(表达式) 
	解释：循环语句 若表达式为真, 执行随后{ }内的语句（或do后{ }内的语句） 