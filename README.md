[合集 \- .NET 开源工具(20\)](https://github.com)[1\..NET 开源快捷的数据库文档查询和生成工具07\-31](https://github.com/1312mn/p/18333223)[2\..NET 结果与错误处理利器 FluentResults08\-01](https://github.com/1312mn/p/18336221)[3\..NET\+WPF 桌面快速启动工具 GeekDesk08\-19](https://github.com/1312mn/p/18361056)[4\.Gradio.NET 支持 .NET 8 简化 Web 应用开发08\-26](https://github.com/1312mn/p/18370464)[5\..NET 开源实时监控系统 \- WatchDog08\-27](https://github.com/1312mn/p/18379779)[6\.实用接地气的 .NET 微服务框架08\-28](https://github.com/1312mn/p/18381195)[7\..NET 开源报表神器 Seal\-Report08\-30](https://github.com/1312mn/p/18385442)[8\..NET 最好用的验证组件 FluentValidation09\-03](https://github.com/1312mn/p/18393208)[9\..NET 8\.0 文档管理系统网盘功能的实现09\-04](https://github.com/1312mn/p/18392313)[10\..NET 8 \+ WPF 企业级工作流系统09\-05](https://github.com/1312mn/p/18395595)[11\..NET 多版本兼容的精美 WinForm UI控件库09\-06](https://github.com/1312mn/p/18389654)[12\.超轻量级、支持插件的 .NET 网络通信框架09\-09](https://github.com/1312mn/p/18401867)[13\..NET 8 微软免费开源的 Blazor UI 组件库09\-10](https://github.com/1312mn/p/18404007)[14\..NET 多版本 WinForm 开源控件库 SunnyUI09\-12](https://github.com/1312mn/p/18405542)[15\.C\# 开源教程带你轻松掌握数据结构与算法09\-13](https://github.com/1312mn/p/18408107):[milou加速器](https://xinminxuehui.org)[16\..NET 开源的功能强大的人脸识别 API09\-14](https://github.com/1312mn/p/18406833)[17\.C\# \+ WPF 音频播放器 界面优雅，体验良好09\-19](https://github.com/1312mn/p/18416419)[18\.C\# 开源浏览器性能提升，体验Chrome级速度09\-25](https://github.com/1312mn/p/18420917)[19\..NET 工具库高效生成 PDF 文档09\-26](https://github.com/1312mn/p/18429834)20\..NET 开源高性能 MQTT 类库09\-27收起**阅读目录**

* [前言](#_label0)
* [项目介绍](#_label1)
* [功能说明](#_label2)
* [功能特点](#_label3)
* [应用场景](#_label4)
* [使用方法](#_label5)
* [项目地址](#_label6)
* [总结](#_label7)
* [最后](#_label8)

## 前言


随着物联网（IoT）技术的迅猛发展，MQTT（消息队列遥测传输）协议凭借其轻量级和高效性，已成为众多物联网应用的首选通信标准。


MQTTnet 作为一个高性能的 .NET 开源库，为 .NET 平台上的 MQTT 客户端与服务器开发提供了强大的支持。


本文将全面介绍 MQTTnet 的核心功能、显著优势及其广泛的应用场景，帮助我们更好地利用工具提升物联网项目的效率与可靠性。


## 项目介绍


MQTTnet 是一个跨平台、高性能和开源的 MQTT 客户端库和服务端实现，是 .NET 平台上主流的 MQTT 实现之一。


基于 MQTTnet，用户可以方便地在 .NET 平台上集成 MQTT 功能，实现 MQTT 协议的消息传输等功能。


它支持 .NET Standard 2\.0 及以上版本，可在多版本 .NET 平台上运行，包括 .NET Framework、.NET Core 和 Xamarin。


MQTTnet 提供同步和异步操作、内置日志记录、QoS 支持等功能，并包含客户端和服务器组件，支持 MQTT 协议从 3\.1\.1 到 5\.0 的版本。


## 功能说明


### 客户端功能


MQTTnet 提供了强大的客户端功能，能够轻松连接到 MQTT 服务器并进行通信。


其主要特性包括：


* **连接管理：** 支持与单个或多个服务器建立和管理连接。
* **消息发布与订阅：** 支持不同 QoS 级别的消息发布和订阅，确保可靠传输。
* **保持活动：** 自动管理心跳，保持连接活跃。
* **重连机制：** 自动重连，确保通信稳定。


### 服务器功能


MQTTnet 同时支持构建 MQTT 服务器，可以创建自定义的 MQTT 服务。


其主要特性包括：


* **连接管理：** 支持大量并发连接。
* **消息路由：** 根据订阅规则将消息路由到相应客户端。
* **安全机制：** 支持多种身份验证和授权机制。
* **日志与监控：** 提供日志记录和监控功能，便于问题排查。


## 功能特点


1、客户端和服务器支持： MQTTnet 同时提供了客户端和服务器实现，便于构建完整的 MQTT 通信系统。


2、高性能： 采用异步编程模型，确保高效的消息处理和传输。


3、跨平台兼容性： 兼容多种 .NET Framework 版本，包括 .NET Core 及 .NET 5/6/7，支持不同操作系统和 CPU 架构。 易于使用： 提供简洁的 API，方便开发者集成 MQTT 功能。


4、支持 MQTT v5： 支持 MQTT 最新版本 5 及其所有特性。


5、可扩展性： 设计灵活，允许自定义和扩展功能。


6、安全性： 支持 SSL/TLS 加密，保障通信安全。


7、轻量级： 体积小巧，适用于资源受限的 IoT 设备。


## 应用场景


MQTTnet 可用于构建多种基于 MQTT 协议的应用程序，包括：


* 物联网 (IoT)： 适用于连接资源受限的设备，如传感器和执行器。
* 车联网： 用于连接车载设备并收集实时数据。
* 工业自动化： 用于连接工业控制系统和设备。


## 使用方法


### 1、安装 MQTTnet


需要将 MQTTnet 库添加到项目中，使用 NuGet 包管理器进行安装：




```
Install-Package MQTTnet
```


或者使用.NET CLI




```
dotnet add package MQTTnet
```


### 2、服务端代码


服务端代码编写，具体步骤可以参考以下步骤。


* 1、初始化 MQTT 服务器


创建一个 MQTT 服务器工厂实例，并使用它创建一个服务器。




```
using MQTTnet.Server;
var factory = new MqttFactory();
var mqttServer = factory.CreateMqttServer();
```


* 2、配置 MQTT 服务器选项


配置服务器选项，例如默认端口等。




```
var options = new MqttServerOptionsBuilder()
    .WithDefaultEndpointPort(1883)
    .Build();
```


* 3、启动 MQTT 服务器




```
await mqttServer.StartAsync(options
```


* 4、处理客户端连接


为服务器的 ClientConnectedHandler 和 ClientDisconnectedHandler 事件添加处理程序，以处理客户端连接和断开。




```
mqttServer.ClientConnectedHandler = new MqttServerClientConnectedHandlerDelegate(e =>
{
    Console.WriteLine($"客户端已连接: {e.ClientId}");
});

mqttServer.ClientDisconnectedHandler = new MqttServerClientDisconnectedHandlerDelegate(e =>
{
    Console.WriteLine($"客户端已断开连接: {e.ClientId}");
});
```


* 5、处理消息


为服务器的 ApplicationMessageReceivedHandler 事件添加处理程序，以处理接收到的消息。




```
mqttServer.ApplicationMessageReceivedHandler = new MqttApplicationMessageReceivedHandlerDelegate(e =>
{
    Console.WriteLine($"接收消息: {Encoding.UTF8.GetString(e.ApplicationMessage.Payload)} from client: {e.ClientId}");
});
```


* 6、停止 MQTT 服务器


完成通信消息后，需要停止服务器。




```
await mqttServer.StopAsync();
```


### 3、客户端代码


使用 MQTTnet创建 MQTT 客户端，具体步骤可以参下面代码。


* 1、初始化 MQTT 客户端


创建一个 MQTT 客户端工厂实例，并使用它创建一个客户端。




```
using MQTTnet;
using MQTTnet.Client;
using MQTTnet.Client.Options;

var factory = new MqttFactory();
var mqttClient = factory.CreateMqttClient();
```


* 2、配置 MQTT 客户端选项


配置客户端连接选项，例如服务器地址和端口。




```
var options = new MqttClientOptionsBuilder()
    .WithClientId("客户端ID")
    .WithTcpServer("mqtt服务器地址", 1883)
    .WithCleanSession()
    .Build();
```


* 3、连接到 MQTT 服务器


使用配置的选项连接到 MQTT 服务器。




```
await mqttClient.ConnectAsync(options, CancellationToken.None);
```


* 4、订阅主题


连接成功后，可以订阅一个或多个主题。




```
await mqttClient.SubscribeAsync(new MqttTopicFilterBuilder()
    .WithTopic("test/topic")
    .Build());
```


* 5、接收消息


为客户端的 ApplicationMessageReceivedHandler 事件添加处理程序，以接收消息：




```
mqttClient.UseApplicationMessageReceivedHandler(e =>
{
    Console.WriteLine($"接收消息: {Encoding.UTF8.GetString(e.ApplicationMessage.Payload)}");
});
```


* 6、发布消息


可以发布消息到指定的主题。




```
var message = new MqttApplicationMessageBuilder()
    .WithTopic("test/topic")
    .WithPayload("您好 MQTT")
    .WithQualityOfServiceLevel(MQTTnet.Protocol.MqttQualityOfServiceLevel.AtLeastOnce)
    .Build();

await mqttClient.PublishAsync(message, CancellationToken.None);
```


* 7、断开连接


完成消息发送后，断开与服务器的连接。




```
await mqttClient.DisconnectAsync();
```


通过上述步骤，我们实现了基本的发布与订阅功能：发布者将消息发布到 "test/Topic" 主题，订阅者订阅了同一主题，并在收到新消息时将其打印出来。


虽然是一个简单示例，但在实际项目中，可以根据具体需求进一步扩展功能，例如添加异常处理等。


## 项目地址


**Github:** https://github.com/dotnet/MQTTnet


**官网：**https://mqtt.org/


## 总结


本文介绍了 MQTT 的相关信息，并展示了如何在.NET 中进行基本的使用。


MQTT 还有许多高级功能，大家可以通过查阅 MQTTnet 的官方 API 文档进一步学习和使用其它功能。


## 最后


如果你觉得这篇文章对你有帮助，不妨点个赞支持一下！你的支持是我继续分享知识的动力。如果有任何疑问或需要进一步的帮助，欢迎随时留言。


也可以加入微信公众号**\[DotNet技术匠]** 社区，与其他热爱技术的同行一起交流心得，共同成长！**优秀是一种习惯，欢迎大家留言学习！**


![](https://img2024.cnblogs.com/blog/576536/202408/576536-20240814113403514-910171896.png)


