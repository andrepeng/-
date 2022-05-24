# -https://www.jianshu.com/p/5e5908ab3ea9  头条面试题

https://www.jianshu.com/p/e3a182bbe7f7  面试题

https://www.sohu.com/a/301383125_608959  面试题

https://blog.csdn.net/wen_haha/article/details/88362469 面试题

java 知识 https://snailclimb.gitee.io/javaguide/#/

github上整理的面试题
https://github.com/Moosphan/Android-Daily-Interview

比较好的博客专栏
https://cloud.tencent.com/developer/user/3504348

好书 https://www.kancloud.cn/redzealot2008/android-performance-patterns/345948

github上的资源
https://github.com/yangkun19921001/Blog#%E9%9F%B3%E8%A7%86%E9%A2%91

需要查的知识点
1. JIT 编译器
2. ConcurrentHashMap、HashTable、HashMap三兄弟
http://note.youdao.com/s/77iN5GuQ
hashmap https://juejin.cn/post/6844903921190699022

linkedHashMap
https://www.jianshu.com/p/8f4f58b4b8ab

java 基础知识
1. 
 equals  和  hashCode
https://www.cnblogs.com/skywang12345/p/3324958.html  
2.  Java泛型的最好解释
https://www.cnblogs.com/wuqinglong/p/9456193.html

3. String  StringBuilder  StringBuffer

java 面试题 https://www.jianshu.com/p/ce1fb8497883

4. finalize  finally

5. 算法题 https://github.com/MisterBooo/LeetCodeAnimation
https://leetcode-solution-leetcode-pp.gitbook.io/leetcode-solution/thinkings/basic-data-structure

https://github.com/doocs/leetcode


Java中Synchronized的使用
https://blog.csdn.net/qq_38011415/article/details/89047812

原理
https://www.cnblogs.com/aspirant/p/11470858.html

简单总结一下，同步块使用monitorenter和monitorexit指令，而同步方法是依靠方法修饰符上的flag——ACC_SYNCHRONIZED来完成的。其本质都是对一个对象监视器monitor进行获取，这个获取过程是排他的，也就是同一时刻只能有一个线程获得由synchronized所保护的对象的监视器。而这个监视器，也可以理解为一个同步工具，它是由java对象进行描述的，在Hotspor中，是通过ObjectMonitor来实现，每个对象中天然都内置了一个ObjectMonitor对象。作者：apkcore链接：https://juejin.cn/post/6844903863024091150来源：掘金著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

2. Activity生命周期
https://zhuanlan.zhihu.com/p/150787285

3. activity 启动模式
https://blog.csdn.net/sinat_14849739/article/details/78072401

singleTask本身自带clearTop这种功能
4.子线程是否可以 context.startActivity() (如ApplicationContext), 会不会有什么问题？
https://www.cnblogs.com/zhongle/articles/12037618.html

5. binder原理
https://blog.csdn.net/qian520ao/article/details/78089877
https://blog.csdn.net/zero9988/article/details/73518778
https://blog.csdn.net/zero9988/article/details/73824661
bindService原理
https://blog.csdn.net/luoshengyang/article/details/6745181

6. handler相关
https://blog.csdn.net/qian520ao/article/details/78262289?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.control

http://gityuan.com/2015/12/26/handler-message-framework/
怎么实现发送延时消息
https://blog.csdn.net/kisty_yao/article/details/71191175

7. 进程的启动
https://blog.csdn.net/luoshengyang/article/details/6747696

binder  https://www.jianshu.com/p/4ee3fd07da14

8. Service启动流程：
https://blog.csdn.net/luoshengyang/article/details/6677029
ActivityManagerProxy类的startService函数把这三个参数写入到data本地变量去，接着通过mRemote.transact函数进入到Binder驱动程序，然后Binder驱动程序唤醒正在等待Client请求的ActivityManagerService进程，最后进入到ActivityManagerService的startService函数中。
 这里调用Process.start函数创建了一个新的进程，指定新的进程执行android.app.ActivityThread类

9. 《Android应用程序启动过程源代码分析》其实是讲Activity的启动过程
https://blog.csdn.net/luoshengyang/article/details/6689748

https://cloud.tencent.com/developer/article/1356506  这篇比较好理解

ActivityThread
https://www.cnblogs.com/muhe221/articles/4893915.html

10.https：
http://note.youdao.com/s/bhXa11SW
https://blog.csdn.net/nnmmbb/article/details/103529565
https://juejin.cn/post/6886725940085424142

11.下载网络图片防止OOM
https://blog.csdn.net/zz51233273/article/details/105509676

12. view的绘制
https://guolin.blog.csdn.net/article/details/16330267?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.control

https://blog.csdn.net/guolin_blog/article/details/12921889

13.性能优化
https://blog.csdn.net/u012165769/article/details/106720230

14. Surface 和 TexureView

15 
https://blog.csdn.net/braintt/article/details/99685243

16 glide 缓存机制
https://www.kancloud.cn/smartsean/android/1106195

https://www.jianshu.com/p/b85f89fce019


17. 虚拟机相关知识
https://blog.csdn.net/jason0539/article/details/50440669

18 listview的优化
https://blog.csdn.net/leexiaobin1993/article/details/50956231
listiview和recyclerview区别
https://segmentfault.com/a/1190000007331249

19. java类的加载过程
https://zhuanlan.zhihu.com/p/73078336

20. jni 相关知识
https://blog.csdn.net/afei__/article/details/84889135

21HTTP1.0和HTTP1.1和HTTP2.0的区别
https://blog.csdn.net/ailunlee/article/details/97831912
https://www.cnblogs.com/smlp/p/9779206.html

22 https://zhuanlan.zhihu.com/p/42896432
一个具体的例子学习Java volatile关键字
23 https://blog.csdn.net/love_hot_girl/article/details/81164279
https如何验证证书

24 jvm先关
https://www.cnblogs.com/chengxuyuanxiaoyang/p/13692997.html



25 systrace 使用
https://blog.csdn.net/oncealong/article/details/90523110

26 java动态代理
https://blog.csdn.net/fangqun663775/article/details/78960545
https://www.jianshu.com/p/4e14dd223897
https://blog.csdn.net/qq_31859365/article/details/82902349

27. java类的加载过程
https://blog.csdn.net/xuemengrui12/article/details/82707473

28. aidl https://www.jianshu.com/p/29999c1a93cd

29 Messenger与AIDL的异同
https://www.cnblogs.com/qlky/p/7583517.html
messager的使用 https://www.ktanx.com/blog/p/629

30  activity4种启动模式
https://cloud.tencent.com/developer/article/1412586

31. java线程的内存模型
https://blog.csdn.net/huyongl1989/article/details/90680118

32 volatile关键字
https://blog.csdn.net/huyongl1989/article/details/90712393

33  yield， wait， sleep， interrupt， notify， join
https://blog.csdn.net/ArtisticProgramming/article/details/107056000

34 Java ThreadLocal使用
 https://www.jianshu.com/p/74f1a883da50

35.Serializable
https://blog.csdn.net/wn084/article/details/83338666

36 线程池
https://blog.csdn.net/u013332124/article/details/79587436
https://www.cnblogs.com/franson-2016/p/13291591.html

37 view post  和 handler post 的区别
https://www.jianshu.com/p/65b5a2a19ec3
https://www.jianshu.com/p/223a5185b733

37.Activity屏幕旋转重建ViewModel不销毁问题分析
https://blog.csdn.net/jackzhouyu/article/details/109031202

38. lru算法  https://blog.csdn.net/qq_25806863/article/details/77548468

39.Int与Integer的区别
https://www.cnblogs.com/bigdata-stone/p/10560759.html

40  okhttp面试题
https://www.it610.com/article/1344476411796205568.htm

https://juejin.cn/post/6844903999137660936

41 leakcanary
https://juejin.cn/post/6844903968263372808
https://www.jianshu.com/p/9cc0db9f7c52

42.  性能优化
https://zhuanlan.zhihu.com/p/30691789

43 操作系统相关的面试题
https://blog.csdn.net/nawuyao/article/details/52703384
