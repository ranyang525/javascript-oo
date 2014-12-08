#JavaScript面向对象

##Class 类
是一种面向对象计算机编程语言的构造，是创建对象的蓝图，描述了所创建的对象共同的属性和方法。

```javascript
//定义类并创建类
function Dog() {
  this.name = '';
  this.age = ‘’;
}
```
##Object 对象
对象（Object）是某一个类（Class）的实例（Instance）

对象具有唯一的标识符，对象包括属性（Properties）和方法（Methods），属性就是需要记忆的信息，方法就是对象能够提供的服务
对象的特征（封装性，继承性，多态性）
```javascript
//实例化一个对象
var mydog = new Dog();
```
##Instance 实例
```javascript
var mydog = new Dog('毛毛','12')
```

##Inheritance 继承
一个类可以继承另一个类的特征。

##Encapsulation 封装
类定义了对象的特征，方法只定义了方法如何执行。

##Polymorphism 多态
多意为‘许多’，态意为‘形态’。不同类可以定义相同的方法或属性。
