## 类的继承

*继承*是从已有的类中派生出新的类，新的类具有被继承类的数据属性和行为，并能扩展新的能力。

### 语法

```java
[修饰符] class SubClass extends SuperClass{
 	// 类定义部分   
}
```

### 重写父类的方法

### 

### super限定

如果需要在子类方法中,调用父类被覆盖的方法,则可以使用super关键字

```java
super() // 调用父类构造器
super.overridedMethod();
```



## 多态

Java引用变量有两种类型,一种是编译时类型,一种是运行时类型.

多态就是指:引用变量的编译时类型跟运行时类型不一致.

```java
Father person = new Son();
// person 的编译时类型是Father 运行时类型是Son.
// 注意 编译时类型是运行时类型的父类
```

**注意:**

1. 实例方法具有多态性,实例变量不具有多态性
2. 如果调用的运行时类型的方法,是编译时类型所不具备的,则会报错.
3. 一般来说,多态其实就是用于接口/或抽象类上.

