# 面向对象基础
tips:我发现通过记案例来学习知识点格外的快速和易于理解，案例学习法
时刻思考：为了解决什么问题，使用什么技术路线，用了哪些方法，最后达到了什么效果？
*临时记录：
1.编程范式跟程序实际性能无关，跟编译方式有关
2.区分对象的引用和对象实体之间的关系和不同
Person person //声明一个类
person = new Person（）//将person引用指向对象实体
3.多态要起到的作用：”一个接口，多种实现“
4.包含抽象方法的类就是抽象类........吗？
5.引用拷贝，浅拷贝，深拷贝：简而言之就是两个点，拷贝顺序从外向内拷贝，每拷贝一次新建一个同类型的对象或引用，后续未拷贝部分地址相同，拷贝部分地址不同
6.final修饰类表示不能被继承，修饰方法表示不能被重写*

[Java接口和抽象类的实现](https://www.runoob.com/w3cnote/java-abstract-interface-different.html)

# Object类
*临时记录：
1.String类的equals()方法是被重写过的，用来比较两个对象的String值是否相等
2.hashcode()是本地方法，通过C/C++来实现
3.hashcode()大大减小了查找的次数，提高了查找的效率
4.hashcode相同不代表值相同（哈希碰撞）*

# String类
*临时记录：
1.Java本身不支持运算符的重载，但是专门为String重载了+和+=两个运算符，也是Java中重载的仅有的两个运算符
2.区分Java字节码编译的时候+和stringbuilder的关系，以及如何优化
3.字符串常量池以及JVM优化：重点*

