# log-ext

```
   作为日志处理框架,怎么可能缺少对log4j/logback的直接支持呢?
```

```
   当前的思路可以扩展sl4j,这样借力,不用适配各种日志框架,直接基于sl4j,日志直接经过log-ak47处理最终落地到elasticsearch或者hdfs等
```