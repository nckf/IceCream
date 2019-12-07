## IceCream

![logo](https://raw.githubusercontent.com/nckf/IceCream/master/logo.png)

## 索引
> #### 它是什么 ？
> #### `Server` `Group` `Client` 它们分别是什么 ？


## 正文
### 1. 它是什么？
> **IceCream** 是一套 `云控` + `群控` 系统的结合。能够通过 `Group` 系统操作 ， 也可以不需要依靠 `Group` 运行。

### 2. `Server` `Group` `Client` 它们分别是什么 ？
> **Server** 是 `IceCream` 的 PHP 服务器端，它基于 `Laravel` 开发。提供了如 `验证` `登陆` `注册` `激活` 等基础功能 API.

> **Group** 是 `IceCream` 的 Windows 客户端，它是基于 `C# .NET` + `CefSharp` + `ADB` 等技术开发的；它实现了能够通过 `WebSocket` 与 `Server` 端双向通讯。以及通过 `ADB` + `Socket` 与 `Client` 端进行双向通讯

> **Client** 是 `IceCream` 的 Android 客户端；它是基于 `Auto.JS 4.1.1` 开发的。实现了对 `Server` 端的单向通讯，以及对 `Group` 端的双向通讯。
