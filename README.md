#### 一些简单的Dubbo的使用
1. com.alibaba.dubbo.demo
	* 先启动提供者(com.alibaba.dubbo.demo.Provider)
	* 再启动消费者(com.alibaba.dubbo.demo.Consumer)
2. com.alibaba.dubbo.callback(参数回调功能)
	* 先启动提供者(com.alibaba.dubbo.callback.impl.Provider)
	* 再启动消费者(com.alibaba.dubbo.callback.test.CallbackServiceTest.java)
3. com.alibaba.dubbo.notify(事件通知功能)
	* 在调用之前，调用之后，出现异常时，会触发oninvoke,onreturn,onthrow三个事件,可以配置当事件发生时，通知哪个类的哪个方法。
	* 先启动提供者(com.alibaba.dubbo.notify.ProviderTest)
	* 再启动消费者(com.alibaba.dubbo.notify.ConsumerTest)
