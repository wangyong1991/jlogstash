用java版本重写logstash目的是提升性能，因为ruby版本的logstash在性能方面没法满足要求。在4core，4g的虚拟机测试是ruby版本的5倍。

这里的少部分源代码也引用了其他第三方的。

jlogstash 的参数配置和使用看wiki介绍，现在的插件跟ruby版本相比还太少，希望更多的人参与开发。

