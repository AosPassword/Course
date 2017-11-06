# 2017红岩网校后端第一次课件



#### 想对你们说的一些话→_→



#### 正课 (°∀°)ﾉ

- .class    .java

  jvm负责兼容

- Java变量:Variables.java

  - 局部变量：在方法、构造方法或者语句块中定义的变量被称为局部变量。变量声明和初始化都是在方法中，方法结束后，变量就会自动销毁。
  - 成员变量：成员变量是定义在类中，方法体之外的变量。这种变量在创建对象的时候实例化。成员变量可以被类中方法、构造方法和特定类的语句块访问。
  - 类变量：声明在类中，方法体之外，但必须声明为static类型。

- 方法:Function.java

  - 方法的命名规则：必须以字母、'_'或'＄'开头，可以包括数字，但不能以它开头。

  - 使程序变得更简短而清晰，有利于程序维护，可以提高程序开发的效率，提高了代码的重用性。

  - 方法的定义

    ```java
    修饰符 返回值类型 方法名(参数类型 参数名){
        ...
        方法体
        ...
        (return 返回值;)
    }
    ```

- 流程控制:Practice.java
  - if else
  - switch...case
  - for
  - while
  - do...while
  - try...catch

- 几个关键字
  - import:在源文件的开始部分指明后面将要引用的一个类或整个包，这样就不必在使用的时候加上包的名字。

    （在讲完面向对象后讲一下）

  - return:用来结束一个方法的执行

  - void

- 类

  类就是具备某些共同特征的实体的集合，它是一种抽象的数据类型，它是对所具有相同特征实体的抽象。在面向对象的程序设计语言中，类是对一类“事物”的属性与行为的抽象。

- 对象

  对象就是一个真实世界中的实体，对象与实体是一一对应关系的，意思就是现实世界的每一个实体都是一个对象，所以对象是一个具体的概念。

  - 类和对象的区别
  - 类是一个抽象的概念，它不存在于现实中的时间/空间里，类只是为所有的对象定义了抽象的属性与行为。就好像“Person（人）”这个类，它虽然可以包含很多个体，但它本身不存在于现实世界上。
  - 对象是类的一个具体。它是一个实实在在存在的东西。
  - 类是一个静态的概念，类本身不携带任何数据。当没有为类创建任何对象时，类本身不存在于内存空间中。
  - 对象是一个动态的概念。每一个对象都存在着有别于其它对象的属于自己的独特的属性和行为。对象的属性可以随着它自己的行为而发生改变。

- 举两个面向对象栗子

- import

  import net.sf.json.JSONObject;

  JSONObject resultJSON = JSONObject.fromObject(result);

  ​


# 微派谁是卧底游戏助手