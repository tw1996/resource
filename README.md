# 编程资源整理     

## php官方手册    
http://php.net/manual/zh/          


## 设计模式系列    
#### 六大原则      
* 开闭原则：软件模块应该对扩展开放，对修改关闭。   
* 里氏替换原则：当衍生类可以替换掉基类，软件单位的功能不受影响，基类才能真正被复用，而衍生类也可以添加新的功能。        
* 依赖倒转原则：面向接口编程，而不是面向实现。    
* 接口隔离原则：尽量使用多个隔离的接口，而不是单个接口。比如登录注册应该是两个不同接口。    
* 迪米特原则：实体尽量与其他实体发生相互作用，使得各模块相互独立。    
* 单一职责原则：一个类只负责一个功能领域。    

#### 常用设计模式    
* 单例模式：三私一共，全局只能有一个类的引用。    
* 简单工厂模式：专门创建一个类根据参数的不同返回不同类的实例。被创建的类通常有共同的父类。    
* 工厂方法模式：定义一个抽象的核心工厂类，并定义创建产品对象的接口，创建具体的产品实例延迟到其工厂子类中去完成，一个具体工厂创建一个产品，是一对一关系，允许系统在不修改工厂角色的情况下引进新的产品。    
* 抽象工厂模式：提供一个创建一系列或相关对象的接口，而无需指定它们的具体类，当需要产品族的一系列产品时，可以创建一个具体工厂生产多种产品，是一对多关系。   
* 生成器模式：将对象复杂的构建过程抽象出来，使得抽象过程不同的实现方法可以构造出不同表现的对象。    
* 观察者模式：也叫发布－订阅模式，　在对象间建立一对多的联系，当被观察对象状态发生改变时，观察者会接到通知。    
* 责任链模式：为了解除请求的发送者和接受者的耦合，将所有对象连成一条链，请求沿该链传递，直到有一个对象处理此请求。        
* 策略模式：定义一族相同类型的算法，算法之间独立封装并且可以相互替代。   
* 装饰器模式：可以动态地往类中添加新的行为，比集成更加灵活，因为可以给对象而不是特定类添加功能。    
* 适配器模式：用于消除接口不匹配造成的类兼容问题。   

#### 参考    
* 推荐这个 : http://www.awaimai.com/patterns    
* 实验楼 : https://www.shiyanlou.com/courses/699     
* 其他 : https://design-patterns.readthedocs.io/zh_CN/latest/read_uml.html    


## 索引     
Elasticsearch：https://es.xiaoleilu.com/    

## 站点资源     
* 极客学院：http://wiki.jikexueyuan.com/list/php/      
* 鸟哥：http://www.laruence.com/licence (无人不知吧)


## 抓包分析     
* Charles：http://blog.csdn.net/lmmilove/article/details/50244537     


## docker    
* http://www.web3.xin/code/911.html    


## Rabbit MQ    
* php版：https://rabbitmq.shujuwajue.com/    




