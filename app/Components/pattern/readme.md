

## 设计模式——原则

1）对象对象

2）复制与复用

3）业务封装

4）紧耦合与松耦合、强内聚与弱内聚（对象的多态、继承、虚方法、方法重写）
    
5）尽量遵循UML类图规则

6）单一职责原则：
    
    就是一个类而言，应该仅有一个引起它变化的原因。
    如果一个类承担的职责过多，就等于把这些职责耦合在一起，
    一个职责的变化可能会削弱或者抑制这个类完成其他职责的能力。
    这种耦合会导致脆弱的设计。当变化发生时，设计会遭受到意想不到的破坏。
    软件设计真正要做的许多内容，就是发现职责并把这些职责相互分离。
    其实要去判断是否应该分离出类来，也不难，那就是如果你能够想到多于一个的动机去改变一个类，
    那么这个类就具有多余一个的职责，就应该考虑类的职责分离。

7）开放-封闭原则：
    
    是说软件实体（类、模块、函数等等），应该可以扩展，但是不可修改。
    开放-封闭原则是面向对象设计的核心所在。
    遵循这哦个原则可以带来面向对象技术所声称的巨大好处，也就是可维护、可扩展、可复用、灵活性好。
    开发人员应该仅对程序中呈现出频繁变化的那些部分作出抽象，
    然而，对于应用程序中的每个部分都刻意地进行抽象同样不是一个好主意。
    拒绝不成熟的抽象和抽象本身一样重要。
    
8）依赖倒转原则

    A、高层模块不应该依赖低层模块。两个模块都应该依赖抽象。
    B、抽象不应该依赖细节。细节应该依赖抽象。
    
9）迪米特法则

    如果两个类不必彼此直接通信，那么这两个类就不应当发生直接的相互作用。
    如果其中一个类需要调用了另一个类的某一个方法的话，可通过第三者转发这个调用。
    
    注意：迪米特法则首先强调的前提是在类的结构设计上，每一个类都应当尽量降低成员的访问权限。
    
    此法则其根本思想是强调了类之剑的松耦合。
    同样道理，我们在设计程序是，类之间的耦合越弱，越有利于复用，一个处在弱耦合的类被修改，
    不会对有关系的类造成波及。

   

