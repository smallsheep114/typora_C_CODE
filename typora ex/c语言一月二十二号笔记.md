## c语言一月二十二号笔记

### 1.结构体   struct Book {};//分号不能漏掉

2.   .的作用   b1.name    b1.price
3.   ->作用，可以代替解引用操作符，更为简便
如： struct Book* pb = &b1;
pb -> name     pb->price 等价于(*pb).name  (*pb).price
操作符.    结构体变量(b1).成员
操作符 ->     结构体指针 ->成员
4.   由分号隔开的叫语句
