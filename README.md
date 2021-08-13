# DoNote

<p align='left'>
<img src="https://img.shields.io/github/stars/deepindo/DoNote.svg">
<img src="https://img.shields.io/github/forks/deepindo/DoNote.svg">
<img src="https://img.shields.io/badge/platform-iOS-ff69b4.svg">
<img src="https://img.shields.io/badge/PR-welcome%20!-brightgreen.svg?colorA=a0cd34">
<img src="https://img.shields.io/packagist/l/doctrine/orm.svg">
</p>

> 持续更新中！！！

- **前言**: 从事iOS开发几年了，一直在业务需求及不同的项目中转动，对于基础知识及一些底层的知识一直不求甚解，期间也多次因为生活中的一地鸡毛，而处于一种惫懒，拖延的恶性循环中，这对于“出身”并不是特别好的开发而言是灾难性的，若是仍不求自救，可能一辈子就这样了。

- **行动**: 在这里从全局的角度将iOS的开发舆图整理出来，然后逐渐补全学习或者整理笔记，另根据知识整理面试题集，知其然，知其所以然，还得能条理的表达出来。以上作为自己`自救`的一个方式吧！**知行合一**，真正做到很难，0到1的过程，就从这第一步开始吧！


### 一、思维

#### 1. OC Basic

  - [ ] **Data Structure** - 数据结构 
        <br/> [管理对象内存的数据结构以及操作算法--SideTables、RefcountMap、weak_table_t](http://www.cocoachina.com/articles/19030)
  - [ ] **Memory Management** - 内存管理
        <br/> [iOS中引用计数相关问题](https://www.jianshu.com/p/13c9199350de/)
        <br/> [iOS中类、元类、isa详解](http://www.cocoachina.com/articles/21805)
        <br/> [SideTable](https://github.com/deepindo/DoNote/wiki/%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86-SideTable)

  - [x] **Property**
        <br/> [OC中属性修饰符](https://github.com/deepindo/DoNote/wiki/OC%E4%B8%AD%E5%B1%9E%E6%80%A7%E4%BF%AE%E9%A5%B0%E7%AC%A6)
        <br/> [weakSelf、strongSelf、@weakify、@strongify](https://github.com/deepindo/DoNote/wiki/iOS%E4%B8%AD%E7%9A%84weakSelf%E3%80%81strongSelf%E3%80%81@weakify%E3%80%81@strongify)
        <br/> [weakSelf与strongSelf的理解](https://github.com/deepindo/DoNote/wiki/weakSelf%E4%B8%8EstrongSelf%E7%9A%84%E7%90%86%E8%A7%A3)

  - [ ] **KVO**
  - [ ] **KVC**
  - [ ] **Block**
  - [ ] **Delegate**
  - [ ] **Runloop** 
        <br/> [CFRunLoop](https://github.com/deepindo/DoNote/wiki/CFRunLoop)

  - [ ] **Runtime**
        <br/> [Objc Runtime](https://github.com/deepindo/DoNote/wiki/Objc-Runtime)

  - [ ] **Multithreading** - 多线程
        <br/> [dispatch_group](https://github.com/deepindo/DoNote/wiki/iOS-dispatch_group)

  - [ ] **Network** - http, https
        <br/> [iOS网络请求](https://github.com/deepindo/DoNote/wiki/iOS%E7%BD%91%E7%BB%9C%E8%AF%B7%E6%B1%82)

  - [ ] **Native&JS** - 原生成JS交互

  - [x] **Encryption** - 加密与解密
        <br/> [iOS RSA的网络安全模型、iOS签名机制总结（登录、token安全、签名）](https://www.jianshu.com/p/2927ca2b3719)
        <br/> [iOS,一行代码进行RSA、DES 、AES、MD5加密、解密](http://www.cocoachina.com/articles/16480)
        <br/> [iOS加密--AES（CBC）和RSA组合加密（避坑）](https://www.jianshu.com/p/4449b0040b24)
        <br/> [iOS加密方式（RSA签名加密、AES加密等）](https://blog.csdn.net/IT_201607/article/details/76162551)


  - [x] **Algorithm** - 算法
        <br/> [算法](https://github.com/deepindo/DoNote/wiki/%E7%AE%97%E6%B3%95)
  - [ ] **objc_msgsend**
  - [x] **Design Patterns** - 设计模式.
  
        1. 创建模式：工厂模式、单子模式、建造者模式、原型模式、工厂方法模式
        2. 结构模式：外观模式、代理模式、适配器模式、组合模式、装饰模式、桥模式、共享模式
        3. 行为模式：模板模式、纪念品模式、观察者模式、责任链模式、命令模式、声明模式、策略模式、中介模式、解释器模式、访问模式
        4. 框架模式: MVC、MVVM、MVP
                  <br/> [MVC、MVP和MVVM之间的区别是什么？](https://www.php.cn/faq/417265.html)

  - [ ] **UI** - UIKit相关的
        <br/> [layoutSubviews 和 layoutIfNeeded](https://github.com/deepindo/DoNote/wiki/iOS-layoutSubviews-%E5%92%8C-layoutIfNeeded)
        <br/> [MBProgressHud 自定义背景 背景色 标题颜色](https://github.com/deepindo/DoNote/wiki/ios-MBProgressHud-%E8%87%AA%E5%AE%9A%E4%B9%89%E8%83%8C%E6%99%AF-%E8%83%8C%E6%99%AF%E8%89%B2-%E6%A0%87%E9%A2%98%E9%A2%9C%E8%89%B2)

  - [ ] **Third Party** - 第三方库
        <br/> [AFN]()

  - [ ] **SDKs** - SDK集合
        <br/> [iOS推送](https://github.com/deepindo/DoNote/wiki/iOS%E6%8E%A8%E9%80%81)
        <br/> [iOS日志及上报](https://github.com/deepindo/DoNote/wiki/iOS%E6%97%A5%E5%BF%97%E5%8F%8A%E4%B8%8A%E6%8A%A5)
        <br/> []()

#### 2. Swift 
  - [ ] **Struct**
  - [ ] **Protocol**
  - [ ] **Extension**
  - [ ] **Function** - 系统函数、API

        - Map & FlatMap
        
  - [ ] Others
        - [Swift与JSContext的交互](https://github.com/deepindo/DoNote/wiki/Swift%E4%B8%8EJSContext%E7%9A%84%E4%BA%A4%E4%BA%92)


#### 3. App

  - [x] [iOS app的编译过程](https://github.com/deepindo/DoNote/wiki/iOS-app%E7%9A%84%E7%BC%96%E8%AF%91%E8%BF%87%E7%A8%8B)
  - [x] [宏(define)与常量(const)的比较](https://github.com/deepindo/DoNote/wiki/iOS-%E5%AE%8F(define)%E4%B8%8E%E5%B8%B8%E9%87%8F(const)%E7%9A%84%E6%AF%94%E8%BE%83)
  - [x] [break、continue、return三者的区别](https://github.com/deepindo/DoNote/wiki/iOS%E4%B8%ADbreak%E3%80%81continue%E3%80%81return%E4%B8%89%E8%80%85%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [x] [向上取整、向下取整、四舍五入](https://github.com/deepindo/DoNote/wiki/iOS%E5%90%91%E4%B8%8A%E5%8F%96%E6%95%B4%E3%80%81%E5%90%91%E4%B8%8B%E5%8F%96%E6%95%B4%E3%80%81%E5%9B%9B%E8%88%8D%E4%BA%94%E5%85%A5)
  - [x] [UUID](https://github.com/deepindo/DoNote/wiki/iOS-%E5%85%B3%E4%BA%8EUUID)
  - [x] [use_frameworks! 和 #use_frameworks!的区别](https://github.com/deepindo/DoNote/wiki/use_frameworks!-%E5%92%8C-%23use_frameworks!%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [x] [iOS新闻类App内容页技术探索](https://github.com/deepindo/DoNote/wiki/iOS%E6%96%B0%E9%97%BB%E7%B1%BBApp%E5%86%85%E5%AE%B9%E9%A1%B5%E6%8A%80%E6%9C%AF%E6%8E%A2%E7%B4%A2)
  - [ ] **App优化** 
```
        - 启动优化
        - 内存优化
        - 界面优化
        - 架构优化
          <br/> [App性能优化](https://github.com/deepindo/DoNote/wiki/APP%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96)
```    

### 二、面试集

1. [iOS面试题大全--(附答案)](https://www.jianshu.com/p/e709fde38de3)
2. [iOSInterviewsAndDevNotes](https://github.com/DevDragonLi/iOSInterviewsAndDevNotes)
3. [全新角度剖析--iOS面试](https://juejin.cn/post/6899689319809286158)
4. [2020-iOS面试题集合](https://github.com/LGCooci/LGiOSQuestions)
  

  
### <a name="二、iOS舆图"></a> 三、iOS舆图

iOS学习笔记通过wiki查看: <https://github.com/deepindo/DoNote/wiki>

![](./NSObject-UITree.png)

#### iOS基础
##### 布局
1. Autolayout
2. Snapkit
3. Masonry
4. Simplex算法
5. Flexbox
6. AsyncDisplayKit

##### 列表
1. UITableView
2. UICollectionView
3. ExpandableCell
4. Header
5. Placeholder
6. CollectionViewLayout
7. IGListKit

#### 图表
1. Charts

##### 图形
1. CoreGraphics
2. Git
3. 图片
4. 图片处理
5. PDF

##### 多媒休
1. 视频
2. 音频
3. 游戏
4. ARKit
5. CoreGraphics
6. CoreImage
7. Metal
8. GPUImage
9. SceneKit
10. Image I/O
11. SiriKit

##### AppService
1. 硬件
2. 定位(CoreLoation)
3. 通知
4. WebView
5. WebScoket
6. iCloud
7. WatchKit
8. 照片
9. 相机
10. 文件管理
11. 手势
12. 键盘
13. 蓝牙
14. NFC
15. ForceTouch
16. iBeacon
17. 地图
18. AppleTV
19. Email
20. PassBook
21. 支付
22. 权限
23. CoreMotion

#### iOS系统
##### Foundation

##### 界面
1. UIViewController
2. UINavigationController
3. ScrollView
4. 按钮
5. Label
6. 表单
7. 登录
8. 菜单
9. Navigation Bar
10. Popup
11. 进度条
12. 下拉刷新
13. SegmentedControl
14. Slider
15. SplashView
16. StatusBar
17. Stepper
18. Switch
19. TabBar
20. PickerView
21. 日历
22. 卡片
23. 自定义控件
24. 浮层
25. 弹窗
26. 标签
27. 通知中心
28. Text
29. TextKit
30. UIPageControl
31. CoreText
32. 字体
33. 多窗口
34. 向导


### 三、欢迎提交 PR / issue


- 收集整理不易，且赞且珍惜！如果你觉得此仓库对你有价值，欢迎 star/fork，蟹蟹🤝。

- **Email**: deepindo@foxmail.com, 有需要请联系 









