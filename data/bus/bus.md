# android 数据传递相关的优秀第三方依赖包

* EventBus Android优化事件总线，简化了活动、碎片、线程、服务等之间的通信，代码少、质量好。  
源码地址：[EventBus](https://github.com/greenrobot/EventBus) 文档：[doc](http://greenrobot.org/eventbus/documentation/)

* RxBus 通过rxjava事件总线。这是一个事件总线，它允许您的应用程序有效地进行通信。
源码地址：[RxBus](https://github.com/AndroidKnife/RxBus) 文档：[doc](https://github.com/AndroidKnife/RxBus/blob/master/README.md)

* LifecycleModel LifecycleModel类用于以有意义的生命周期方式存储和管理与UI相关的数据，LifecycleModel类允许数据在屏幕旋转等配置变化后存活，还处理Activity / Fragment与其他应用程序的通信
源码地址：[LifecycleModel](https://github.com/JessYanCoding/LifecycleModel) 文档：[doc](https://github.com/JessYanCoding/LifecycleModel/blob/master/README.md)

* LiveEventBus [EventBus for Android，消息总线]，基于LiveData，具有生命周期感知能力，支持Sticky，支持AndroidX，支持跨进程，支持跨APP
  *  生命周期感知，消息随时订阅，自动取消订阅
  * 支持Sticky粘性消息
  * 支持AndroidX
  * 支持单APP跨进程通信
  * 支持跨APP通信
  * 支持设置LifecycleObserver（如Activity）接收消息的模式：
  * 整个生命周期（从onCreate到onDestroy）都可以实时收到消息
  * 激活状态（Started）可以实时收到消息，非激活状态（Stoped）无法实时收到消息，需等到Activity重新变成激活状态，方可收到消息
  
  
源码地址：[LiveEventBus](https://github.com/JeremyLiao/LiveEventBus)
