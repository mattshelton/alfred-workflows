> Surge Mac 4.0提供了HTTP API支持，因此终于可以打通外部App调用了。这里实现了Alfred的打通，比如快速切换代理模式等。

## install 

1. install node
2. 开启Surge API支持

##  如何开启Surge API支持

配置文件中增加如下配置

```
http-api = examplekey@0.0.0.0:6171

```

更多介绍参见这里 https://1991421.cn/2020/11/16/a12a6619/

### Surge API官方文档

据作者所说，未来还会开放更多API，敬请期待。。。

- https://manual.nssurge.com/others/http-api.html

## 注意
Surge Mac 4.0.0、Surge iOS 4.4.0开始提供HTTP API, 即该版本之前的均不支持


[![](https://img.shields.io/badge/version-v1.8-green)](./Surge.alfredworkflow)



<!-- more -->

## 实际效果

![](./surge.gif)
