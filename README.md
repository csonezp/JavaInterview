* [Java基础](#java基础)
   * [1.说下面向对象四大特性](#1说下面向对象四大特性)
   * [2.抽象类和接口（Java7）的区别](#2抽象类和接口java7的区别)
   * [3.Java 8的接口新增了哪些特性？](#3java-8的接口新增了哪些特性)
   * [4.重写和重载的区别](#4重写和重载的区别)
   * [5.ArrayList和LinkedList有什么区别？](#5arraylist和linkedlist有什么区别)
   * [6.HashMap是怎么实现的？](#6hashmap是怎么实现的)
   * [7.HashMap在Java7和Java8中的实现有什么不同？](#7hashmap在java7和java8中的实现有什么不同)
   * [8.HashMap有时候会死循环，你知道是什么原因吗？](#8hashmap有时候会死循环你知道是什么原因吗)
   * [9.ConcurrentHashMap是怎么实现的？](#9concurrenthashmap是怎么实现的)
   * [10.静态代理和动态代理的区别](#10静态代理和动态代理的区别)
   * [11.JDK动态代理和CGLIB动态代理的区别](#11jdk动态代理和cglib动态代理的区别)
* [Java多线程](#java多线程)
   * [1.说说synchronized的实现原理](#1说说synchronized的实现原理)
   * [2.ReentrantLock与synchronized的区别](#2reentrantlock与synchronized的区别)
   * [3.ReentrantLock实现原理](#3reentrantlock实现原理)
   * [4.Java原子类AtomicInteger实现原理](#4java原子类atomicinteger实现原理)
   * [5.Java线程池实现原理](#5java线程池实现原理)
   * [6.ThreadLocal实现原理](#6threadlocal实现原理)
   * [7.InheritableThreadLocal原理知道吗？](#7inheritablethreadlocal原理知道吗)
   * [8.说一下synchronized锁升级过程](#8说一下synchronized锁升级过程)
   * [9.了解过什么是“伪共享”吗？](#9了解过什么是伪共享吗)
   * [10.“伪共享”出现的原因是什么？](#10伪共享出现的原因是什么)
   * [11.如何避免“伪共享”？](#11如何避免伪共享)
   * [12.Java里的线程有哪些状态？](#12java里的线程有哪些状态)
   * [13.什么是悲观锁？什么是乐观锁？](#13什么是悲观锁什么是乐观锁)
   * [14.怎么停止一个运行中的线程？](#14怎么停止一个运行中的线程)
   * [15.说一下你对volatile的理解？](#15说一下你对volatile的理解)
* [Java虚拟机](#java虚拟机)
   * [说一下JVM的内存结构？](#说一下jvm的内存结构)
   * [栈帧里面包含哪些东西？](#栈帧里面包含哪些东西)
   * [程序计数器有什么作用？](#程序计数器有什么作用)
   * [字符串常量存放在哪个区域？](#字符串常量存放在哪个区域)
   * [你熟悉哪些垃圾收集算法？](#你熟悉哪些垃圾收集算法)
   * [Java里有哪些引用类型？](#java里有哪些引用类型)
   * [JVM怎么判断一个对象是不是要回收？](#jvm怎么判断一个对象是不是要回收)
   * [GC Roots 有哪些？](#gc-roots-有哪些)
   * [你知道哪些GC类型？](#你知道哪些gc类型)
   * [对象都是优先分配在年轻代上的吗？](#对象都是优先分配在年轻代上的吗)
   * [你了解过哪些垃圾收集器？](#你了解过哪些垃圾收集器)
   * [说说CMS垃圾收集器的工作原理](#说说cms垃圾收集器的工作原理)
   * [说说G1垃圾收集器的工作原理](#说说g1垃圾收集器的工作原理)
   * [说说ZGC垃圾收集器的工作原理](#说说zgc垃圾收集器的工作原理)
   * [ZGC收集器中的染色指针有什么用？](#zgc收集器中的染色指针有什么用)
   * [说说类加载的过程](#说说类加载的过程)
   * [说下有哪些类加载器？](#说下有哪些类加载器)
   * [什么是双亲委派机制？](#什么是双亲委派机制)
   * [双亲委派机制可以被违背吗？请举例说明。](#双亲委派机制可以被违背吗请举例说明)
   * [Tomcat是怎么打破双亲委派机制的呢？](#tomcat是怎么打破双亲委派机制的呢)
   * [Java对象的布局了解过吗？](#java对象的布局了解过吗)
* [MySQL](#mysql)
   * [了解过哪些存储引擎？各有什么优缺点？](#了解过哪些存储引擎各有什么优缺点)
   * [说一下什么是事务的ACID属性吧](#说一下什么是事务的acid属性吧)
   * [事务的隔离级别了解过吗？](#事务的隔离级别了解过吗)
   * [说说InnoDB的索引原理](#说说innodb的索引原理)
   * [说说InnoDB的MVCC机制](#说说innodb的mvcc机制)
   * [有了解过“回表”的概念吗？什么情况下会出现“回表”？](#有了解过回表的概念吗什么情况下会出现回表)
   * [MySQL索引的类型](#mysql索引的类型)
   * [有做过MySQL的索引优化吗](#有做过mysql的索引优化吗)
   * [什么是聚簇索引？](#什么是聚簇索引)
   * [InnoDB有聚簇索引吗？MyIsam呢？](#innodb有聚簇索引吗myisam呢)
   * [MyIsam的数据是怎么存储的？](#myisam的数据是怎么存储的)
   * [InnoDB的数据是怎么存储的？](#innodb的数据是怎么存储的)
   * [InnoDB主键索引跟非主键索引在数据存储上的差异](#innodb主键索引跟非主键索引在数据存储上的差异)
   * [InnoDB删除某条记录后，内部会怎么处理？](#innodb删除某条记录后内部会怎么处理)
   * [InnoDB如果没有设置主键的话，它内部会怎么处理？](#innodb如果没有设置主键的话它内部会怎么处理)
   * [为什么InnoDB一定会生成主键？](#为什么innodb一定会生成主键)
   * [MySQL分库分表了解过吗？](#mysql分库分表了解过吗)
   * [MySQL的redo日志和undo日志分别有什么用？](#mysql的redo日志和undo日志分别有什么用)
   * [MySQL的redo日志的刷盘时机](#mysql的redo日志的刷盘时机)
   * [MySQL有哪些锁？以及各种锁的作用？](#mysql有哪些锁以及各种锁的作用)
* [Redis](#redis)
   * [Redis有哪些数据结构？](#redis有哪些数据结构)
   * [Redis为什么那么快？](#redis为什么那么快)
   * [Redis如何实现分布式锁？](#redis如何实现分布式锁)
   * [Redis是单线程还是多线程？](#redis是单线程还是多线程)
   * [缓存失效？缓存穿透？缓存雪崩？缓存并发？](#缓存失效缓存穿透缓存雪崩缓存并发)
   * [Redis中的热key怎么处理？](#redis中的热key怎么处理)
   * [Redis中的大key怎么处理？](#redis中的大key怎么处理)
   * [使用Redis统计网站的UV，应该怎么做？](#使用redis统计网站的uv应该怎么做)
   * [Redis事务机制了解过吗？](#redis事务机制了解过吗)
   * [Redis key的淘汰策略有哪些？](#redis-key的淘汰策略有哪些)
   * [Redis在什么情况下会触发key的回收？](#redis在什么情况下会触发key的回收)
   * [Redis的持久化了解过吗？](#redis的持久化了解过吗)
   * [Redis在集群种查找key的时候，是怎么定位到具体节点的？](#redis在集群种查找key的时候是怎么定位到具体节点的)
   * [Redis集群各个节点之间是怎么保持数据一致性的？](#redis集群各个节点之间是怎么保持数据一致性的)
   * [用Redis做延时队列，具体应该怎么实现？](#用redis做延时队列具体应该怎么实现)
   * [Redis String的内部编码有哪些？](#redis-string的内部编码有哪些)
* [Spring](#spring)
   * [Spring是怎么解决循环依赖的？](#spring是怎么解决循环依赖的)
   * [Spring Boot手动装配有哪几种方式？](#spring-boot手动装配有哪几种方式)
   * [Spring Boot自动配置原理](#spring-boot自动配置原理)
* [Netty](#netty)
   * [你了解过哪些IO模型？](#你了解过哪些io模型)
   * [什么是Reactor模型？Reactor的3种版本都知道吗？](#什么是reactor模型reactor的3种版本都知道吗)
   * [了解过粘包拆包吗？为什么会出现粘包拆包？怎么处理粘包拆包？](#了解过粘包拆包吗为什么会出现粘包拆包怎么处理粘包拆包)
   * [UDP协议会有粘包拆包的问题吗？为什么？](#udp协议会有粘包拆包的问题吗为什么)
* [微服务](#微服务)
            * [微服务有哪些优缺点？](#微服务有哪些优缺点)
            * [作为注册中心，Zookeeper和Eureka有什么区别？](#作为注册中心zookeeper和eureka有什么区别)
            * [Service Mesh了解过吗？](#service-mesh了解过吗)
      * [Zookeeper](#zookeeper)
            * [Zookeeper有哪些节点类型？](#zookeeper有哪些节点类型)
            * [了解过Zookeeper的ZAB协议吗？](#了解过zookeeper的zab协议吗)
            * [Zookeeper怎么实现分布式锁？](#zookeeper怎么实现分布式锁)
            * [Zookeeper是怎么保证数据一致性的？](#zookeeper是怎么保证数据一致性的)
            * [Zookeeper Leader选举过程是怎样的？](#zookeeper-leader选举过程是怎样的)
            * [Zookeeper怎么实现服务注册？](#zookeeper怎么实现服务注册)
      * [消息队列](#消息队列)
            * [消息队列有哪些应用场景？](#消息队列有哪些应用场景)
            * [消息队列的弊端有哪些？](#消息队列的弊端有哪些)
            * [使用消息队列，怎么确保消息不丢失？](#使用消息队列怎么确保消息不丢失)
            * [使用消息队列，如果处理重复消息？](#使用消息队列如果处理重复消息)
            * [Kafka的消息是有序的吗？如果保证Kafka消息的顺序性？](#kafka的消息是有序的吗如果保证kafka消息的顺序性)
      * [计算机网络](#计算机网络)
            * [说下TCP三次握手的过程](#说下tcp三次握手的过程)
            * [TCP为什么需要3次握手](#tcp为什么需要3次握手)
            * [TCP为什么需要4次挥手](#tcp为什么需要4次挥手)
            * [TCP time_wait状态是主动断开方才有，还是被动断开方才有？还是两边都有？](#tcp-time_wait状态是主动断开方才有还是被动断开方才有还是两边都有)
            * [TCP的keepalive机制了解过吗？](#tcp的keepalive机制了解过吗)
            * [HTTP的keepalive和TCP的keepalive，有什么区别？](#http的keepalive和tcp的keepalive有什么区别)
            * [TCP与UDP的区别？](#tcp与udp的区别)
            * [简述 HTTP1.0/1.1/2.0 的区别](#简述-http101120-的区别)
            * [HTTPS的原理了解过吗？](#https的原理了解过吗)
            * [TCP里Nagle算法了解过吗？可以禁用吗？在Java里怎么禁用？](#tcp里nagle算法了解过吗可以禁用吗在java里怎么禁用)
            * [HTTP协议为什么无法实现服务端推送？](#http协议为什么无法实现服务端推送)
            * [websocket协议升级过程了解过吗？](#websocket协议升级过程了解过吗)
      * [数据结构与算法](#数据结构与算法)
            * [说下你熟悉的排序算法](#说下你熟悉的排序算法)
            * [布隆过滤器了解过吗？](#布隆过滤器了解过吗)
            * [一致性hash算法了解过吗？](#一致性hash算法了解过吗)
      * [设计模式](#设计模式)
            * [Java怎么实现单例模式？](#java怎么实现单例模式)
            * [什么是代理模式？什么是动态代理？Java中动态代理有哪些实现方式？](#什么是代理模式什么是动态代理java中动态代理有哪些实现方式)
            * [什么是模板方法模式？试举例说明。](#什么是模板方法模式试举例说明)
      * [分布式](#分布式)
            * [分布式id如何生成？](#分布式id如何生成)
            * [雪花算法了解过吗？](#雪花算法了解过吗)
            * [什么是CAP定理？](#什么是cap定理)
            * [分布式事务了解过吗？](#分布式事务了解过吗)
            * [什么是二阶段提交（2PC）？什么是三阶段提交（3PC）？](#什么是二阶段提交2pc什么是三阶段提交3pc)
            * [TCC了解过吗？](#tcc了解过吗)
            * [Paxos算法了解过吗？](#paxos算法了解过吗)
            * [Zookeeper的Zab协议了解过吗？](#zookeeper的zab协议了解过吗)
            * [知道什么是Gossip协议吗？](#知道什么是gossip协议吗)




## Java基础

#### 1.说下面向对象四大特性

封装、继承、多态、抽象。

#### 2.抽象类和接口（Java7）的区别

1. 抽象类可以提供成员方法的实现细节，而接口中只能存在public abstract 方法；
2. 抽象类中的成员变量可以是各种类型的，而接口中的成员变量只能是public static final类型的；
3. 接口中不能含有静态代码块以及静态方法，而抽象类可以有静态代码块和静态方法；
4. 一个类只能继承一个抽象类，而一个类却可以实现多个接口。

#### 3.Java 8的接口新增了哪些特性？

增加了default方法和static方法，这2种方法可以有方法体。

#### 4.重写和重载的区别

重写是子类对父类的允许访问的方法的实现过程进行重新编写, 返回值和形参都不能改变。即外壳不变，核心重写！
重写的好处在于子类可以根据需要，定义特定于自己的行为。 也就是说子类能够根据需要实现父类的方法。
重写方法不能抛出新的检查异常或者比被重写方法申明更加宽泛的异常。

重载(overloading) 是在一个类里面，方法名字相同，而参数不同。返回类型可以相同也可以不同。
每个重载的方法（或者构造函数）都必须有一个独一无二的参数类型列表。


#### 5.ArrayList和LinkedList有什么区别？

1. ArrayList和LinkedList的差别主要来自于Array和LinkedList数据结构的不同。ArrayList是基于数组实现的，LinkedList是基于双链表实现的。另外LinkedList类不仅是List接口的实现类，可以根据索引来随机访问集合中的元素，除此之外，LinkedList还实现了Deque接口，Deque接口是Queue接口的子接口，它代表一个双向队列，因此LinkedList可以作为双向队列 ，栈（可以参见Deque提供的接口方法）和List集合使用，功能强大。

2. 因为Array是基于索引(index)的数据结构，它使用索引在数组中搜索和读取数据是很快的，可以直接返回数组中index位置的元素，因此在随机访问集合元素上有较好的性能。Array获取数据的时间复杂度是O(1),但是要插入、删除数据却是开销很大的，因为这需要移动数组中插入位置之后的的所有元素。

3. 相对于ArrayList，LinkedList的随机访问集合元素时性能较差，因为需要在双向列表中找到要index的位置，再返回；但在插入，删除操作是更快的。因为LinkedList不像ArrayList一样，不需要改变数组的大小，也不需要在数组装满的时候要将所有的数据重新装入一个新的数组，这是ArrayList最坏的一种情况，时间复杂度是O(n)，而LinkedList中插入或删除的时间复杂度仅为O(1)。ArrayList在插入数据时还需要更新索引（除了插入数组的尾部）。

4. LinkedList需要更多的内存，因为ArrayList的每个索引的位置是实际的数据，而LinkedList中的每个节点中存储的是实际的数据和前后节点的位置。

#### 6.HashMap是怎么实现的？

详见：https://blog.csdn.net/woshimaxiao1/article/details/83661464

#### 7.HashMap在Java7和Java8中的实现有什么不同？

详见：https://blog.csdn.net/qq_36520235/article/details/82417949

#### 8.HashMap有时候会死循环，你知道是什么原因吗？

详见：https://www.cnblogs.com/williamjie/p/11089522.html

#### 9.ConcurrentHashMap是怎么实现的？

详见：https://www.infoq.cn/article/ConcurrentHashMap/

#### 10.静态代理和动态代理的区别

静态代理中代理类在编译期就已经确定，而动态代理则是JVM运行时动态生成，静态代理的效率相对动态代理来说相对高一些，但是静态代理代码冗余大，一单需要修改接口，代理类和委托类都需要修改。

#### 11.JDK动态代理和CGLIB动态代理的区别

JDK动态代理只能对实现了接口的类生成代理，而不能针对类。
CGLIB是针对类实现代理，主要是对指定的类生成一个子类，覆盖其中的方法。因为是继承，所以该类或方法最好不要声明成final。


## Java多线程

#### 1.说说synchronized的实现原理

在 Java 中，每个对象都隐式包含一个 monitor（监视器）对象，加锁的过程其实就是竞争 monitor 的过程，当线程进入字节码 monitorenter 指令之后，线程将持有 monitor 对象，执行 monitorexit 时释放 monitor 对象，当其他线程没有拿到 monitor 对象时，则需要阻塞等待获取该对象。 

#### 2.ReentrantLock与synchronized的区别

ReentrantLock 有如下特点：
1. 可重入
ReentrantLock 和 syncronized 关键字一样，都是可重入锁，不过两者实现原理稍有差别， RetrantLock 利用 AQS 的的 state 状态来判断资源是否已锁，同一线程重入加锁， state 的状态 +1 ; 同一线程重入解锁, state 状态 -1 (解锁必须为当前独占线程，否则异常); 当 state 为 0 时解锁成功。
2. 需要手动加锁、解锁
synchronized 关键字是自动进行加锁、解锁的，而 ReentrantLock 需要 lock() 和 unlock() 方法配合 try/finally 语句块来完成，来手动加锁、解锁。
3. 支持设置锁的超时时间
synchronized 关键字无法设置锁的超时时间，如果一个获得锁的线程内部发生死锁，那么其他线程就会一直进入阻塞状态，而 ReentrantLock 提供 tryLock 方法，允许设置线程获取锁的超时时间，如果超时，则跳过，不进行任何操作，避免死锁的发生。
4. 支持公平/非公平锁
synchronized 关键字是一种非公平锁，先抢到锁的线程先执行。而 ReentrantLock 的构造方法中允许设置 true/false 来实现公平、非公平锁，如果设置为 true ，则线程获取锁要遵循"先来后到"的规则，每次都会构造一个线程 Node ，然后到双向链表的"尾巴"后面排队，等待前面的 Node 释放锁资源。
5. 可中断锁
ReentrantLock 中的 lockInterruptibly() 方法使得线程可以在被阻塞时响应中断，比如一个线程 t1 通过 lockInterruptibly() 方法获取到一个可重入锁，并执行一个长时间的任务，另一个线程通过 interrupt() 方法就可以立刻打断 t1 线程的执行，来获取t1持有的那个可重入锁。而通过 ReentrantLock 的 lock() 方法或者 Synchronized 持有锁的线程是不会响应其他线程的 interrupt() 方法的，直到该方法主动释放锁之后才会响应 interrupt() 方法。

#### 3.ReentrantLock实现原理

详见：https://blog.csdn.net/yanbin0830/article/details/107542529

#### 4.Java原子类AtomicInteger实现原理

详见：https://www.cnblogs.com/scuwangjun/p/9098057.html

#### 5.Java线程池实现原理

详见：https://www.cnblogs.com/dolphin0520/p/3932921.html

#### 6.ThreadLocal实现原理

详见：https://www.cnblogs.com/fsmly/p/11020641.html

#### 7.InheritableThreadLocal原理知道吗？

详见：https://www.jianshu.com/p/94ba4a918ff5

#### 8.说一下synchronized锁升级过程

1. 偏向锁
在 JDK1.8 中，其实默认是轻量级锁，但如果设定了 -XX:BiasedLockingStartupDelay = 0 ，那在对一个 Object 做 syncronized 的时候，会立即上一把偏向锁。当处于偏向锁状态时， markwork 会记录当前线程 ID 。

2. 升级到轻量级锁
当下一个线程参与到偏向锁竞争时，会先判断 markword 中保存的线程 ID 是否与这个线程 ID 相等，如果不相等，会立即撤销偏向锁，升级为轻量级锁。每个线程在自己的线程栈中生成一个 LockRecord ( LR )，然后每个线程通过 CAS (自旋)的操作将锁对象头中的 markwork 设置为指向自己的 LR 的指针，哪个线程设置成功，就意味着获得锁。关于 synchronized 中此时执行的 CAS 操作是通过 native 的调用 HotSpot 中 bytecodeInterpreter.cpp 文件 C++ 代码实现的，有兴趣的可以继续深挖。

3. 升级到重量级锁
如果锁竞争加剧(如线程自旋次数或者自旋的线程数超过某阈值， JDK1.6 之后，由 JVM 自己控制该规则)，就会升级为重量级锁。此时就会向操作系统申请资源，线程挂起，进入到操作系统内核态的等待队列中，等待操作系统调度，然后映射回用户态。在重量级锁中，由于需要做内核态到用户态的转换，而这个过程中需要消耗较多时间，也就是"重"的原因之一。

#### 9.了解过什么是“伪共享”吗？

CPU缓存从内存读数据时，是按缓存行读取的，即使只用到一个变量，也要将整行数据进行读取，这行数据量可能包含其他变量。当多个线程同时修改同一个缓存行里的不同变量时，由于同时只能有一个线程在操作，所以相比将每个变量放到不同缓存行里，性能会有所下降。多个线程同时修改了同一个缓存行上的不同变量，由于不能并发修改，所以称为“伪共享”。

#### 10.“伪共享”出现的原因是什么？

因为CPU缓存和内存交换数据的单位是缓存行，而同一个缓存行里的多个变量不能同时被多个线程修改。

#### 11.如何避免“伪共享”？

1. 字节填充（创建变量时，使用字段对其进行填充，避免多个变量被分派到同一个缓存行里）。
2. JDK8提供了一个Contended注解来解决伪共享。

#### 12.Java里的线程有哪些状态？

1. 初始(NEW)：新创建了一个线程对象，但还没有调用start()方法。
2. 运行(RUNNABLE)：Java线程中将就绪（ready）和运行中（running）两种状态笼统的称为“运行”。线程对象创建后，其他线程(比如main线程）调用了该对象的start()方法。该状态的线程位于可运行线程池中，等待被线程调度选中，获取CPU的使用权，此时处于就绪状态（ready）。就绪状态的线程在获得CPU时间片后变为运行中状态（running）。
3. 阻塞(BLOCKED)：表示线程阻塞于锁。
4. 等待(WAITING)：进入该状态的线程需要等待其他线程做出一些特定动作（通知或中断）。
5. 超时等待(TIMED_WAITING)：该状态不同于WAITING，它可以在指定的时间后自行返回。
6. 终止(TERMINATED)：表示该线程已经执行完毕。

#### 13.什么是悲观锁？什么是乐观锁？

当我们要对一个数据库中的一条数据进行修改的时候，为了避免同时被其他人修改，最好的办法就是直接对该数据进行加锁以防止并发。
这种借助数据库锁机制在修改数据之前先锁定，再修改的方式被称之为悲观并发控制（又名“悲观锁”，Pessimistic Concurrency Control，缩写“PCC”）。
之所以叫做悲观锁，是因为这是一种对数据的修改抱有悲观态度的并发控制方式。我们一般认为数据被并发修改的概率比较大，所以需要在修改之前先加锁。

乐观锁（ Optimistic Locking ） 是相对悲观锁而言的，乐观锁假设数据一般情况下不会造成冲突，所以在数据进行提交更新的时候，才会正式对数据的冲突与否进行检测，如果发现冲突了，则让返回用户错误的信息，让用户决定如何去做。
相对于悲观锁，在对数据库进行处理的时候，乐观锁并不会使用数据库提供的锁机制。一般的实现乐观锁的方式就是记录数据版本。

#### 14.怎么停止一个运行中的线程？

详见：https://www.cnblogs.com/liyutian/p/10196044.html

#### 15.说一下你对volatile的理解？

详见：https://blog.csdn.net/yinbucheng/article/details/71305951/

## Java虚拟机

#### 说一下JVM的内存结构？

详见：https://blog.csdn.net/rongtaoup/article/details/89142396

#### 栈帧里面包含哪些东西？

局部变量表、操作数栈、动态连接、返回地址等

#### 程序计数器有什么作用？

程序计数器是一块较小的内存空间，它的作用可以看作是当前线程所执行的字节码的行号指示器。这里面存的，就是当前线程执行的进度。
程序计数器还存储了当前正在运行的流程，包括正在执行的指令、跳转、分支、循环、异常处理等。

#### 字符串常量存放在哪个区域？

1. 字符串常量池，已经移动到堆上（jdk8之前是perm区），也就是执行intern方法后存的地方。
2. 类文件常量池，constant_pool，是每个类每个接口所拥有的，这部分数据在方法区，也就是元数据区。而运行时常量池是在类加载后的一个内存区域，它们都在元空间。

#### 你熟悉哪些垃圾收集算法？

标记清除（缺点是碎片化）
复制算法（缺点是浪费空间）
标记整理算法（效率比前两者差）
分代收集算法（老年代一般使用“标记-清除”、“标记-整理”算法，年轻代一般用复制算法）

#### Java里有哪些引用类型？

强引用
这种引用属于最普通最强硬的一种存在，只有在和 GC Roots 断绝关系时，才会被消灭掉。

软引用
软引用用于维护一些可有可无的对象。在内存足够的时候，软引用对象不会被回收，只有在内存不足时，系统则会回收软引用对象，如果回收了软引用对象之后仍然没有足够的内存，才会抛出内存溢出异常。
可以看到，这种特性非常适合用在缓存技术上。比如网页缓存、图片缓存等。
软引用可以和一个引用队列（ReferenceQueue）联合使用，如果软引用所引用的对象被垃圾回收，Java 虚拟机就会把这个软引用加入到与之关联的引用队列中。

弱引用
弱引用对象相比较软引用，要更加无用一些，它拥有更短的生命周期。当JVM进行垃圾回收时，无论内存是否充足，都会回收被弱引用关联的对象。弱引用拥有更短的生命周期，在 Java 中，用 java.lang.ref.WeakReference 类来表示。它的应用场景和软引用类似，可以在一些对内存更加敏感的系统里采用。

虚引用
这是一种形同虚设的引用，在现实场景中用的不是很多。虚引用必须和引用队列（ReferenceQueue）联合使用。如果一个对象仅持有虚引用，那么它就和没有任何引用一样，在任何时候都可能被垃圾回收。实际上，虚引用的 get，总是返回 null。

#### JVM怎么判断一个对象是不是要回收？

引用计数法（缺点是对于相互引用的对象，无法进行清除）
可达性分析

#### GC Roots 有哪些？

GC Roots 是一组必须活跃的引用。用通俗的话来说，就是程序接下来通过直接引用或者间接引用，能够访问到的潜在被使用的对象。

GC Roots 包括：
Java 线程中，当前所有正在被调用的方法的引用类型参数、局部变量、临时值等。也就是与我们栈帧相关的各种引用。
所有当前被加载的 Java 类。
Java 类的引用类型静态变量。
运行时常量池里的引用类型常量（String 或 Class 类型）。
JVM 内部数据结构的一些引用，比如 sun.jvm.hotspot.memory.Universe 类。
用于同步的监控对象，比如调用了对象的 wait() 方法。
JNI handles，包括 global handles 和 local handles。

这些 GC Roots 大体可以分为三大类，下面这种说法更加好记一些：
活动线程相关的各种引用。
类的静态变量的引用。
JNI 引用。

有两个注意点：
我们这里说的是活跃的引用，而不是对象，对象是不能作为 GC Roots 的。
GC 过程是找出所有活对象，并把其余空间认定为“无用”；而不是找出所有死掉的对象，并回收它们占用的空间。所以，哪怕 JVM 的堆非常的大，基于 tracing 的 GC 方式，回收速度也会非常快。

#### 你知道哪些GC类型？

Minor GC：发生在年轻代的 GC。
Major GC：发生在老年代的 GC。
Full GC：全堆垃圾回收。比如 Metaspace 区引起年轻代和老年代的回收。

#### 对象都是优先分配在年轻代上的吗？

不是。当新生代内存不够时，老年代分配担保。而大对象则是直接在老年代分配。

#### 你了解过哪些垃圾收集器？

年轻代
Serial 垃圾收集器（单线程，通常用在客户端应用上。因为客户端应用不会频繁创建很多对象，用户也不会感觉出明显的卡顿。相反，它使用的资源更少，也更轻量级。）
ParNew 垃圾收集器（多线程，追求降低用户停顿时间，适合交互式应用。）
Parallel Scavenge 垃圾收集器（追求 CPU 吞吐量，能够在较短时间内完成指定任务，适合没有交互的后台计算。）

老年代
Serial Old 垃圾收集器
Parallel Old垃圾收集器
CMS 垃圾收集器（以获取最短 GC 停顿时间为目标的收集器，它在垃圾收集时使得用户线程和 GC 线程能够并发执行，因此在垃圾收集过程中用户也不会感到明显的卡顿。）

#### 说说CMS垃圾收集器的工作原理

Concurrent mark sweep(CMS)收集器是一种年老代垃圾收集器，其最主要目标是获取最短垃圾回收停顿时间， 和其他年老代使用标记-整理算法不同，它使用多线程的标记-清除算法。
最短的垃圾收集停顿时间可以为交互比较高的程序提高用户体验。
CMS 工作机制相比其他的垃圾收集器来说更复杂，整个过程分为以下 4 个阶段：
1）初始标记
只是标记一下 GC Roots 能直接关联的对象，速度很快，仍然需要暂停所有的工作线程。
2）并发标记
进行 GC Roots 跟踪的过程，和用户线程一起工作，不需要暂停工作线程。
3）重新标记
为了修正在并发标记期间，因用户程序继续运行而导致标记产生变动的那一部分对象的标记记录，仍然需要暂停所有的工作线程。
4）并发清除
清除 GC Roots 不可达对象，和用户线程一起工作，不需要暂停工作线程。由于耗时最长的并发标记和并发清除过程中，垃圾收集线程可以和用户线程一起并发工作， 所以总体上来看CMS 收集器的内存回收和用户线程是一起并发地执行。

#### 说说G1垃圾收集器的工作原理

优点：指定最大停顿时间、分Region的内存布局、按收益动态确定回收集

G1开创的基于Region的堆内存布局是它能够实现这个目标的关键。虽然G1也仍是遵循分代收集理论设计的，但其堆内存的布局与其他收集器有非常明显的差异：G1不再坚持固定大小以及固定数量的分代区域划分，而是把连续的Java堆划分为多个大小相等的独立区域（Region），每一个Region都可以根据需要，扮演新生代的Eden空间、Survivor空间，或者老年代空间。收集器能够对扮演不同角色的Region采用不同的策略去处理，这样无论是新创建的对象还是已经存活了一段时间、熬过多次收集的旧对象都能获取很好的收集效果。 

虽然G1仍然保留新生代和老年代的概念，但新生代和老年代不再是固定的了，它们都是一系列区域（不需要连续）的动态集合。G1收集器之所以能建立可预测的停顿时间模型，是因为它将Region作为单次回收的最小单元，即每次收集到的内存空间都是Region大小的整数倍，这样可以有计划地避免在整个Java堆中进行全区域的垃圾收集。更具体的处理思路是让G1收集器去跟踪各个Region里面的垃圾堆积的“价值”大小，价值即回收所获得的空间大小以及回收所需时间的经验值，然后在后台维护一个优先级列表，每次根据用户设定允许的收集停顿时间（使用参数-XX：MaxGCPauseMillis指定，默认值是200毫秒），优先处理回收价值收益最大的那些Region，这也就是“Garbage First”名字的由来。这种使用Region划分内存空间，以及具有优先级的区域回收方式，保证了G1收集器在有限的时间内获取尽可能高的收集效率。 

G1收集器的运作过程大致可划分为以下四个步骤：
·初始标记 （Initial Marking）：仅仅只是标记一下GC Roots能直接关联到的对象，并且修改TAMS指针的值，让下一阶段用户线程并发运行时，能正确地在可用的Region中分配新对象。这个阶段需要停顿线程，但耗时很短，而且是借用进行Minor GC的时候同步完成的，所以G1收集器在这个阶段实际并没有额外的停顿。
·并发标记 （Concurrent Marking）：从GC Root开始对堆中对象进行可达性分析，递归扫描整个堆里的对象图，找出要回收的对象，这阶段耗时较长，但可与用户程序并发执行。当对象图扫描完成以后，还要重新处理SATB记录下的在并发时有引用变动的对象。
·最终标记 （Final Marking）：对用户线程做另一个短暂的暂停，用于处理并发阶段结束后仍遗留下来的最后那少量的SATB记录。
·筛选回收 （Live Data Counting and Evacuation）：负责更新Region的统计数据，对各个Region的回收价值和成本进行排序，根据用户所期望的停顿时间来制定回收计划，可以自由选择任意多个Region构成回收集，然后把决定回收的那一部分Region的存活对象复制到空的Region中，再清理掉整个旧Region的全部空间。这里的操作涉及存活对象的移动，是必须暂停用户线程，由多条收集器线程并行完成的。
从上述阶段的描述可以看出，G1收集器除了并发标记外，其余阶段也是要完全暂停用户线程的 。

#### 说说ZGC垃圾收集器的工作原理

1）内存布局
·小型Region（Small Region）：容量固定为2MB，用于放置小于256KB的小对象。
·中型Region（Medium Region）：容量固定为32MB，用于放置大于等于256KB但小于4MB的对象。
·大型Region（Large Region）：容量不固定，可以动态变化，但必须为2MB的整数倍，用于放置4MB或以上的大对象。每个大型Region中只会存放一个大对象，这也预示着虽然名字叫作“大型Region”，但它的实际容量完全有可能小于中型Region，最小容量可低至4MB。大型Region在ZGC的实现中是不会被重分配（重分配是ZGC的一种处理动作，用于复制对象的收集器阶段，稍后会介绍到）的，因为复制一个大对象的代价非常高昂。

2）染色指针
染色指针是一种直接将少量额外的信息存储在指针上的技术，可是为什么指针本身也可以存储额外信息呢？在64位系统中，理论可以访问的内存高达16EB（2的64次幂）字节 [3] 。实际上，基于需求（用不到那么多内存）、性能（地址越宽在做地址转换时需要的页表级数越多）和成本（消耗更多晶体管）的考虑，在AMD64架构 [4] 中只支持到52位（4PB）的地址总线和48位（256TB）的虚拟地址空间，所以目前64位的硬件实际能够支持的最大内存只有256TB。此外，操作系统一侧也还会施加自己的约束，64位的Linux则分别支持47位（128TB）的进程虚拟地址空间和46位（64TB）的物理地址空间，64位的Windows系统甚至只支持44位（16TB）的物理地址空间。
尽管Linux下64位指针的高18位不能用来寻址，但剩余的46位指针所能支持的64TB内存在今天仍然能够充分满足大型服务器的需要。鉴于此，ZGC的染色指针技术继续盯上了这剩下的46位指针宽度，将其高4位提取出来存储四个标志信息。通过这些标志位，虚拟机可以直接从指针中看到其引用对象的三色标记状态、是否进入了重分配集（即被移动过）、是否只能通过finalize()方法才能被访问到。当然，由于这些标志位进一步压缩了原本就只有46位的地址空间，也直接导致ZGC能够管理的内存不可以超过4TB（2的42次幂） 。

3）收集过程
·并发标记 （Concurrent Mark）：与G1、Shenandoah一样，并发标记是遍历对象图做可达性分析的阶段，前后也要经过类似于G1、Shenandoah的初始标记、最终标记（尽管ZGC中的名字不叫这些）的短暂停顿，而且这些停顿阶段所做的事情在目标上也是相类似的。与G1、Shenandoah不同的是，ZGC的标记是在指针上而不是在对象上进行的，标记阶段会更新染色指针中的Marked 0、Marked 1标志位。
·并发预备重分配 （Concurrent Prepare for Relocate）：这个阶段需要根据特定的查询条件统计得出本次收集过程要清理哪些Region，将这些Region组成重分配集（Relocation Set）。重分配集与G1收集器的回收集（Collection Set）还是有区别的，ZGC划分Region的目的并非为了像G1那样做收益优先的增量回收。相反，ZGC每次回收都会扫描所有的Region，用范围更大的扫描成本换取省去G1中记忆集的维护成本。因此，ZGC的重分配集只是决定了里面的存活对象会被重新复制到其他的Region中，里面的Region会被释放，而并不能说回收行为就只是针对这个集合里面的Region进行，因为标记过程是针对全堆的。此外，在JDK 12的ZGC中开始支持的类卸载以及弱引用的处理，也是在这个阶段中完成的。
·并发重分配 （Concurrent Relocate）：重分配是ZGC执行过程中的核心阶段，这个过程要把重分配集中的存活对象复制到新的Region上，并为重分配集中的每个Region维护一个转发表（Forward Table），记录从旧对象到新对象的转向关系。得益于染色指针的支持，ZGC收集器能仅从引用上就明确得知一个对象是否处于重分配集之中，如果用户线程此时并发访问了位于重分配集中的对象，这次访问将会被预置的内存屏障所截获，然后立即根据Region上的转发表记录将访问转发到新复制的对象上，并同时修正更新该引用的值，使其直接指向新对象，ZGC将这种行为称为指针的“自愈”（Self-Healing）能力。这样做的好处是只有第一次访问旧对象会陷入转发，也就是只慢一次，对比Shenandoah的Brooks转发指针，那是每次对象访问都必须付出的固定开销，简单地说就是每次都慢，因此ZGC对用户程序的运行时负载要比Shenandoah来得更低一些。还有另外一个直接的好处是由于染色指针的存在，一旦重分配集中某个Region的存活对象都复制完毕后，这个Region就可以立即释放用于新对象的分配（但是转发表还得留着不能释放掉），哪怕堆中还有很多指向这个对象的未更新指针也没有关系，这些旧指针一旦被使用，它们都是可以自愈的。
·并发重映射 （Concurrent Remap）：重映射所做的就是修正整个堆中指向重分配集中旧对象的所有引用，这一点从目标角度看是与Shenandoah并发引用更新阶段一样的，但是ZGC的并发重映射并不是一个必须要“迫切”去完成的任务，因为前面说过，即使是旧引用，它也是可以自愈的，最多只是第一次
使用时多一次转发和修正操作。重映射清理这些旧引用的主要目的是为了不变慢（还有清理结束后可以释放转发表这样的附带收益），所以说这并不是很“迫切”。因此，ZGC很巧妙地把并发重映射阶段要做的工作，合并到了下一次垃圾收集循环中的并发标记阶段里去完成，反正它们都是要遍历所有对象的，这样合并就节省了一次遍历对象图 [9] 的开销。一旦所有指针都被修正之后，原来记录新旧对象关系的转发表就可以释放掉了。

#### ZGC收集器中的染色指针有什么用？

染色指针是一种直接将少量额外的信息存储在指针上的技术，可是为什么指针本身也可以存储额外信息呢？在64位系统中，理论可以访问的内存高达16EB（2的64次幂）字节 [3] 。实际上，基于需求（用不到那么多内存）、性能（地址越宽在做地址转换时需要的页表级数越多）和成本（消耗更多晶体管）的考虑，在AMD64架构 [4] 中只支持到52位（4PB）的地址总线和48位（256TB）的虚拟地址空间，所以目前64位的硬件实际能够支持的最大内存只有256TB。此外，操作系统一侧也还会施加自己的约束，64位的Linux则分别支持47位（128TB）的进程虚拟地址空间和46位（64TB）的物理地址空间，64位的Windows系统甚至只支持44位（16TB）的物理地址空间。
尽管Linux下64位指针的高18位不能用来寻址，但剩余的46位指针所能支持的64TB内存在今天仍然能够充分满足大型服务器的需要。鉴于此，ZGC的染色指针技术继续盯上了这剩下的46位指针宽度，将其高4位提取出来存储四个标志信息。通过这些标志位，虚拟机可以直接从指针中看到其引用对象的三色标记状态、是否进入了重分配集（即被移动过）、是否只能通过finalize()方法才能被访问到。当然，由于这些标志位进一步压缩了原本就只有46位的地址空间，也直接导致ZGC能够管理的内存不可以超过4TB（2的42次幂） 。

#### 说说类加载的过程

加载
验证
准备（为一些类变量分配内存，并将其初始化为默认值）
解析（将符号引用替换为直接引用。类和接口、类方法、接口方法、字段等解析）
初始化

#### 说下有哪些类加载器？

Bootstrap ClassLoader（启动类加载器）
Extention ClassLoader（扩展类加载器）
App ClassLoader（应用类加载器）

#### 什么是双亲委派机制？

双亲委派机制的意思是除了顶层的启动类加载器以外，其余的类加载器，在加载之前，都会委派给它的父加载器进行加载。这样一层层向上传递，直到祖先们都无法胜任，它才会真正的加载。

#### 双亲委派机制可以被违背吗？请举例说明。

可以被违背。
打破双亲委派的例子：Tomcat

对于一些需要加载的非基础类，会由一个叫作WebAppClassLoader的类加载器优先加载。等它加载不到的时候，再交给上层的ClassLoader进行加载。
这个加载器用来隔绝不同应用的 .class 文件，比如你的两个应用，可能会依赖同一个第三方的不同版本，它们是相互没有影响的。

#### Tomcat是怎么打破双亲委派机制的呢？

是通过重写ClassLoader#loadClass和ClassLoader#findClass 实现的。可以看图中的WebAppClassLoader，它加载自己目录下的.class文件，并不会传递给父类的加载器。但是，它却可以使用 SharedClassLoader 所加载的类，实现了共享和分离的功能。

#### Java对象的布局了解过吗？

对象头区域此处存储的信息包括两部分：
1、对象自身的运行时数据( MarkWord )，占8字节
存储 hashCode、GC 分代年龄、锁类型标记、偏向锁线程 ID 、 CAS 锁指向线程 LockRecord 的指针等， synconized 锁的机制与这个部分( markwork )密切相关，用 markword 中最低的三位代表锁的状态，其中一位是偏向锁位，另外两位是普通锁位。
2、对象类型指针( Class Pointer )，占4字节
对象指向它的类元数据的指针、 JVM 就是通过它来确定是哪个 Class 的实例。

实例数据区域 
此处存储的是对象真正有效的信息，比如对象中所有字段的内容

对齐填充区域
JVM 的实现 HostSpot 规定对象的起始地址必须是 8 字节的整数倍，换句话来说，现在 64 位的 OS 往外读取数据的时候一次性读取 64bit 整数倍的数据，也就是 8 个字节，所以 HotSpot 为了高效读取对象，就做了"对齐"，如果一个对象实际占的内存大小不是 8byte 的整数倍时，就"补位"到 8byte 的整数倍。所以对齐填充区域的大小不是固定的。

#### 

## MySQL

#### 了解过哪些存储引擎？各有什么优缺点？

常用的是MyISAM和InnoDB。
InnoDB：支持事务、支持外键、支持行级锁、不支持全文索引、
MyISAM：不支持事务、不支持外键、不支持行级锁、支持全文索引

#### 说一下什么是事务的ACID属性吧

1. 原子性（atomicity)
一个事务要么全部提交成功，要么全部失败回滚，不能只执行其中的一部分操作，这就是事务的原子性

2. 一致性（consistency)
事务的执行不能破坏数据库数据的完整性和一致性，一个事务在执行之前和执行之后，数据库都必须处于一致性状态。
如果数据库系统在运行过程中发生故障，有些事务尚未完成就被迫中断，这些未完成的事务对数据库所作的修改有一部分已写入物理数据库，这是数据库就处于一种不正确的状态，也就是不一致的状态

3. 隔离性（isolation）
事务的隔离性是指在并发环境中，并发的事务时相互隔离的，一个事务的执行不能不被其他事务干扰。不同的事务并发操作相同的数据时，每个事务都有各自完成的数据空间，即一个事务内部的操作及使用的数据对其他并发事务时隔离的，并发执行的各个事务之间不能相互干扰。
在标准SQL规范中，定义了4个事务隔离级别，不同的隔离级别对事务的处理不同，分别是：未授权读取，授权读取，可重复读取和串行化

4. 持久性（durability）
一旦事务提交，那么它对数据库中的对应数据的状态的变更就会永久保存到数据库中。--即使发生系统崩溃或机器宕机等故障，只要数据库能够重新启动，那么一定能够将其恢复到事务成功结束的状态

#### 事务的隔离级别了解过吗？

1、读未提交（Read Uncommited），该隔离级别允许脏读取，其隔离级别最低；比如事务A和事务B同时进行，事务A在整个执行阶段，会将某数据的值从1开始一直加到10，然后进行事务提交，此时，事务B能够看到这个数据项在事务A操作过程中的所有中间值（如1变成2，2变成3等），而对这一系列的中间值的读取就是未授权读取

2、授权读取也称为已提交读（Read Commited），授权读取只允许获取已经提交的数据。比如事务A和事务B同时进行，事务A进行+1操作，此时，事务B无法看到这个数据项在事务A操作过程中的所有中间值，只能看到最终的10。另外，如果说有一个事务C，和事务A进行非常类似的操作，只是事务C是将数据项从10加到20，此时事务B也同样可以读取到20，即授权读取允许不可重复读取。

3、可重复读（Repeatable Read)

就是保证在事务处理过程中，多次读取同一个数据时，其值都和事务开始时刻是一致的，因此该事务级别禁止不可重复读取和脏读取，但是有可能出现幻影数据。所谓幻影数据，就是指同样的事务操作，在前后两个时间段内执行对同一个数据项的读取，可能出现不一致的结果。在上面的例子中，可重复读取隔离级别能够保证事务B在第一次事务操作过程中，始终对数据项读取到1，但是在下一次事务操作中，即使事务B（注意，事务名字虽然相同，但是指的是另一个事务操作）采用同样的查询方式，就可能读取到10或20；

4、串行化

是最严格的事务隔离级别，它要求所有事务被串行执行，即事务只能一个接一个的进行处理，不能并发执行。

#### 说说InnoDB的索引原理

详见：https://www.cnblogs.com/williamjie/p/11081081.html

#### 说说InnoDB的MVCC机制

详见：https://baijiahao.baidu.com/s?id=1629409989970483292

#### 有了解过“回表”的概念吗？什么情况下会出现“回表”？

回表就是先通过数据库索引扫描出数据所在的行，再通过行主键id取出索引中未提供的数据，即基于非主键索引的查询需要多扫描一棵索引树。
当查询的字段在二级索引上没有的时候，就需要“回表”在主键索引上再查一次。

#### MySQL索引的类型

聚簇索引、二级（辅助）索引
B树索引、hash索引

#### 有做过MySQL的索引优化吗

详见：https://blog.csdn.net/m0_37984616/article/details/81047676

#### 什么是聚簇索引？

聚簇索引：将数据存储与索引放到了一块，找到索引也就找到了数据
非聚簇索引：将数据与索引分开存储，索引结构的叶子节点指向了数据的对应行

#### InnoDB有聚簇索引吗？MyIsam呢？

InnoDB有聚簇索引，主键索引就是聚簇索引。MyIsam没有聚簇索引，因为他的索引和记录行是分开存储的。

#### MyIsam的数据是怎么存储的？

MyIsam索引的节点中存储的是数据的物理地址（磁道和扇区），在查找数据时，查找到索引后，根据索引节点中的物理地址，查找到具体的数据内容。

#### InnoDB的数据是怎么存储的？

InnoDB的主键索引文件上直接存放该行数据，称为聚簇索引，非主索引指向对主键的引用。

#### InnoDB主键索引跟非主键索引在数据存储上的差异

主键索引的叶子节点存的是整行数据。在 InnoDB 里，主键索引也被称为聚簇索引（clustered index）。
非主键索引的叶子节点内容是主键的值。在 InnoDB 里，非主键索引也被称为二级索引（secondary index）。

#### InnoDB删除某条记录后，内部会怎么处理？

记录头信息里的delete_mask标记位设置为1（表示该记录已删除），同时将记录从记录行链表中断开，并加入到垃圾链表中，垃圾链表的空间后续可以复用。

#### InnoDB如果没有设置主键的话，它内部会怎么处理？

优先使用用户自定义主键作为主键，如果用户没有定义主键，则选取一个Unique键作为主键，如果表中连Unique键都没有定义的话，则InnoDB会为表默认添加一个名为row_id的隐藏列作为主键。所以我们从上表中可以看出：InnoDB存储引擎会为每条记录都添加 transaction_id 和 roll_pointer 这两个列，但是 row_id 是可选的（在没有自定义主键以及Unique键的情况下才会添加该列）。这些隐藏列的值不用我们操心，InnoDB存储引擎会自己帮我们生成的。

#### 为什么InnoDB一定会生成主键？

因为Innodb的数据结构是通过聚簇索引组织起来的，如果没有主键的话，通过其他索引回表的时候没法查到相应的数据行。

#### MySQL分库分表了解过吗？

详见：https://baijiahao.baidu.com/s?id=1622441635115622194

#### MySQL的redo日志和undo日志分别有什么用？

1）redo
作用：保证事务的持久性
MySQL作为一个存储系统，为了保证数据的可靠性，最终得落盘。但是，又为了数据写入的速度，需要引入基于内存的"缓冲池"。其实不止MySQL，这种引入缓冲来解决速度问题的思想无处不在。既然数据是先缓存在缓冲池中，然后再以某种方式刷新到磁盘，那么就存在因宕机导致的缓冲池中的数据丢失，为了解决这种情况下的数据丢失问题，引入了redo log。在其他存储系统，比如Elasticsearch中，也有类似的机制，叫translog。
但是一般讨论数据写入时，在MySQL中，一般叫事务操作，根据事务的ACID特性，如何保证一个事务提交后Durability的保证？而这就是 redo log 的作用。当向MySQL写用户数据时，先写redo log，然后redo log根据"某种方式"持久化到磁盘，变成redo log file，用户数据则在"buffer"中(比如数据页、索引页)。如果发生宕机，则读取磁盘上的 redo log file 进行数据的恢复。从这个角度来说，MySQL 事务的持久性是通过 redo log 来实现的。

2）undo
作用：实现事务回滚
Undo log是InnoDB MVCC事务特性的重要组成部分。当我们对记录做了变更操作时就会产生undo记录，Undo记录默认被记录到系统表空间(ibdata)中，但从5.6开始，也可以使用独立的Undo 表空间。
Undo记录中存储的是老版本数据，当一个旧的事务需要读取数据时，为了能读取到老版本的数据，需要顺着undo链找到满足其可见性的记录。当版本链很长时，通常可以认为这是个比较耗时的操作。
大多数对数据的变更操作包括INSERT/DELETE/UPDATE，其中INSERT操作在事务提交前只对当前事务可见，因此产生的Undo日志可以在事务提交后直接删除（谁会对刚插入的数据有可见性需求呢！！），而对于UPDATE/DELETE则需要维护多版本信息，在InnoDB里，UPDATE和DELETE操作产生的Undo日志被归成一类，即update_undo。

#### MySQL的redo日志的刷盘时机

log buffer空间不足时
事务提交时
后台线程不停的刷刷刷
正常关闭服务器时
做所谓的checkpoint时

#### MySQL有哪些锁？以及各种锁的作用？

详见：https://blog.csdn.net/qq_40378034/article/details/90904573


## Redis

#### Redis有哪些数据结构？

Redis 有 5 种基础数据结构，它们分别是：string(字符串)、list(列表)、hash(字典)、set(集合) 和 zset(有序集合)。这 5 种是 Redis 相关知识中最基础、最重要的部分。

#### Redis为什么那么快？

1、内存操作；
2、单线程，省去线程切换、锁竞争的开销；
3、非阻塞IO模型，epoll。

#### Redis如何实现分布式锁？

详见：https://www.cnblogs.com/wlwl/p/11651409.html

#### Redis是单线程还是多线程？

Redis6.0采用多线程IO，不过命令的执行还是单线程的。
Redis6.0之前，IO线程和执行线程都是单线程的。

#### 缓存失效？缓存穿透？缓存雪崩？缓存并发？

1. 缓存失效
缓存失效指的是大量的缓存在同一时间失效，到时DB的瞬间压力飙升。造成这种现象的原因是，key的过期时间都设置成一样了。解决方案是，key的过期时间引入随机因素，比如5分钟+随机秒这种方式。

2. 缓存穿透
缓存穿透是指查询一条数据库和缓存都没有的一条数据，就会一直查询数据库，对数据库的访问压力就会增大，缓存穿透的解决方案，有以下2种：
缓存空对象：代码维护较简单，但是效果不好。
布隆过滤器：代码维护复杂，效果很好。

3. 缓存雪崩
缓存雪崩 是指在某一个时间段，缓存集中过期失效。此刻无数的请求直接绕开缓存，直接请求数据库。
造成缓存雪崩的原因，有以下2种：
reids宕机。
大部分数据失效。

对于缓存雪崩的解决方案有以下2种：
搭建高可用的集群，防止单机的redis宕机。
设置不同的过期时间，防止同意之间内大量的key失效。

4. 缓存并发
有时候如果网站并发访问高，一个缓存如果失效，可能出现多个进程同时查询DB，同时设置缓存的情况，如果并发确实很大，这也可能造成DB压力过大，还有缓存频繁更新的问题。
一般处理方案是在查DB的时候进行加锁，如果KEY不存在，就加锁，然后查DB入缓存，然后解锁；其他进程如果发现有锁就等待，然后等解锁后再查缓存或者进入DB查询。

#### Redis中的热key怎么处理？

1、对热key进行分散处理。比如：在key上加上不同的前后缀，缓存多个key，使得各个key分散到不同的节点上。
2、采用多级缓存。

#### Redis中的大key怎么处理？

大key指的是value特别大的key。比如很长的字符串，或者很大的set等等。
大key会造成2个问题：1、数据倾斜，比如某些节点内存占用过高。2、当删除大key或者大key自动过期的时候，会造成QPS突降，因为Redis是单线程的缘故。
处理方案：可以将一个大key进行分片处理，比如：将一个大set分成多个小的set。

#### 使用Redis统计网站的UV，应该怎么做？

UV与PV不同，UV需要去重。一般有2种方案：
1、用BitMap。存的是用户的uid，计算UV的时候，做下bitcount就行了。
2、用布隆过滤器。将每次访问的用户uid都放到布隆过滤器中。优点是省内存，缺点是无法得到精确的UV。但是对于不需要精确知道具体UV，只需要大概的数量级的场景，是个不错的选择。

#### Redis事务机制了解过吗？

Redis事务的概念：
Redis 事务的本质是一组命令的集合。事务支持一次执行多个命令，一个事务中所有命令都会被序列化。在事务执行过程，会按照顺序串行化执行队列中的命令，其他客户端提交的命令请求不会插入到事务执行命令序列中。
Redis事务就是一次性、顺序性、排他性的执行一个队列中的一系列命令。　　

Redis事务没有隔离级别的概念：
批量操作在发送 EXEC 命令前被放入队列缓存，并不会被实际执行，也就不存在事务内的查询要看到事务里的更新，事务外查询不能看到。
Redis不保证原子性：
Redis中，单条命令是原子性执行的，但事务不保证原子性，且没有回滚。事务中任意命令执行失败，其余的命令仍会被执行。

Redis事务的三个阶段：
开始事务
命令入队
执行事务

Redis事务相关命令：
watch key1 key2 ... : 监视一或多个key,如果在事务执行之前，被监视的key被其他命令改动，则事务被打断 （ 类似乐观锁 ）
multi : 标记一个事务块的开始（ queued ）
exec : 执行所有事务块的命令 （ 一旦执行exec后，之前加的监控锁都会被取消掉 ）　
discard : 取消事务，放弃事务块中的所有命令
unwatch : 取消watch对所有key的监控

#### Redis key的淘汰策略有哪些？

8种：noeviction，volatile-lru，volatile-lfu，volatile-ttl，volatile-random，allkey-lru，allkeys-lfu，allkeys-random

#### Redis在什么情况下会触发key的回收？

2种情况：1、定时（抽样）清理；2、执行命令时，判断内存是否超过maxmemory。

#### Redis的持久化了解过吗？

Redis持久化有RDB和AOF这2种方式。
RDB：将数据库快照以二进制的方式保存到磁盘中。
AOF：以协议文本方式，将所有对数据库进行过写入的命令和参数记录到AOF文件，从而记录数据库状态。

#### Redis在集群种查找key的时候，是怎么定位到具体节点的？

使用crc16算法对key进行hash
将hash值对16384取模，得到具体的槽位
根据节点和槽位的映射信息（与集群建立连接后，客户端可以取得槽位映射信息），找到具体的节点地址
去具体的节点找key
如果key不在这个节点上，则redis集群会返回moved指令，加上新的节点地址给客户端，同时，客户端会刷新本地的节点槽位映射关系
如果槽位正在迁移中，那么redis集群会返回asking指令给客户端，这是临时纠正，客户端不会刷新本地的节点槽位映射关系

#### Redis集群各个节点之间是怎么保持数据一致性的？

主要考察点是Redis的Gossip协议。
详见：https://mp.weixin.qq.com/s/dW0I29Sw86lU0qHpxyhdmw

#### 用Redis做延时队列，具体应该怎么实现？

可以使用Zset实现。member是任务描述，score是执行时间，然后用定时器定时去扫描，一旦有执行时间小于或等于当前时间的任务，就立即执行。

#### Redis String的内部编码有哪些？

int、embstr、raw
10000以下的整数会使用缓存里的int常量。
长度小于等于44字节：embstr编码
长度大于44字节：raw编码

## Spring

#### Spring是怎么解决循环依赖的？

整个IOC容器解决循环依赖，用到的几个重要成员：
singletonObjects：一级缓存，存放完全初始化好的Bean的集合，从这个集合中取出来的Bean可以立马返回
earlySingletonObjects：二级缓存，存放创建好但没有初始化属性的Bean的集合，它用来解决循环依赖
singletonFactories：三级缓存，存放单实例Bean工厂的集合
singletonsCurrentlyInCreation：存放正在被创建的Bean的集合

IOC容器解决循环依赖的思路：
1. 初始化Bean之前，将这个BeanName放入三级缓存
2. 创建Bean将准备创建的Bean放入 singletonsCurrentlyInCreation （正在创建的Bean）
3. createNewInstance 方法执行完后执行 addSingletonFactory，将这个实例化但没有属性赋值的Bean放入二级缓存，并从三级缓存中移除
4. 属性赋值&自动注入时，引发关联创建
5. 关联创建时，检查“正在被创建的Bean”中是否有即将注入的Bean。如果有，检查二级缓存中是否有当前创建好但没有赋值初始化的Bean。如果没有，检查三级缓存中是否有正在创建中的Bean。至此一般会有，将这个Bean放入二级缓存，并从三级缓存中移除
6. 之后Bean被成功注入，最后执行 addSingleton，将这个完全创建好的Bean放入一级缓存，从二级缓存和三级缓存移除，并记录已经创建了的单实例Bean

#### Spring Boot手动装配有哪几种方式？

1. 使用模式注解 @Component 等（Spring2.5+）
2. 使用配置类 @Configuration 与 @Bean （Spring3.0+）
3. 使用模块装配 @EnableXXX 与 @Import （Spring3.1+）

其中使用 @Component 及衍生注解很常见，咱开发中常用的套路，不再赘述。
但模式注解只能在自己编写的代码中标注，无法装配jar包中的组件。为此可以使用 @Configuration 与 @Bean，手动装配组件（如上一篇的 @Configuration 示例）。但这种方式一旦注册过多，会导致编码成本高，维护不灵活等问题。
SpringFramework 提供了模块装配功能，通过给配置类标注 @EnableXXX 注解，再在注解上标注 @Import 注解，即可完成组件装配的效果。

#### Spring Boot自动配置原理

详见：https://blog.csdn.net/Dongguabai/article/details/80865599

## Netty

#### 你了解过哪些IO模型？

详见：https://www.cnblogs.com/sharing-java/p/10791802.html

#### 什么是Reactor模型？Reactor的3种版本都知道吗？

Reactor模式究竟是个什么东西呢？这要从事件驱动的开发方式说起。我们知道，对于应用服务器，一个主要规律就是，CPU的处理速度是要远远快于IO速度的，如果CPU为了IO操作（例如从Socket读取一段数据）而阻塞显然是不划算的。好一点的方法是分为多进程或者线程去进行处理，但是这样会带来一些进程切换的开销，试想一个进程一个数据读了500ms，期间进程切换到它3次，但是CPU却什么都不能干，就这么切换走了，是不是也不划算？
这时先驱们找到了事件驱动，或者叫回调的方式，来完成这件事情。这种方式就是，应用业务向一个中间人注册一个回调（event handler），当IO就绪后，就这个中间人产生一个事件，并通知此handler进行处理。这种回调的方式，也体现了“好莱坞原则”（Hollywood principle）-“Don't call us, we'll call you”，在我们熟悉的IoC中也有用到。看来软件开发真是互通的！
好了，我们现在来看Reactor模式。在前面事件驱动的例子里有个问题：我们如何知道IO就绪这个事件，谁来充当这个中间人？Reactor模式的答案是：由一个不断等待和循环的单独进程（线程）来做这件事，它接受所有handler的注册，并负责先操作系统查询IO是否就绪，在就绪后就调用指定handler进行处理，这个角色的名字就叫做Reactor。

Reactor的3种版本：单线程模式、多线程模式、主从多线程模式

#### 了解过粘包拆包吗？为什么会出现粘包拆包？怎么处理粘包拆包？

粘包的主要原因：发送方写入数据<套接字缓冲区大小；接收方读取套接字缓冲区数据不够及时。

拆包的主要原因：发送方写入数据>套接字缓冲区大小；发送方发送的数据大于协议的MTU（最大传输单元），不得已必须拆包。

如何处理：1、消息长度固定；2、消息之间用分隔符分隔；3、在消息头保留一个字段，用于描述消息的长度。

#### UDP协议会有粘包拆包的问题吗？为什么？

UDP不会有这个问题。
因为TCP是“数据流”协议，UDP是“数据报”协议。
UDP协议的数据包之间是没有联系，而且有明确边界的。

## 微服务

#### 微服务有哪些优缺点？

优点：
独立的可扩展性，每个微服务都可以独立进行横向或纵向扩展，根据业务实际增长情况来进行快速扩展；
独立的可升级性，每个微服务都可以独立进行服务升级、更新，不用依赖于其它服务，结合持续集成工具可以进行持续发布，开发人员就可以独立快速完成服务升级发布流程；
易维护性，每个微服务的代码均只专注于完成该单个业务范畴的事情，因此微服务项目代码数量将减少至IDE可以快速加载的大小，这样可以提高了代码的可读性，进而可以提高研发人员的生产效率；
语言无关性，研发人员可以选用自己最为熟悉的语言和框架来完成他们的微服务项目（当然，一般根据每个公司的实际技术栈需要来了），这样在面对新技术或新框架的选用时，微服务能够更好地进行快速响应；
故障和资源的隔离性，在系统中出现不好的资源操作行为时，例如内存泄露、数据库连接未关闭等情况，将仅仅只会影响单个微服务；
优化跨团队沟通，如果要完全实践微服务架构设计风格，研发团队势必会按照新的原则来进行划分，由之前的按照技能、职能划分的方式变为按照业务（单个微服务）来进行划分，如此这般团队里将有各个方向技能的研发人员，沟通效率上来说要优于之前按照技能进行划分的组织架构；
原生基于“云”的系统架构设计，基于微服务架构设计风格，我们能构建出来原生对于“云”具备超高友好度的系统，与常用容器工具如Docker能够很方便地结合，构建持续发布系统与IaaS、PaaS平台对接，使其能够方便的部署于各类“云”上，如公用云、私有云以及混合云。

缺点：
增加了系统复杂性；
运维难度增加；
本地调用变成RPC调用，接口耗时增加；
可能会引入分布式事务。

#### 作为注册中心，Zookeeper和Eureka有什么区别？

详见：https://mp.weixin.qq.com/s/B6F9Ea1GnDIou41Po3NMAQ

#### Service Mesh了解过吗？

详见：https://www.jianshu.com/p/27a742e349f7

## Zookeeper

#### Zookeeper有哪些节点类型？

4种：持久节点、持久有序节点、临时节点、临时有序节点。

#### 了解过Zookeeper的ZAB协议吗？

详见：https://blog.csdn.net/liuchang19950703/article/details/111406622

#### Zookeeper怎么实现分布式锁？

详见：https://blog.csdn.net/crazymakercircle/article/details/85956246

#### Zookeeper是怎么保证数据一致性的？

详见：https://blog.csdn.net/liuchang19950703/article/details/111406622

#### Zookeeper Leader选举过程是怎样的？

详见：https://blog.csdn.net/liuchang19950703/article/details/111406622

#### Zookeeper怎么实现服务注册？

详见：https://segmentfault.com/a/1190000019670015

## 消息队列

#### 消息队列有哪些应用场景？

异步处理、流量控制、服务解耦、消息广播

#### 消息队列的弊端有哪些？

数据延迟；增加系统复杂度；可能产生数据不一致的问题。

#### 使用消息队列，怎么确保消息不丢失？

在生产阶段，你需要捕获消息发送的错误，并重发消息。
在存储阶段，你可以通过配置刷盘和复制相关的参数，让消息写入到多个副本的磁盘上，来确保消息不会因为某个 Broker 宕机或者磁盘损坏而丢失。
在消费阶段，你需要在处理完全部消费业务逻辑之后，再发送消费确认。

#### 使用消息队列，如果处理重复消息？

1）利用数据库的唯一约束实现幂等
2）为更新的数据设置前置条件（CAS）
3）记录并检查操作（在发送消息时，给每条消息指定一个全局唯一的 ID，消费时，先根据这个 ID 检查这条消息是否有被消费过，如果没有消费过，才更新数据，然后将消费状态置为已消费。）

#### Kafka的消息是有序的吗？如果保证Kafka消息的顺序性？

Kafka只能保证局部有序，即只能保证一个分区里的消息有序。而其具体实现是通过生产者为每个分区的消息维护一个发送队列，我们需要将保证顺序的消息都发送到同一个分区中。并且由于Kafka会同时发送多个消息，所以还需指定max.in.flight.requests.per.connection为1，保证前一个消息发送成功，后一个消息才开始发送。

## 计算机网络

#### 说下TCP三次握手的过程

详见：https://baijiahao.baidu.com/s?id=1654225744653405133

#### TCP为什么需要3次握手

主要原因是为了防止旧的重复连接引起连接混乱问题。
比如在网络状况比较复杂或者网络状况比较差的情况下，发送方可能会连续发送多次建立连接的请求。如果 TCP 握手的次数只有两次，那么接收方只能选择接受请求或者拒绝接受请求，但它并不清楚这次的请求是正常的请求，还是由于网络环境问题而导致的过期请求，如果是过期请求的话就会造成错误的连接。
所以如果 TCP 是三次握手的话，那么客户端在接收到服务器端 SEQ+1 的消息之后，就可以判断当前的连接是否为历史连接，如果判断为历史连接的话就会发送终止报文（RST）给服务器端终止连接；如果判断当前连接不是历史连接的话就会发送指令给服务器端来建立连接。

#### TCP为什么需要4次挥手

TCP协议是一种面向连接的、可靠的、基于字节流的运输层通信协议。TCP是全双工模式，这就意味着，当主机1发出FIN报文段时，只是表示主机1已经没有数据要发送了，主机1告诉主机2，它的数据已经全部发送完毕了；但是，这个时候主机1还是可以接受来自主机2的数据；当主机2返回ACK报文段时，表示它已经知道主机1没有数据发送了，但是主机2还是可以发送数据到主机1的；当主机2也发送了FIN报文段时，这个时候就表示主机2也没有数据要发送了，就会告诉主机1，我也没有数据要发送了，之后彼此就会愉快的中断这次TCP连接。

#### TCP time_wait状态是主动断开方才有，还是被动断开方才有？还是两边都有？

主动断开方才有

#### TCP的keepalive机制了解过吗？

详见：https://blog.csdn.net/chrisnotfound/article/details/80111559https://blog.csdn.net/chrisnotfound/article/details/80111559

#### HTTP的keepalive和TCP的keepalive，有什么区别？

HTTP协议的Keep-Alive意图在于TCP连接复用，在同一个TCP连接上进行多次HTTP请求与响应数据的传输；TCP的Keepalive机制意图在于探测连接的对端是否存活。

#### TCP与UDP的区别？

详见：https://www.cnblogs.com/fundebug/p/differences-of-tcp-and-udp.html

#### 简述 HTTP1.0/1.1/2.0 的区别

* HTTP 1.0
HTTP 1.0 是在 1996 年引入的，从那时开始，它的普及率就达到了惊人的效果。
HTTP 1.0 仅仅提供了最基本的认证，这时候用户名和密码还未经加密，因此很容易收到窥探。
HTTP 1.0 被设计用来使用短链接，即每次发送数据都会经过 TCP 的三次握手和四次挥手，效率比较低。
HTTP 1.0 只使用 header 中的 If-Modified-Since 和 Expires 作为缓存失效的标准。
HTTP 1.0 不支持断点续传，也就是说，每次都会传送全部的页面和数据。
HTTP 1.0 认为每台计算机只能绑定一个 IP，所以请求消息中的 URL 并没有传递主机名（hostname）。

* HTTP 1.1
HTTP 1.1 是 HTTP 1.0 开发三年后出现的，也就是 1999 年，它做出了以下方面的变化
HTTP 1.1 使用了摘要算法来进行身份验证
HTTP 1.1 默认使用长连接，长连接就是只需一次建立就可以传输多次数据，传输完成后，只需要一次切断连接即可。长连接的连接时长可以通过请求头中的 keep-alive 来设置
HTTP 1.1 中新增加了 E-tag，If-Unmodified-Since, If-Match, If-None-Match 等缓存控制标头来控制缓存失效。
HTTP 1.1 支持断点续传，通过使用请求头中的 Range 来实现。
HTTP 1.1 使用了虚拟网络，在一台物理服务器上可以存在多个虚拟主机（Multi-homed Web Servers），并且它们共享一个IP地址。

* HTTP 2.0
HTTP 2.0 是 2015 年开发出来的标准，它主要做的改变如下
头部压缩，由于 HTTP 1.1 经常会出现 User-Agent、Cookie、Accept、Server、Range 等字段可能会占用几百甚至几千字节，而 Body 却经常只有几十字节，所以导致头部偏重。HTTP 2.0 使用 HPACK 算法进行压缩。
二进制格式，HTTP 2.0 使用了更加靠近 TCP/IP 的二进制格式，而抛弃了 ASCII 码，提升了解析效率
强化安全，由于安全已经成为重中之重，所以 HTTP2.0 一般都跑在 HTTPS 上。
多路复用，即每一个请求都是是用作连接共享。一个请求对应一个id，这样一个连接上可以有多个请求。

#### HTTPS的原理了解过吗？

详见：https://segmentfault.com/a/1190000018992153

#### TCP里Nagle算法了解过吗？可以禁用吗？在Java里怎么禁用？

详见：https://blog.csdn.net/wdscq1234/article/details/52432095
可以禁用。
在Java里可以通过设置socket里的TcpNoDelay选项，来禁用Nagle算法。

#### HTTP协议为什么无法实现服务端推送？

HTTP协议是建立在TCP协议之上的应用层协议，而TCP协议本身是面向连接、可靠的、支持双向的传输层协议，因此理论上任何一种建立在TCP协议之上的应用层协议都是支持服务端推送的。
那为什么我们不使用HTTP协议实现服务端推送呢？这其实不是HTTP协议本身的问题，而是HTTP客户端跟服务端实现的问题。
因为大多数的HTTP客户端只实现了响应报文的解析，没有实现请求报文的解析，这意味着，及时服务端给客户端发送了请求报文（推送数据）了，客户端也解析不了，所以也就没办法做到服务端推送了。
解决的方式也很简单，改造客户端，让他也支持请求报文的解析就行了，这样服务端就可以给客户端发送请求报文，实现服务端推送了。
但是这样改造的成本太大了，再加上HTTP1.1是文本协议，本身效率并不高，因此我们一般使用其他应用层协议来实现服务端推送，而不使用HTTP协议。

#### websocket协议升级过程了解过吗？

详见：https://mp.weixin.qq.com/s/aolwd8SYib6GD3xAnrxSEQ

## 数据结构与算法

#### 说下你熟悉的排序算法

详见：https://www.cnblogs.com/onepixel/articles/7674659.html

#### 布隆过滤器了解过吗？

详见：https://mp.weixin.qq.com/s/VGeOe4DsZmjkkJ6Ovhf8jQ

#### 一致性hash算法了解过吗？

详见：https://mp.weixin.qq.com/s/bCH-aU8cKS3uT6PwRYNJtA

## 设计模式

#### Java怎么实现单例模式？

详见：https://mp.weixin.qq.com/s/3G3OdsD-bhqUfVW4ySkq5Q

#### 什么是代理模式？什么是动态代理？Java中动态代理有哪些实现方式？

详见：https://www.cnblogs.com/qlqwjy/p/7550609.html

#### 什么是模板方法模式？试举例说明。

详见：https://www.cnblogs.com/adamjwh/p/10919149.html

## 分布式

#### 分布式id如何生成？

详见：https://mp.weixin.qq.com/s/eakphQDWKrsUnIwTj8zMQA

#### 雪花算法了解过吗？

雪花算法生成的是Long类型的ID，一个Long类型占8个字节，每个字节占8比特，也就是说一个Long类型占64个比特。
雪花ID组成结构：正数位（占1比特）+ 时间戳（占41比特）+ 机器ID（占5比特）+ 数据中心（占5比特）+ 自增值（占12比特），总共64比特组成的一个Long类型。
第一个bit位（1bit）：Java中long的最高位是符号位代表正负，正数是0，负数是1，一般生成ID都为正数，所以默认为0。
时间戳部分（41bit）：毫秒级的时间，不建议存当前时间戳，而是用（当前时间戳 - 固定开始时间戳）的差值，可以使产生的ID从更小的值开始；41位的时间戳可以使用69年，(1L << 41) / (1000L * 60 * 60 * 24 * 365) = 69年
工作机器id（10bit）：也被叫做workId，这个可以灵活配置，机房或者机器号组合都可以。
序列号部分（12bit），自增值支持同一毫秒内同一个节点可以生成4096个ID

#### 什么是CAP定理？

详见：http://www.ruanyifeng.com/blog/2018/07/cap.html

#### 分布式事务了解过吗？

详见：https://mp.weixin.qq.com/s/amuBimPo7lnfsfo5Pyzc-w

#### 什么是二阶段提交（2PC）？什么是三阶段提交（3PC）？

详见：https://mp.weixin.qq.com/s/amuBimPo7lnfsfo5Pyzc-w

#### TCC了解过吗？

详见：https://mp.weixin.qq.com/s/amuBimPo7lnfsfo5Pyzc-w

#### Paxos算法了解过吗？

详见：https://blog.csdn.net/westbrookliu/article/details/99713365

#### Zookeeper的Zab协议了解过吗？

详见：https://blog.csdn.net/liuchang19950703/article/details/111406622

#### 知道什么是Gossip协议吗？

详见：https://mp.weixin.qq.com/s/dW0I29Sw86lU0qHpxyhdmw




