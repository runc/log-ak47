# log-ak47项目,又一个日志处理一条龙服务的轮子

## 但对比已有的日志处理工具,做了下面这些改进
```
   1, 提供一个web控制台,可以动态配置相关参数,管理各种agent(rsyslog,filbeat...)等
   2, 虽然同样支持plugin插件开发,但更容易,且不区分input,output
```

```
   参考资料框架,比如:
   Apache Flume
   Fluentd
   Logstash
   Chukwa
   Scribe
   Splunk Forwarder
   最后还有我司的jlogstash,至于我为什么还要开发jlogstash,原因最后我再揭晓.
```