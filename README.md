# combing
梳理核心知识点

面向对象有三个主要的特点：封装、继承和多态。

（1）封装
现在我要研究下狗，并且关注它的叫和咬人行为，所以我封装了一个狗的类，如下代码所示：

![](http://fed.renren.com/wp-content/uploads/2017/05/2.png)

上面代码封装两个行为：叫、咬人，和一个属性：年龄。

（2）继承
然后我又要研究下哈士奇，如下代码所示：

![](http://fed.renren.com/wp-content/uploads/2017/05/3.png)

哈士奇是狗的一种，我让它继承了Dog这个类，于是它就继承了父类的行为，如它可以咬你：
![](http://fed.renren.com/wp-content/uploads/2017/05/4.png)

同时，哈士奇它有自己的行为，例如它可能时不时就会露出奇怪的表情。

（3）多态
哈士奇也会叫，但是它不是“汪汪汪”地叫，它有时候会发出像狼嚎的声音，所以同样是叫的行为，但是哈士奇有自己特点，这个就是多态，如下所示：

![](http://fed.renren.com/wp-content/uploads/2017/05/5-4.png)

当调用Husky的bark函数时就是wolf wolf而不是wang wang了：
![](http://fed.renren.com/wp-content/uploads/2017/05/6-2.png)

