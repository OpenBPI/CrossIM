## 跨云CROSSIM解决方案

跨云CROSSIM是一款采用了“跨生态共享”技术的即时通信IM解决方案。

跨生态共享技术具备2个特点：

（1） 生态与生态之间的聊天是互通的。无需下载和注册其他生态的账号

（2） 从一个生态（app）进入其他所有的生态（小程序），无需再次注册。

### 主要功能
（1）跨界单聊

跨界单聊功能，可以让您的用户与其他生态上的用户直接进行互通的私聊。

（2）跨界群聊

跨界群聊可以让不同生态（app）离的用户在同一个群里聊天。

（3）跨界小程序

跨界小程序的特点是研发一次小程序，上万个生态通用，帮助小微企业解决无法建立程序员生态的难题。

### 主要包括一下项目：

| [GitHub仓库地址(主站)](https://github.com/openbpi/crossim)      | [码云仓库地址(镜像)](https://gitee.com/apowner)        | 说明                                                                                      | 备注                                           |
| ------------------------------------------------------------ | ----------------------------------------------------- | ----------------------------------------------------------------------------------------- | ---------------------------------------------- |
| [ospn-connector](https://github.com/openbpi/ospn-connector)             | [ospn-connector](https://gitee.com/apowner/ospn-connector)             | ospn-connector是与其他app交互信息的服务                                 | 要与其他app互通，就一定要打开ospn-connector服务，需要指定参数ipPeer为邻近节点。       |
| [ospn-ims](https://github.com/openbpi/ospn-ims)             | [ospn-ims](https://gitee.com/apowner/ospn-ims)             | ospn-ims是IM服务                                 | 托管IM节点，支持android、iOS、web、微信小程序（需要使用https）使用。      |
| [ospn-ims-share](https://github.com/openbpi/ospn-ims-share)             | [ospn-ims-share](https://gitee.com/apowner/ospn-ims-share)             | ospn-ims-share是IM服务                                 | 共享IM节点，支持android、iOS使用。      |
| [ospn-share-register](https://github.com/openbpi/ospn-share-register)    | [ospn-share-register](https://gitee.com/apowner/ospn-share-register)     | ospn-share-register是用户数据存储服务                                 | ospn-share-register存储用户数据（敏感数据）      |
| [crossim-android-sdk](https://github.com/openbpi/crossim-android-sdk) | [crossim-android-sdk](https://gitee.com/apowner/osnsdk-android) | Android SDK源码，不带UI                                                           |                                     |
| [crossim-ios-sdk](https://github.com/openbpi/crossim-ios-sdk) | [crossim-ios-sdk](https://gitee.com/apowner/osnsdk-ios) | iOS SDK源码，不带UI                                                           |                                     |
| [litapp-demo-java](https://github.com/openbpi/crossim-litapp-java-demo) | [litapp-demo-java](https://gitee.com/apowner/ospn-litapp-demo) | java版小程序demo                                                           |                                     |
| [litapp-demo-php](https://github.com/openbpi/crossim-litapp-php-demo) | [litapp-demo-php](https://gitee.com/apowner/ospn-litapp-php-demo) | php版小程序demo                                                           |                                     |
| [litapp-demo-net](https://github.com/openbpi/crossim-litapp-dot-net-demo) | [litapp-demo-net](https://gitee.com/apowner/ospn-litapp-dot-net-demo) | .net版小程序demo                                                           |                                     |
|   | [crossim-android-demo](https://gitee.com/apowner/crossim-android-demo) | android版demo                                                           | 供使用者参考、具备跨界聊天、跨界群聊、小程序平台功能。与ospn-ims、ospn-connector配套使用。        |
|   | [crossim-android-js-demo](https://gitee.com/apowner/crossim-android-js-demo) | android版demo                                                           | 该demo与crossim-android-demo的区别是，该demo为h5项目量身定制，通过简单配置编译即可生成apk，与ospn-ims、ospn-connector配套使用。       |
|   | [crossim-share-android](https://gitee.com/apowner/crossim-share-android) | android版demo                                                           | 该demo演示了敏感数据的存放以及可切换到任意共享IM节点上使用。与ospn-share-register、ospn-ims-share、ospn-connector配套使用，仅供使用者参考。       |
| [docs](https://github.com/)                 | [docs](https://gitee.com/)                 | IM相关文档 |                                                |  |


### 问题交流

1. 如果大家发现bug，请在GitHub提issue
2. 其他问题，请到[社联网社区论坛](http://47.92.123.66:8080)进行交流学习
3. 微信号 cannontech

### 使用共享IM服务
共享节点是由参与的志愿者提供的。有一部分是免费的，一部分是需要使用者共同均分费用的。

获得更多的共享IM服务请加微信群

<img src="http://www.openspn.com/groupid.jpg" width = 50% height = 50% />

### 目前可免费使用的共享IM节点

| 节点IP                                                                             | 备注                                           |
| ----------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| 103.163.46.82  | 共享IM节点    | 
| 47.92.123.66  | 共享IM节点    | 
| 39.100.133.144  | 共享IM节点    | 
| 45.32.90.120  | 共享IM节点(美国)   | 
| 39.100.147.50  | 托管IM节点，支持android、ios、web   | 
|                          |                                                |  |


**托管节点39.100.147.50**

该节点提供websocket和android、IOS服务

账号注册
端口：8080

命令：
>{
>"command":"registerUser",
>"username":"username"，
>"password":"password"
>}


### 体验Demo

<img src="https://pwelfare.com/download/1.png" width = 25% height = 25% />
身边大爱app

华为、小米、OPPO、vivo应用市场可下载。
[下载地址 ](https://pwelfare.com/download)


<img src="https://www.yjj520.com/assets/imges/logo.png" width = 100% height = 100% />
圆家家app

华为、小米、OPPO、vivo应用市场可下载。
[下载地址 www.yjj520.com](https://www.yjj520.com) 


<img src="http://www.openspn.com/tubiao19.png" width = 25% height = 25% />
跨云社联网app

小米、OPPO、vivo应用市场可下载。
[下载地址 ](http://www.openspn.com/download.html)


<img src="http://www.openspn.com/picture/chewlogo.jpg" width = 25% height = 25% />
教育全景地图app

OPPO、vivo应用市场可下载。
[下载地址 ](http://www.openspn.com/deploy/chewbank_20210920.apk)


### 应用截图

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />

<img src="" width = 50% height = 50% />


## 升级说明

## 特别感谢

您的star是我们坚持做“跨生态共享”技术的动力

