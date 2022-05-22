### 一月二十一号的c笔记
1.按fn+f10就可以一步步运行，但是进入test函数我们要需要按fn+f11
2.f11查看
3.static修饰局部变量延长了生命周期||
4.static修饰全局变量改变了其作用域，使其只能在当前源文件使用（而不是整个程序）
5.只要用extern引用外部函数是可以使用的，大半年是static修饰自定义函数，就使得这个自定义函数只能在当前源文件使用，即改变了函数的外部链接属性---     外部-->内部
6.全局变量作用域是整个程序，extern是声明外面符号的
7.#define定义宏    别忘了大写喔
#define MAX(X,Y)(X>Y?X:Y)

int main()
{
	int a = 10;
	int b = 20;
	int max = MAX(a, b);
	printf("max=%d", max);
	return 0;
}
11.character文字 字母 字符
所以我们c语言中，一般字符变量名常用ch