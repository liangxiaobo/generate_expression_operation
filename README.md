# generate_expression_operation
用Js写的一个生成，运算游戏的运算表达式

有四个变量需要注意：

  // 定义一个表达式的类型，表示计算倍数
	var expression_type = [2, 3, 4];
	// 取expression_type数组的长度限制
	var expression_type_max_length = 2;
	
	// 生成表达式的最大值
	var expression_max_value = 5;
	// 生成表达式的最小值
	var expression_min_value = 1;
	
	expression_type 数组存放的数，2表示 “n+n”, 3表示 "n+n+n",可以根据需要自定义
	
	expression_type_max_length 2表示取expression_type数组的值，下标[0,1] 可用来控制难度
	
	expression_max_value 表示生成 n 的最大值 
	
	expression_min_value 表示生成 n 的最小值
	
	可以把Js文件引入到页面，在控制台console中看打印的结果
