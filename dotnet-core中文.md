#目前下面的是google翻译的，有空会逐步更改。
# Awesome .NET Core 
> 1. 源地址https://github.com/thangchung/awesome-dotnet-core
> 2. 版权所有https://github.com/thangchung/awesome-dotnet-core

##内容

* [一般](#一般)
* [框架，库和工具](#框架，库和工具)
  * [API](#API)
  * [应用框架](#应用框架)
  * [应用程序模板](#应用程序模板)
  * [身份验证和授权](#身份验证和授权)
  * [区块链](#区块链)
  * [机器人](#机器人)
  * [自动部署](#自动部署)
  * [cssjs打包工具](#cssjs打包工具)
  * [缓存](#缓存)
  * [内容管理系统](#内容管理系统)
  * [代码分析](#代码分析)
  * [压缩](#压缩)
  * [编译器](#编译器)
  * [密码学](#密码学)
  * [数据库](#数据库)
  * [数据库驱动程序](#数据库驱动程序)
  * [数据库工具和实用程序](#数据库工具和实用程序)
  * [日期和时间](#日期和时间)
  * [分布式计算](#分布式计算)
  * [电子商务和支付](#电子商务和支付)
  * [异常](#异常)
  * [功能编程](#功能编程)
  * [图形](#图形)
  * [GUI](#GUI)
  * [IDE](#IDE)
  * [国际化](#国际化)
  * [IOC](#IOC)
  * [日志](#日志)
  * [机器学习和数据科学](#机器学习和数据科学)
  * [邮件](#邮件)
  * [数学](#数学)
  * [网络](#网络)
  * [其他](#其他)
  * [office](#office)
  * [ORM](#ORM)
  * [分析](#分析)
  * [队列和消息传递](#队列和消息传递)
  * [查询生成器](#查询生成器)
  * [调度程序和作业](#调度程序和作业)
  * [SDKs](#SDKs)
  * [安全](#安全)
  * [搜索](#搜索)
  * [序列化](#序列化)
  * [模板引擎](#模板引擎)
  * [测试](#测试)
  * [工具](#工具)
  * [Web框架](#Web框架)
  * [Web Socket工具](#WebSocket)
  * [Windows服务](#Windows服务)
  * [工作流程](#工作流程)
* [路线图](#路线图)
* [入门套件](#入门套件)
* [示例项目](#示例项目)
* [文章](#文章)
* [书籍](#书籍)
* [备忘录](#备忘录)
* [视频](#视频)
* [播客](#播客)
* [社区](#社区)

## 一般

* [ASP.NET核心文档](https://docs.asp.net/en/latest/) - 官方ASP.NET核心文档站点。
* [.NET核心文档](https://docs.microsoft.com/en-us/dotnet/articles/welcome) -  .NET Core，C#，F#和Visual Basic技术文档的主页，包括基本概念，入门说明，教程和示例。
* [.NET Core SDK](https://www.microsoft.com/net/core) -  .NET Core SDK是由Microsoft和.NET社区在[GitHub]上维护的通用开发平台(https：// github.com/dotnet/core)。
* [.NET平台标准](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - 旧版本和新版本的.NET之间存在差异。
* [.NET Standard 2.0简介](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - 介绍.NET Standard 2.0的内容和当前.NET标准中某些缺失部分的路线图。
* [Clean Code .NET / .NET Core](https://github.com/thangchung/clean-code-dotnet) - 适用于.NET / .NET Core的Clean Code概念。

##框架，库和工具

### API

* [autorest](https://github.com/Azure/autorest) -  Swagger(OpenAPI)规范代码生成器，具有C#和Razor模板。支持C#，Java，Node.js，TypeScript，Python和Ruby。 `4.5.x或以上`
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) - 一组库，它们将服务API版本添加到ASP.NET Web API，使用ASP.NET Web API添加OData，以及ASP.NET核心。
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) -  ASP.NET核心速率限制中间件。
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - 使用Kestrel和Consul的API Condenser / Reverse Proxy，包括轻量级consul库。
* [Flurl](https://github.com/tmenier/Flurl) - 适用于.NET的Fluent URL构建器和可测试的HTTP [https://flurl.dev](https://flurl.dev)。
* GraphQL
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) - 一个用于集成Dapper和graphql-dotnet项目的库，其中易用性和性能是主要关注点。
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore) -  ASP.NET Core MiddleWare创建GraphQL端点。
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) - 这个库是一个补充层，允许您使用现有的属性getter和方法自动将.NET类包装到GraphQL模式定义中作为场解析器
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) - 用于ASP.NET Core的GraphiQL中间件。
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - 基于[https://github.com/graphql/graphql-js](https://github)的.NETQL GraphQL的.com / graphql / graphql-JS)。
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) -  GraphQL for .NET。
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server) -  GraphQL for .NET  - 订阅传输WebSockets。
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) -  .Net Core和.NET Framework的GraphQL服务器。
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) -  Facebook GraphQL查询语言的FSharp实现[https://fsprojects.github.io/FSharp.Data.GraphQL] (https://fsprojects.github.io/FSharp.Data.GraphQL)。
  * [parser](https://github.com/graphql-dotnet/parser) -  .NET中GraphQL的词法分析器和解析器。
* [halcyon](https://github.com/visualeyes/halcyon) -  ASP.NET的HAL实现。
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) - 用于构建json：api兼容API的框架，目标是消除RESTful样板。
* [LightNode](https://github.com/neuecc/LightNode) - 基于OWIN的微型RPC / REST框架[http://neuecc.github.io/LightNode](http://neuecc.github.io/) LightNode)。
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy) - 适用于.NET Standard 2.0的类型安全的分布式REST库(NetCoreStack Flying Proxy)
* [NSwag](https://github.com/RSuter/NSwag) - 用于.NET，Web API和TypeScript的Swagger / OpenAPI工具链。 [http://NSwag.org](http://NSwag.org)。
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) - 开放数据协议(OData)支持创建基于HTTP的数据服务，允许使用统一资源标识符识别资源( URIs)并在抽象数据模型中定义，由Web客户端使用简单的HTTP消息进行发布和编辑。
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) -  OpenAPI Generator允许生成API客户端库(例如C#，TypeScript等)，服务器存根(ASP.NET Core，NancyFx等) ，OpenAPI规范(v2，v3)自动提供文档和配置。
* [refit](https://github.com/paulcbetts/refit) -  Xamarin和.NET的自动类型安全REST库。
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net) - 适用于所有C#平台的跨平台REST客户端
* [RestEase](https://github.com/canton7/RestEase) - 易于使用的类型安全REST API客户端库，简单且可自定义。
* [RestLess](https://github.com/letsar/RestLess) -  .Net Standard的自动类型安全无反射REST API客户端库。
* [Restier](https://github.com/OData/RESTier) -  RESTier是一个RESTful API开发框架，用于在.NET平台上构建基于OData V4的标准化RESTful服务。
* [Restsharp](https://github.com/restsharp/RestSharp) - 用于.NET的简单REST和HTTP API客户端
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - 无缝地为WebApi项目添加了一个全家桶。
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation) - 向Swagger添加FluentValidation规则。
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) - 一堆用于Swashbuckle.AspNetCore的有用过滤器。
* [ASP.NET CORE的WebAPIContrib](https://github.com/WebApiContrib/WebAPIContrib.Core) -  ASP.NET Core的社区贡献。

###应用程序框架
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) -  ASP.NET Boilerplate是一个专用于新的现代Web应用程序的通用应用程序框架。它使用已经熟悉的工具并实现最佳实践，为您提供SOLID开发体验。
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) -  async / await的帮助程序库。
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) - 高效可靠的UDP单播，UDP多播和IPC消息传输 -  Aeron的.NET端口。
* [akka.net](https://github.com/akkadotnet/akka.net) - 用于在.NET和Mono上构建高度并发，分布式和容错的事件驱动应用程序的工具包和运行时。
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) -  Aggregates.NET是一个框架，可以帮助开发人员将优秀的NServiceBus和EventStore库集成在一起。
* [ASP.NET MVC](https://github.com/aspnet/Mvc) - 模型视图控制器框架，用于构建动态网站，清晰分离关注点，包括合并的MVC，Web API和带Razor的Web页面。
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet) - 允许用最少的工作量构建实时Web应用程序和本机应用程序。定义Web API和Subscription API，以自动同步所连接客户端的数据集。
* [CAP](https://github.com/dotnetcore/CAP) - 具有本地持久消息功能的EventBus，用于SOA或微服务架构中的系统集成。
* [Carter](https://github.com/CarterCommunity/Carter) -  Carter是一个允许Nancy-esque路由与ASP.Net Core一起使用的库。
* [Chromely](https://github.com/mattkol/Chromely) -  Electron.NET的轻量级替代品，适用于.NET / .NET Core的Electron。
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) - 用于.NET的ETL框架(用于CSV，Flat，Xml，JSON，键值格式文件的分析器/写入器)。
* [CQRSlite](https://github.com/gautema/CQRSlite) - 用于帮助在C#中编写CQRS和Eventsourcing应用程序的轻量级框架。
* [dataaccess_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore) -  DataAccess工具箱包含使用工作单元和存储库模式在ASP.NET Core中使用Entity Framework Core 1.0进行数据访问的基类。
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) - 用于构建基于ASP.NET Core的高质量Web应用程序的轻量级和可扩展基础架构。
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) - 用于将程序集作为插件加载的.NET Core库。
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) -  DotnetSpider，一个类似于WebMagic和Scrapy的.NET标准网络爬行库。它是.NET的轻量级，高效且快速的高级Web爬行和抓取框架。
* [DotNetty](https://github.com/Azure/DotNetty) -  netty端口，事件驱动的异步网络应用程序框架。
* [dotvvm](https://github.com/riganti/dotvvm) -  Web应用程序的开源MVVM框架。
* [ElectronNET](https://github.com/ElectronNET/Electron.NET) - 使用ASP.NET NET Core构建跨平台桌面应用程序。
* [EmbedIO](https://github.com/unosquare/embedio) - 一个基于模块的小型跨平台模块，用于.NET Framework和.NET Core。
* [Ether.Network](https://github.com/Eastrall/Ether.Network) -  Ether.Network是一个开源网络库，允许开发人员通过TCP /创建简单，快速和可扩展的套接字服务器或客户端应用程序IP协议。
* [EventFlow](https://github.com/eventflow/EventFlow) - 异步/等待.NET的第一个CQRS + ES和DDD框架。
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - 用C#编写的轻量级快速库，用于读取Microsoft Excel文件。
* [ExtCore](https://github.com/ExtCore) - 用于创建基于ASP.NET Core 1.0的模块化和可扩展Web应用程序的免费，开源和跨平台框​​架。
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant) -  Finbuckle.MultiTenant是一个.NET标准库，用于为ASP.NET 2.0+设计的多租户支持。它提供租户解析，每租户应用配置和每租户数据隔离的功能。
* [fission](https://github.com/fission/fission) -  Kubernetes的快速服务器功能。
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - 远程过程调用(RPC)为构建分布式应用程序和服务提供了有用的抽象。此存储库中的库提供了gRPC协议的具体实现，通过HTTP / 2分层。这些库使用支持的语言的任意组合实现客户端和服务器之间的通信。
* [Halibut](https://github.com/OctopusDeploy/Halibut) - 使用基于SSL的JSON-RPC的.NET安全通信堆栈。
* [MagicOnion](https://github.com/neuecc/MagicOnion) - 基于gRPC的HTTP / 2 RPC流式框架，适用于.NET，.NET Core和Unity。
* [MassTransit](https://github.com/MassTransit/MassTransit) -  .NET分布式应用程序框架。
* [microdot](https://github.com/gigya/microdot) - 一个开源的.NET微服务框架。
* [MoreLINQ](https://github.com/morelinq/MoreLINQ) -  LINQ to Objects的扩展。
* [Nancy](https://github.com/NancyFx/Nancy) - 用于在.NET和Mono上构建基于HTTP的服务的轻量级，低仪式框架。
* [opencvsharp](https://github.com/shimat/opencvsharp) -  OpenCV的.NET Framework包装器。
* [orleans](https://github.com/dotnet/orleans) - 提供构建分布式高规模计算应用程序的直接方法的框架，无需学习和应用复杂的并发或其他扩展模式。
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) -  Golang和C#的快速分布式演员[http://proto.actor](http://proto.actor)。
* [resin](https://github.com/kreeben/resin) - 带有HTTP API和可插拔读/写管道的16位宽矢量空间搜索引擎。
* [RService.io](https://github.com/Stoom/RService.IO) -  ASP.Net核心RESTful微服务框架，专注于速度和易用性。
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - 为所有[https://servicestack.net](https://servicestack.net)精心设计，提供极其快速，令人愉快的网络服务。
* [Steeltoe OSS](https://github.com/SteelToeOSS) - 用于常见微服务模式的.NET工具包。
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore) - 一个在ASP.NET Core MVC项目中启用强类型路由的库。
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - 一个简单的库，用于创建基于CQRS模式的应用程序，支持属性路由和托管处理程序。在C#中开发，面向.NET Standard 1.0。
* [X.PagedList](https://github.com/dncuug/X.PagedList) - 用于轻松分页ASP.NET / ASP.NET Core中任何IEnumerable / IQueryable的库。

###应用程序模板
* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates) - 包含电池的项目模板，提供使您前往所需的最少代码。包括ASP.NET Core API和GraphQL模板。
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) -  ASP.NET Core 2.0 / React SPA模板应用程序。
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa) - 具有Angular CLI全功能应用程序的Asp.Net Core 2+和Angular 6 SPA。
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) - 带有存储库的ASP.NET MVC 5和ASP.NET Core的现成模板，服务，模型映射和DI和StyleCop警告已修复。
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) - 为ASP.NET Core中的MVC控制器和视图启用功能文件夹。
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio) - 用于Webpack，Visual Studio，ASP.NET Core和Angular的模板。应用程序的客户端和服务器端都在一个ASP.NET Core项目中实现，这使得部署更容易。
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate) - 基于[DNTFrameworkCore]的Boilerplate项目模板(https://github.com/rabbal/DNTFrameworkCore)
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju) -  dotnet新模板，具有很棒的架构风格！提高生产率，以设计基于六边形，清洁或事件采购架构样式的分层应用程序。它支持多个数据访问框架(MongoDB，EntityFramework，Dapper或Kafka)，并且完全可以测试。
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) -  Microsoft ASP.NET核心JavaScript服务。
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - 一个基于jQuery的HTML5小部件库，用于构建现代Web应用程序。 [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui)。
* [QuickApp](https://github.com/emonney/QuickApp) - 具有完整登录，用户和角色管理的ASP.NET Core / Angular4启动项目模板。
* [Serenity](https://github.com/volkanceylan/Serenity) -  Serenity是一个ASP.NET MVC / TypeScript应用程序平台，旨在通过基于服务的体系结构简化和缩短以数据为中心的业务应用程序的开发。
* [Toucan](https://github.com/mrellipse/toucan) - 用于构建单页应用程序的Boilerplate。服务器是围绕SOLID原则设计的多项目.Net Core解决方案。客户端是TypeScript 2，Vuejs 2，Vuex 2。

###身份验证和授权
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - 用于OWIN / Katana和ASP.NET Core的OpenID Connect / OAuth2服务器框架。
* [Auth0](https://github.com/auth0/auth0.net) - 用于现代身份的托管企业级平台。
* [Cierge](https://github.com/PwdLess/Cierge) -  Cierge是一个OpenID Connect服务器，用于处理用户注册，登录，配置文件，管理，社交登录等。 Cirege不使用密码，而是使用魔术链接/代码和外部登录来验证您的用户。
* [Identity](https://github.com/aspnet/Identity) -  ASP.NET Core Identity是用于构建ASP.NET Core Web应用程序的成员资格系统，包括成员资格，登录名和用户数据。
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - 用于ASP.NET Core 1.0和2.0的IdentityServer
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) -  EntityFramework持久层
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) -  MongoDB持久层
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - 实体框架核心持久层
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) -  IdentityServer4的dotnet cli模板。
* [openiddict](https://github.com/openiddict/openiddict-core) - 易于使用的OpenID Connect服务器，适用于ASP.NET Core。
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger) -  OAuth 2.0和OpenID Connect调试工具。
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - 使用Stormpath构建[简单，安全的Web应用程序](https://github.com/stormpath/stormpath-aspnetcore) ASP.NET核心。
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - 使用Stormpath构建[简单，安全的Web应用程序](https://github.com/stormpath/stormpath-aspnetcore) ASP.NET Core。(已弃用：加入OKTA后，将于2017年3月更新)
* [stuntman](https://github.com/ritterim/stuntman) - 利用ASP.NET身份在开发过程中模拟用户的库。

###区块链
* [BTCPayServer](https://github.com/btcpayserver/btcpayserver) - 与Bitpay API兼容的跨平台自托管服务器。
* [Meadow](https://github.com/MeadowSuite/Meadow) - 一个集成的以太坊实施和工具套件，专注于Solidity测试和开发。
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) - 用于.NET框架的综合比特币库。
* [NBlockchain](https://github.com/danielgerlag/NBlockchain) - 用于构建支持区块链的应用程序的.NET标准库
* [NBXplorer](https://github.com/dgarage/NBXplorer) - 比特币和Altcoin轻量级块浏览器。
* [NEO](https://github.com/neo-project/neo) - 开放智能经济网络。
* [Nethereum](https://github.com/Nethereum) - 将以太坊的热爱带到.NET。
* [Nethermind](https://github.com/NethermindEth/nethermind) -  .NET Core以太坊客户端
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) - 简单且经济实惠的端到端解决方案，用于在.Net框架上开发，测试和部署本机C#区块链应用程序。
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net) - 用于与Trezor Hardwarewallet交谈的跨平台C#库
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi) - 以隐私为重点，符合ZeroLink标准的比特币钱包。

### 机器人
* [BotSharp](https://github.com/SciSharp/BotSharp) - 使用机器学习算法在.NET Core中运行的100％C#开源AI Chatbot平台构建器。
* [NadekoBot](https://github.com/Kwoth/NadekoBot) - 用C#编写的开源，通用的Discord聊天机器人。
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) -  C#Telegram Bot API库。
* [Funogram](https://github.com/Dolfik1/Funogram) -  F#Telegram Bot Api库。

###构建自动化
* [cake-build](https://github.com/cake-build/cake) - 跨平台构建自动化系统。
* [CatLight](https://catlight.io) - 用于监视项目中的构建和任务的开发人员的状态通知程序。使用.Net Core和Electron构建。
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - 设置您的C#控制台输出样式！
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) - 用于使用.NET Core和.NET Core Tools的基本Docker镜像。
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET) - 用于将.NET核心应用程序打包成docker映像的.NET Cli工具：'dotnet dockerize'
* [FlubuCore](https://github.com/flubu-core/flubu.core) - 跨平台构建和部署自动化系统，用于使用C#代码构建项目和执行部署脚本。
* [GitInfo](https://github.com/kzu/GitInfo) - 来自MSBuild，C#和VB的Git和SemVer信息。
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) - 使用单个简单版本.txt文件中的版本标记程序集和NuGet包，并为非官方构建包含git commit ID。
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - 转到.NET Core Runtime的包装器。
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win) - 将现有Windows应用程序工作负载移植到Docker的PowerShell模块。
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor) - 在本地运行您的AppVeyor版本。
* [msbuild](https://github.com/Microsoft/msbuild) -  Microsoft Build Engine是一个用于构建应用程序的平台。
* [Nuke](https://github.com/nuke-build/nuke) - 跨平台构建自动化系统。
* [Opserver](https://github.com/opserver/Opserver) -  Stack Exchange的监控系统。
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) -  Visual Studio Team Services构建和发布代理。

###cssjs打包工具
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) -  Visual Studio扩展，让您可以配置JS，CSS和HTML文件的捆绑和缩小。
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) - 用于在JavaScript环境中呈现标记的ASP.NET MVC ViewEngine。适用于React和Angular服务器端呈现。
* [Smidge](https://github.com/Shazwazza/Smidge/) - 用于ASP.NET Core的轻量级运行时CSS / JavaScript文件缩小，组合，压缩和管理库。
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin) - 包含一组标记最小化器的.NET库。该项目的目标是通过减少HTML，XHTML和XML代码的大小来提高Web应用程序的性能。

###缓存
* [CacheManager](https://github.com/MichaCo/CacheManager) - 用C#编写的.NET的开源缓存抽象层。它支持各种缓存提供程序并实现许多高级功能。 [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [EasyCaching](https://github.com/dotnetcore/EasyCaching) - 开源缓存库，包含基本用法和缓存的一些高级用法，可以帮助我们更轻松地处理缓存。
* [更快](https://github.com/Microsoft/FASTER/tree/master/cs) - 来自Microsoft Research的快速键值存储。
* [Foundatio](https://github.com/exceptionless/Foundatio) - 用于构建分布式应用程序的可插入基础块。
* [Microsoft Caching](https://github.com/aspnet/Caching) - 用于内存缓存和分布式缓存的库。
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - 用于.NET语言的高性能通用redis客户端(C#等)。

### 内容管理系统
* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core) - 真棒CMS Core是一个使用ASP.Net Core和ReactJS构建的开源CMS，考虑到模块分离问题并提供最新的技术趋势，如.Net Core，React，Webpack，SASS，后台作业，Message Queue。
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) -  ASP.NET应用程序提供常见的博客功能。
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry) - 开源.NET Core CMS和模块化应用程序框架。代码优先，不引人注目且可扩展。
* [CoreWiki](https://github.com/csharpfritz/CoreWiki) - 我们正在实时编码流中处理的简单ASP.NET核心wiki。
* [Lynicon](https://github.com/jamesej/lyniconanc) - 带有付费模块的O / S ASP.Net Core / .Net核心CMS：JSON内容，适用于各种数据存储，c#内容类型
* [Miniblog](https://github.com/madskristensen/Miniblog.Core) - 一个ASP.NET核心博客引擎。
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS) - 一个开源的ASP.NET Core 2.0 CMS。它目前支持MySQL并计划实现MSSQL，SQLite和PostgreSQL。此外，它是一个模块化CMS支持主题，皮肤，自定义布局，小部件，多语言(En，BN)。
* [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore) - 在模块化和可扩展的应用程序框架之上使用ASP.NET Core构建的开源内容管理系统。
* [Piranha CMS](https://github.com/piranhacms/piranha.core) - 用于ASP.NET核心和实体框架核心的轻量级且不显眼的开源CMS。
* [Platformus](https://github.com/Platformus) - 基于ASP.NET Core 1.0和ExtCore框架的免费，开源和跨平台的CMS。
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) - 用于ASP.NET Core的简单而灵活的内容和博客引擎，可以使用或不使用数据库。
* [Squidex](https://github.com/Squidex/squidex) - 无头CMS，基于MongoDB，CQRS和事件采购。
* [Swastika I / O核心CMS](https://github.com/Swastika-IO/Swastika-IO-Core) - 开源ASP.NET Core 2.x CMS。它目前支持MS SQL并计划在不久的将来实现MSSQL，SQLite。它有许多开箱即用的功能，如多语言支持，主题，模板......
* [Weapsy](https://github.com/Weapsy/Weapsy) - 基于DDD和CQRS的开源ASP.NET核心CMS。它支持开箱即用的MSSQL，MySQL，SQLite和PostgreSQL。
* [Wyam](https://github.com/Wyamio/Wyam) - 模块化静态内容和静态站点生成器。
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core) - 视觉设计，通过拖放构建网站。

###代码分析
* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis) - 针对各种编程语言的静态分析工具，链接和代码质量检查器的精选列表。
*代码分析
  * [DevSkim](https://github.com/Microsoft/DevSkim) - 一组提供安全“linting”功能的IDE插件和规则。
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) - 重构Visual Studio的Essentials。
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) -  .NET编译器平台(“Roslyn”)分析器。
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - 使用.NET编译器平台的StyleCop规则。
*指标
  * [AppMetrics](https://github.com/alhardy/AppMetrics) -  App Metrics是一个开源和跨平台的.NET库，用于记录和报告应用程序中的指标并报告其健康状况。
  * [Audit.NET](https://github.com/thepirat000/Audit.NET) - 审核.NET对象更改的小框架。
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - 强大的.NET库，用于基准测试。
  * [coverlet](https://github.com/tonerdo/coverlet) - 用于.NET Core的跨平台代码覆盖库。
  * [Foundatio](https://github.com/exceptionless/Foundatio#metrics) - 内存，redis，StatsD和Metrics.NET实现的通用接口。
  * [MiniCover](https://github.com/lucaslorentz/minicover) - 用于.NET Core的极简代码覆盖工具。
  * [NBench](https://github.com/petabridge/NBench) -  .NET应用程序的性能基准测试和测试框架。
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics) - 用于在.NET中收集应用程序指标并将其导出到Prometheus的库。
  * [OpenCover](https://github.com/OpenCover/opencover) - 适用于.NET 2及更高版本的代码覆盖工具(仅限WINDOWS OS)，支持包含分支和序列点的32和64个进程。
  * [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor) -  .NET核心应用程序性能监视器。
    * [prometheus-net](https://github.com/prometheus-net/prometheus-net) -  [https://prometheus.io]的.NET客户端(https://prometheus.io)。
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client) -  [Prometheus]的.NET客户端(https://prometheus.io)。
  * [Prometheus.Client.MetricPusher](https://github.com/PrometheusClientNet/Prometheus.Client.MetricPusher) - 将指标推送到Prometheus.Client的PushGateaway。
  * [Prometheus.Client.AspNetCore](https://github.com/PrometheusClientNet/Prometheus.Client.AspNetCore) -  Prometheus.Client的中间件。
  * [Prometheus.Client.MetricServer](https://github.com/PrometheusClientNet/Prometheus.Client.MetricServer) -  Prometheus.Client的MetricServer。
  * [Prometheus.Client.HttpRequestDurations](https://github.com/PrometheusClientNet/Prometheus.Client.HttpRequestDurations) -  Prometheus.Client的请求持续时间的度量标准记录。

###压缩
* [lz4net](https://github.com/MiloszKrajewski/K4os.Compression.LZ4) - 适用于所有.NET平台的超快速压缩算法。
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - 完全管理的C#库，用于处理许多压缩类型和格式。

###编译器
* [Fable](https://github.com/fable-compiler/Fable) -  F#到JavaScript编译器。
* [fparsec](https://github.com/stephan-tolksdorf/fparsec) -  F#和C#的解析器组合库。
* [Mond](https://github.com/Rohansi/Mond) - 一种用C#编写的动态类型脚本语言，带有REPL，调试器和简单的嵌入API。
* [peachpie](https://github.com/peachpiecompiler/peachpie) -  .NET的开源PHP编译器。
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - 用于C#的轻量级，快速且灵活的解析库，由Stack Overflow开发。
* [roslyn](https://github.com/dotnet/roslyn) -  .NET编译器平台(“Roslyn”)为开源C#和Visual Basic编译器提供了丰富的代码分析API。
* [Sprache](https://github.com/sprache/Sprache) -  Tiny C#Monadic Parser Framework。

###密码学
* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net) - 更新原始的bcrypt包。
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) - 用于安全存储密码的BCrypt.NET的.NET核心端口。
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) -  Bouncy Castle Crypto包是加密算法和协议的C#实现。
* [multiformats](https://github.com/multiformats/cs-multihash) - 一个通用的散列库，但是一个用于编码/解码Multihashes的库，它是一个“容器”，用于描述计算摘要的散列算法。
* [nsec](https://github.com/ektrah/nsec) -  NSec是基于libsodium的.NET Core新加密库。

###数据库
* [DBreeze](https://github.com/hhblaze/DBreeze) -  C#.NET MONO NOSQL(嵌入式键值存储)ACID多范例数据库管理系统。
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) - 简单的JSON平面文件数据存储，支持打字和动态数据。
* [LiteDB](https://github.com/mbdavid/LiteDB) -  .NET NoSQL文档存储在一个数据文件中 -  [http://www.litedb.org](http://www.litedb.org )。
* [NoDb](https://github.com/joeaudette/NoDb) -  .NET Core / ASP.NET Core的“无数据库”文件系统存储，因为并非每个项目都需要数据库。
* [marten](https://github.com/JasperFx/marten) -  Postgresql作为.NET应用程序的文档数据库和事件存储[http://jasperfx.github.io/marten](http://jasperfx。 github.io/marten)。
* [yessql](https://github.com/sebastienros/yessql) - 适用于任何RDBMS的.NET文档数据库。

###数据库驱动程序
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - 用于Apache Cassandra的DataStax C#驱动程序。
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) -  Confluent的Apache Kafka .NET客户端。
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) - 一个轻量级，面向文档(NoSQL)，可同步的.NET数据库引擎。
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) -  MongoDB的.NET驱动程序。
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) -  Connector / Net是一个完全托管的MySQL ADO.NET驱动程序。
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) - 用于.NET和.NET Core的异步MySQL连接器。
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - 用于.NET的Neo4j Bolt驱动程序。
  * [Neo4jClient](https://github.com/Readify/Neo4jClient) -  Neo4j的.NET客户端绑定。
* [npgsql](https://github.com/npgsql/npgsql) -  PostgreSQL的.NET数据提供程序。它允许为.NET框架开发的任何程序访问PostgreSQL数据库服务器。它以100％C#代码实现。自9.1以来的Pos​​tgreSQL版本得到官方支持，其他版本可能有效。 [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - 支持Linq的.NET文档数据库。
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - 具有100％ReQL API覆盖率的C#/ .NET RethinkDB驱动程序。
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) -  Tarantool NoSql数据库的.NET客户端。

###数据库工具和实用程序
* [DbUp](https://github.com/DbUp/DbUp) -  .NET库，可帮助您将更改部署到SQL Server数据库。它跟踪已经运行的SQL脚本，并运行使数据库保持最新所需的更改脚本。
* [Evolve](https://github.com/lecaillon/Evolve) - 使用纯SQL脚本的简单数据库迁移工具。受到Flyway的启发。
* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) -  .NET的迁移框架，就像Ruby on Rails Migrations一样。
* [monitor-table-change-with-sqltabledependency](https://github.com/christiandelbianco/monitor-table-change-with-sqltabledependency) - 获取有关记录表更改的SQL Server通知。
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) - 具有OLAP操作和数据透视表数据模型的内存数据立方体。
* [roundhouse](https://github.com/chucknorris/roundhouse) - 使用sql文件和基于源代码控制的版本控制的.NET数据库迁移实用程序。
* [SharpRepository](https://github.com/SharpRepository/SharpRepository) -  SharpRepository是一个用C#编写的通用存储库，它包括对各种关系，文档和对象数据库的支持，包括Entity Framework，RavenDB，MongoDb和Db4o。 SharpRepository还包括Xml和InMemory存储库实现。
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core) - 使用.NET Core跨服务边界进行更改跟踪。
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration) -  Mongo.Migration是为[MongoDB C#驱动程序]设计的(https://github.com/mongodb/mongo-csharp-driver )轻松，即时地迁移您的文档。不再有架构迁移的停机时间。只需编写小而简单的迁移。 [链接](https://github.com/SRoddis/Mongo.Migration)

### 日期和时间
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) -  DateTimeRange，营业日和各种DateTime，DateTimeOffset，TimeSpan扩展方法。
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime) - 允许您编写更清晰的DateTime表达式和操作。部分灵感来自Ruby DateTime Extensions。
* [nodatime](https://github.com/nodatime/nodatime) - 更好的.NET日期和时间API [http://nodatime.org](http://nodatime.org)。

###分布式计算
* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks) - 适用于ASP.NET核心诊断程序包的Enterprise HealthChecks。
   -  [BeatPulse](https://github.com/Xabaril/BeatPulse) - 启用负载均衡器以监控已部署的Web应用程序的状态
* [Foundatio](https://github.com/exceptionless/Foundatio) - 用于构建分布式应用程序的可插入基础块。
* [Rafty](https://github.com/ThreeMammals/Rafty) - 在.NET Core中达成共识。
* [Obvs](https://github.com/christopherread/Obvs) - 一个可观察的微服务总线.NET库，它在简单的基于Rx的接口中包装底层传输。
* [Ocelot](https://github.com/ThreeMammals/Ocelot) - 使用.NET Core创建的API网关。
* [OpenTracing](https://github.com/opentracing/opentracing-csharp) - 供应商中立的API和分布式跟踪工具。
* [Polly](https://github.com/App-vNext/Polly) -  .NET 3.5 / 4.0 / 4.5 / PCL库，允许开发人员表达瞬态异常和故障处理策略，如重试，永远重试，等待和以流利的方式重试或断路器。

###电子商务和支付
* [nopCommerce](https://github.com/nopSolutions/nopCommerce) - 免费的开源电子商务购物车(ASP.NET MVC / ASP.NET核心MVC)，拥有庞大的社区和充满新功能的市场，主题和插件。
* [GrandNode](https://github.com/grandnode/grandnode) - 基于ASP.NET Core 2.1和MongoDB的多平台免费开源电子商务购物车，源自[nopCommerce](https：// github。 COM / nopSolutions / nopCommerce)。
* [PayPal](https://github.com/paypal/PayPal-NET-SDK) - 用于PayPal的RESTful API的.NET SDK。
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - 基于.NET Core构建的超级简单电子商务系统。
* [Stripe](https://github.com/ServiceStack/Stripe) - 用于stripe.com REST API的类型.NET客户端。


###异常
* [Demystifier](https://github.com/benaadams/Ben.Demystifier) - 对堆栈跟踪的高性能理解(使错误日志更高效)。
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 无异常的.NET客户端
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet) -  GlobalExceptionHandlerDotNet允许您将异常处理配置为ASP.NET核心应用程序管道的约定，而不是在每个控制器操作中显式处理它们。

###功能编程
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) -  C#的功能扩展。
* [DynamicData](https://github.com/RolandPheasant/DynamicData) - 基于Rx.NET的反应式集合。
* [echo-process](https://github.com/louthy/echo-process) -  C#的Actor库，其中包含支持Redis持久性的其他模块，以及JS集成。
* [FsCheck](https://github.com/fscheck/FsCheck) -  .NET的随机测试。
* [Giraffe](https://github.com/dustinmoris/Giraffe) - 适用于F#开发人员的本机功能ASP.NET核心Web框架。
* [language-ext](https://github.com/louthy/language-ext) -  C#功能语言扩展和'Erlang like'并发系统。
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) - 用于在C#中进行功能编程的实用程序库。
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions) - 使用Reactive Extensions(RX)轻松地在网络上的任何位置发送消息。传输协议是ZeroMQ。
* [可选](https://github.com/nlkl/Optional) -  C#的强大选项类型。
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) -  [Reactive Streams](http://www.reactive-streams.org/)for .NET。
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - 一个MVVM框架，它与Reactive Extensions for .NET集成，以创建在任何移动或桌面平台上运行的优雅，可测试的用户界面。
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) -  .NET的[Reactive Extensions](http://reactivex.io)。
* [Qactive](https://github.com/RxDave/Qactive) - 反应性可查询可观察框架。 `4.x.x或以上`
* [钠](https://github.com/SodiumFRP/sodium/tree/master/) - 功能反应编程(FRP)库。 `4.x.x或以上`

###图形
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) -  GLFW的.NET绑定。
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - 一个流畅的System.Drawing包装器，用于处理图像文件[http://imageprocessor.org](http://imageprocessor.org)。 `4.5.x或以上`
* [ImageSharp](https://github.com/SixLabors/ImageSharp) - 用于处理用C#编写的图像文件的跨平台库。
* [LibVLCSharp](https://github.com/videolan/libvlcsharp)：libvlc的.NET / Mono绑定，这是为VideoLAN制作的VLC应用程序提供动力的多媒体框架。
* [Magick.NET](https://github.com/dlemstra/Magick.NET) -  ImageMagick的.NET库。
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce) - 适用于.NET的MagicScaler高性能，高质量图像处理管道
* [QRCoder](https://github.com/codebude/QRCoder) - 纯C#开源QR码实现。
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) -  bgfx图形库的C#绑定。
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - 用于支持.NET Core的.NET应用程序的图像处理库。
* [veldrid](https://github.com/mellinoe/veldrid) - 一个用于.NET的低级硬件加速3D图形库。

### GUI
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) - 一个多平台.NET UI框架(以前称为Perspex)。
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - 基于Avalonia的文本编辑器组件，来自[AvalonEdit](https://github.com/icsharpcode/AvalonEdit)
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) - 用于Mono / .NET / .NET Core的跨平台Qml / .NET集成。
* [WinApi](https://github.com/prasannavl/WinApi) - 一个简单，直接，超薄的CLR库，用于高性能Win32 Native Interop，具有自动化，窗口，DirectX，OpenGL和Skia助手。

### IDE
* [Mono](https://github.com/mono/monodevelop) -  MonoDevelop使开发人员能够在Linux，Windows和Mac OS X上快速编写桌面和Web应用程序。它还使开发人员可以轻松移植创建的.NET应用程序使用Visual Studio到Linux和Mac OS X为所有平台维护单一代码库。
* [rider](https://www.jetbrains.com/rider/) - 基于IntelliJ平台和ReSharper的跨平台C#IDE。
* [Omnisharp](http://www.omnisharp.net/) - 开源项目系列，每个项目都有一个目标：在您选择的编辑器中实现出色的.NET体验。
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) -  SharpDevelop是一个免费的集成开发环境(IDE)，适用于Microsoft .NET平台上的C#，VB.NET，Boo，IronPython，IronRuby和F#项目。它(几乎)完全用C#编写，并带有您期望在IDE中使用的功能以及更多功能。
* [Visual Studio Code](https://github.com/Microsoft/vscode) - 一种新型工具，它结合了代码编辑器的简单性和开发人员的核心编辑 - 构建 - 调试周期所需的工具。 Code提供全面的编辑和调试支持，可扩展性模型以及与现有工具的轻量级集成。
* [Visual Studio社区](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - 面向个人开发人员，开源项目，学术研究，教育和小型专业团队。

###国际化
* [Localization](https://github.com/aspnet/Localization) -  ASP.NET Core应用程序的本地化抽象和实现。
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization) - 具有实体框架和内存缓存的.NET Core的数据库资源本地化
* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization) -  .NET应用程序的数据库驱动资源本地化。

### IOC
* [AutoDI](https://github.com/Keboo/AutoDI) - 使用IL编织的超快编译时依赖注入。
* [Autofac](https://github.com/autofac/Autofac) - 上瘾的.NET IoC容器。
* [Castle.Windsor](https://github.com/castleproject/Windsor)Castle Windsor是适用于.NET的最佳，成熟的Inversion of Control容器。
* [DryIoc](https://github.com/dadhi/DryIoc) - 快速，小巧，功能齐全的IoC Container for .NET。
* [Grace](https://github.com/ipjohnson/Grace) -  Grace是一款功能丰富的依赖注入容器，其设计考虑了易用性和性能。
* [Inyector](https://github.com/davidrevoledo/Inyector) -  AspNetCore的依赖注入自动化
* [LightInject](https://github.com/seesharper/LightInject) - 超轻量级IoC容器[http://www.lightinject.net](http://www.lightinject.net)。
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - 简单，灵活，快速的依赖注入库，可促进最佳实践，引导开发人员走向成功之路。
* [Stashbox](https://github.com/z4kn4fein/stashbox) - 基于.NET的解决方案的轻量级，可移植依赖注入框架。
* [StructureMap](https://github.com/structuremap/structuremap) -  .NET的控制工具的依赖注入/反转。

###日志
* [common-logging](https://github.com/net-commons/common-logging) -  .NET的可移植日志记录抽象[http://net-commons.github.io/common-logging](http： //net-commons.github.io/common-logging)。
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - 使用UDP和Redis传输的.NET Core应用程序的Logstash日志记录扩展。
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 无异常的.NET客户端
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) - 一个流畅的日志记录API，可用于在整个应用程序中记录消息。
* [LibLog](https://github.com/damianh/LibLog) - 单个文件，您可以通过nuget复制/粘贴或安装到您的库/框架/应用程序中，以提供日志记录抽象。
* [log4net](https://github.com/apache/logging-log4net) -  log4net是Microsoft®.NET运行时的优秀Apache log4j™框架的一个端口。
* [NLog](https://github.com/NLog/NLog) - 高级.NET，Silverlight和Xamarin日志记录。
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - 用于在ASP.NET Core日志中构建的日志附加程序，以将所有日志发送到Application Insights。
* [serilog](https://github.com/serilog/serilog) - 具有完全结构化事件的简单.NET日志记录。
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore) - 用于ASP.NET Core 2+的Serilog集成。
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) -  Serilog.Exceptions是[Serilog](https://serilog.net/)的附加组件，用于记录异常详细信息和自定义Exception.ToString()中未输出的属性。
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration) - 从Microsoft.Extensions.Configuration读取的Serilog配置提供程序。
* [SEQ](https://getseq.net) -  Seq通过HTTP收集数据，而您的应用程序使用适用于您平台的最佳可用结构化日志API。

###机器学习和数据科学
* [Accord](https://github.com/accord-net/framework) -  .NET的机器学习，计算机视觉，统计和通用科学计算。
* [ML.NET](https://github.com/dotnet/machinelearning) - 跨平台的开源机器学习框架，使.NET开发人员可以访问机器学习[http://dot.net/ml]( http://dot.net/ml)。
* [Spreads](https://github.com/Spreads/Spreads/) - 用于数据流实时和探索性分析的系列和面板。
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) - 适用于.NET语言的TensorFlow API。
* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) - 借助量子力学的思想，从单个例子​​生成itmap和tilemap。
* [SiaNet](https://github.com/SciSharp/SiaNet) - 一个C#深度学习库，人性化，支持CUDA / OpenCL，结构良好，易于扩展

###邮件
* [FluentEmail](https://github.com/lukencode/FluentEmail) -  .NET和.NET Core的一体化电子邮件发件人
* [MailBody](https://github.com/doxakis/MailBody) - 使用流畅的界面(.NET)创建交易电子邮件。
* [MailKit](https://github.com/jstedfast/MailKit) - 用于IMAP，POP3和SMTP的跨平台.NET库。
* [MailMergeLib](https://github.com/axuno/MailMergeLib) -  SMTP邮件客户端库，为文本，内嵌图像和附件提供舒适的邮件合并功能，以及发送邮件的良好吞吐量和容错能力。
* [MimeKit](https://github.com/jstedfast/MimeKit) - 跨平台.NET MIME创建和解析器库，支持S / MIME，PGP，DKIM，TNEF和Unix mbox spool。
* [netDumbster](https://github.com/cmendible/netDumbster) - 用于测试的.Net假SMTP服务器。克隆流行的Dumbster。
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - 将样式表移动到内联样式属性的C#库，以实现与电子邮件客户端的最大兼容性。
* [SendGrid客户端](https://github.com/0xdeafcafe/sendgrid-dotnet) -  SendGrid v3邮件端点的C#库。
* [SmtpServer](https://github.com/cosullivan/SmtpServer) - 用于创建自己的SMTP服务器的库。
* [StrongGrid](https://github.com/Jericho/StrongGrid) -  SendGrid的v3 API客户端。不仅允许您发送电子邮件，还允许您批量导入联系人，管理列表和段，为列表创建自定义字段等。还包括SendGrid Webhooks的解析器。

###数学
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - 用于.NET Core和.NET Framework的可扩展单元转换库。
* [AutoDiff](https://github.com/alexshtf/autodiff) - 一个库，提供快速，准确和自动的数学函数微分(计算导数/梯度)。

###杂项
* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport) - 用于改进P / Invoke-ing本机代码的库。与本机对象交互，就像它们是第一类对象一样。
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - 最终尖括号解析器库。它解析HTML5，MathML，SVG和CSS，以构建基于官方W3C规范的DOM。可与python的beautifulsoup4相媲美。
* [AgileMapper](https://github.com/agileobjects/AgileMapper) -  AgileMapper是一个零配置，高度可配置的对象 - 对象映射器，具有可查看的执行计划。
* [AspNetCore扩展库](https://github.com/sgjsakura/AspNetCore) -  ASP.NET核心扩展库。
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) -  .NET中基于约定的对象 - 对象映射器。
* [Baget](https://github.com/loic-sharma/BaGet) - 轻量级NuGet服务器。
* [Bleak](https://github.com/Akaion/Bleak) -  Windows本机DLL注入库。
* [Bullseye](https://github.com/adamralph/bullseye/) - 用于描述和运行目标及其依赖项的.NET包。
* [Castle.Core](https://github.com/castleproject/Core) -  Castle Core，包括Castle DynamicProxy，Logging Services和DictionaryAdapter [http://www.castleproject.org](http：//www.castleproject .ORG)。
* [Chessie](https://github.com/fsprojects/Chessie) - 面向铁路的.NET编程[http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie )。
* [CliWrap](https://github.com/Tyrrrz/CliWrap) - 命令行界面的包装器。
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet) - 在类中为您的命令行应用程序接口建模。
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - 在C#中实现CommonMark规范，用于将Markdown文档转换为HTML。
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) - 用于为.NET控制台应用程序创建表的Fluent库。
* [CoordinateSharp](https://github.com/Tronald/CoordinateSharp) - 一个可以快速格式化和转换地理坐标以及提供基于位置的太阳和月亮信息(日落，日出，月亮照明等)的库。 )。
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) -  Microsoft ASP.NET服务器端支持和jQuery DataTables的帮助程序。
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) - 用于wkhtmltopdf库的C#.NET核心包装器，它使用Webkit引擎将HTML页面转换为PDF。
* [dotnet-env](https://github.com/tonerdo/dotnet-env) - 用于从.env文件加载环境变量的.NET库。
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob) - 用于.NET / .NETStandard应用程序的快速通配库。优于正则表达式。
* [Dotnet过时](https://github.com/jerriep/dotnet-outdated) - 一个.NET Core全局工具，用于在项目中显示过时的NuGet包。
* [Dotnet Script](https://github.com/filipw/dotnet-script) - 从.NET CLI运行C#脚本。
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve) - 用于.NET Core CLI的简单命令行HTTP服务器。
* [Eighty](https://github.com/benjamin-hodgson/Eighty) - 一个简单的HTML生成库
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) -  Enums.NET是一个高性能类型安全的.NET枚举实用程序库
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) - 快速ExpressionTree编译器委托。
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) -  FTP和FTPS客户端，具有广泛的FTP命令，SSL / TLS连接，散列/校验和等。
* [Fody](https://github.com/Fody/Fody) - 用于编织.net程序集的可扩展工具
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) - 高动态范围(HDR)直方图。
* [httpclient-interception](https://github.com/justeat/httpclient-interception) - 用于拦截服务器端HTTP依赖关系的.NET标准库。
* [Humanizer](https://github.com/Humanizr/Humanizer) -  Humanizer满足您操作和显示字符串，枚举，日期，时间，时间跨度，数字和数量的所有.NET需求。
* [加湿器](https://github.com/jakejscott/Humidifier) - 使用C#编写和维护AWS Cloudformation模板。
* [LibSass主机](https://github.com/Taritsyn/LibSassHost) - 围绕[libSass](http://sass-lang.com/libsass)库的.NET包装器，能够支持虚拟文件系统。
* [markdig](https://github.com/lunet-io/markdig) - 快速，强大，兼容CommonMark，可扩展的Markdown处理器，适用于.NET。
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - 将字符串表达式(公式，方法调用，条件)解析为LINQ表达式树，可以编译为lambda并进行求值。
* [Otp.NET](https://github.com/kspearrin/Otp.NET) - 在C#中实现TOTP RFC 6238和HOTP RFC 4226。
* [pose](https://github.com/tonerdo/pose) - 用委托替换任何.NET方法(包括静态和非虚拟)
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp) -  Puppeteer Sharp是官方Node.JS Puppeteer API的.NET端口。
* [readline](https://github.com/tsolarin/readline) - 用于.NET / .NET Core的纯C#GNU-Readline库。
* [Relinq](https://github.com/re-motion/Relinq) - 使用re-linq，现在比以往更容易创建功能齐全的LINQ提供商。
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) -  Html到Markdown转换器库。
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) -  PdfReport.Core是一个代码优先的报告引擎，它建立在iTextSharp.LGPLv2.Core和EPPlus.Core库之上。
* [Scientist](https://github.com/github/Scientist.net) - 用于仔细重构关键路径的.NET库。它是GitHub的Ruby Scientist库的一个端口。
* [Scrutor](https://github.com/khellang/Scrutor) -  Microsoft.Extensions.DependencyInjection的程序集扫描扩展。
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) -  string.Format的可扩展替代品。
*股票
  * [Trady](https://github.com/lppkarl/Trady) - 用于计算技术指标的便捷图书馆，其目标是成为一个自动交易系统，提供股票数据投放，指标计算，策略构建和自动交易。
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) - 来自System Linq Dynamic功能的.NET Standard(.NET Core)版本。
* [UnitsNet](https://github.com/angularsen/UnitsNet) -  Units.NET为您提供所有常用的度量单位和它们之间的转换。
*验证
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) -  .NET的小型验证库，它使用流畅的接口和lambda表达式来构建验证规则。
  * [Guard](https://github.com/safakgur/guard) - 一个高性能，可扩展的参数验证库。
  * [Valit](https://github.com/valit-stack/Valit) - 对.NET Core的简单验证。代码周围不再有if语句。写一些漂亮而干净的流利验证器吧！
* [warden-stack](https://github.com/warden-stack) - 针对您的应用程序，资源和基础架构的“运行状况检查”。让守望者守在手表上。
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker) -  ASP.NET核心渐进式Web应用程序。
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg) - 用于FFmpeg的.NET标准包装器。它允许在不知道FFmpeg如何工作的情况下处理媒体，并且可以用于将自定义参数传递给来自C#应用程序的FFmpeg。
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) - 用于提取元数据和下载Youtube视频和播放列表的终极库。

### 网络
* [AspNetCore.Proxy](https://github.com/twitchax/AspNetCore.Proxy) -  ASP.NET核心代理变得简单。
* [CurlThin](https://github.com/stil/CurlThin) - 用于C#的轻量级cURL绑定库，支持通过curl_multi接口进行多个同时传输。
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) - 用于.NET Core的HttpListener(NETStandard)。
* [Networker](https://github.com/MarkioE/Networker) - 一个简单易用的.NET TCP和UDP网络库，旨在实现灵活，可扩展和快速。

###Office
* [EPPlus](https://github.com/JanKallman/EPPlus) - 使用.NET创建高级Excel电子表格。
* [npoi](https://github.com/tonyqus/npoi) - 可以读取/写入未安装Microsoft Office的Office格式的.NET库。没有COM +，没有互操作。
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) -  Open XML SDK提供了使用Office Word，Excel和PowerPoint文档的工具。
### ORM
* [Chloe](https://github.com/shuxinqin/Chloe) - 用于.NET的轻量级高性能对象/关系映射(ORM)库。
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - 熟悉以前版本的EF的开发人员经验，包括LINQ，POCO和Code First支持。
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) -  EntityFrameworkCore插入更新删除读取(CRUD)操作的批量批量扩展
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) - 实体框架实用程序|批量操作|批量删除|批量更新|查询缓存|查询过滤器|查询未来|查询包括|审计。
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) - 触发EF的事件。
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx) - 您的EF操作的反应性**热**可观察量。
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) -  PostgreSQL的实体框架核心提供程序。
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) - 轻松获取任何实体的主键(包括复合键)。
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) - 获取实体的原始值的代理对象(对Property(“...”)的类型访问.OriginalValue)。
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties) - 自动神奇地保存指定属性更改的审核历史记录的类。
  * [LINQKit](https://github.com/scottksmith95/LINQKit) -  LINQ to SQL和Entity Framework高级用户的一组免费扩展。
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - 构建在mysql-net / MySqlConnector之上的MySql的实体框架核心提供程序。
* [Dapper](https://github.com/StackExchange/Dapper) -  .NET的简单对象映射器。
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - 提供一个简单的API，可以在使用Dapper时将POCO属性流畅地映射到数据库列。
  * [Dommel](https://github.com/henkmollema/Dommel) -  Dapper的简单CRUD操作。
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) -  DAPper的CRUD。
* [Limebean](https://nick-lucas.github.io/LimeBean/) -  Hybrid-ORM，设计简单易用，不完全隐藏SQL，同时拥有您期望从ORM获得的所有好处。灵感来自RedBeanPHP。
* [LINQ to DB(linq2db)](https://linq2db.github.io/) - 最快的LINQ数据库访问库，在POCO对象和数据库之间提供简单，轻量，快速且类型安全的层，以获取更多信息超过10个具有完全SQL支持的数据库引擎。
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core) -  NHibernate对象关系映射器。
* [NEventStore](https://github.com/NEventStore/NEventStore) - 使用事件源作为存储机制时，用于抽象不同存储实现的持久性库。该库的开发特别关注DDD / CQRS应用程序。
* [NPoco](https://github.com/schotime/NPoco) - 简单的microORM，可将查询结果映射到POCO对象。项目基于Schotime的PetaPoco分公司。
* [NReco.Data](https://github.com/nreco/data) - 用于SQL命令生成，CRUD操作和简单POCO映射的轻量级提供者独立DAL。
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) - 对于你的POCO来说，这是一个很小的ORM东西。
* [querybuilder](https://github.com/sqlkata/querybuilder) -  SqlKata Query Builder是一个用C#编写的功能强大的Sql Query Builder。
* [RepoDb](https://github.com/mikependon/RepoDb) - 用于.NET的动态，轻量，高效且非常快速的混合ORM库。
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - 轻松，简单，快速的基于约定的POCO ORM。
* [SqlFu](https://github.com/sapiens/SqlFu) - 快速且通用的Micro-ORM。
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql) -  SmartSql = MyBatis + Cache(Memory | Redis)+ ZooKeeper + R / W Splitting + Dynamic Repository ....
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) - 针对基于SQL的.NET实现的Stream Store库。

###分析
* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype) - 适用于.NET的轻量级，开源，实时诊断和洞察分析器。 `不稳定的版本`
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - 一个简单但有效的ASP.NET网站迷你探查器。

###查询构建器
* [SqlKata](https://github.com/sqlkata/querybuilder) - 优雅的Sql查询生成器，支持复杂查询，连接，子查询，嵌套条件，供应商引擎目标等等

###队列和消息
* [emitter](https://emitter.io/) - 连接所有设备的免费开源实时消息服务。此发布 - 订阅消息传递API是为了提高速度和安全性而构建的。
* [EventStore](https://github.com/EventStore/EventStore) - 使用JavaScript中的复杂事件处理的开源，功能数据库。
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) - 内存，redis和azure实现的通用接口。
* [MediatR](https://github.com/jbogard/MediatR) -  .NET中简单，无语的中介实现。
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) -  Microsoft.Extensions.DependencyInjection的MediatR扩展。
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) -  .Net的简单中介，用于发送支持管道的命令，发布事件和请求响应。
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - 用于.NET的简单流程中介。
* [MQTTnet](https://github.com/chkr1011/MQTTnet) -  MQTTnet是一个用于基于MQTT的通信的高性能.NET库。
* [netmq](https://github.com/zeromq/netmq) -  ZeroMQ for .NET的100％原生C#实现。
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS) - 用于DDD，CQRS和事件采购的.NET核心库，具有Azure Service Bus集成。 Command和Event存储支持的数据库提供程序包括：DocumentDB，MongoDB，SQL Server，MySQL，PostgreSQL和SQLite。
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) -  RabbitMQ .NET客户端[https://www.rabbitmq.com](https://www.rabbitmq。 COM)。
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - 用于通过RabbitMq进行通信的现代.NET框架。
* [Rebus](https://github.com/rebus-org/Rebus) -  .NET的简单和精简服务总线实现。
* [Restbus](http://restbus.org) -  RabbitMq的消息传递库。
* [Tossit](https://github.com/turgayozgur/tossit) - 简单易用的库，用于分布式作业/工作人员逻辑。内置RabbitMQ实现处理的分布式消息。

###报道
* [FastReport](https://github.com/FastReports/FastReport) -  .NET Core 2.x / .Net Framework 4.x的开源报告生成器。 FastReport可用于MVC，Web API应用程序。

###日程安排和工作
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - 用于在日程安排上运行任务(作业)的轻量级健壮库。
* [Coravel](https://github.com/jamesmh/coravel) -  .Net Core符合Laravel：调度，排队等
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - 具有流畅界面的自动作业调度程序。
* [Gofer.NET](https://github.com/brthor/Gofer.NET) - 用于.NET Core的分布式后台任务/作业的简易C#API。灵感来自芹菜的蟒蛇。
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - 在ASP.NET应用程序中执行“即发即忘”，“延迟”和“重复”任务的简便方法[http://hangfire.io](http：/ /hangfire.io)。
* [LiquidState](https://github.com/prasannavl/LiquidState) - 用于.NET的高效异步和同步状态机。
* [NCrontab](https://github.com/atifaziz/NCrontab) - 用于.NET的Crontab。
* [quartznet](https://github.com/quartznet/quartznet/) -  Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net) 。
* [stateless](https://github.com/dotnet-state-machine/stateless) - 用于在C#代码中创建状态机的简单库。

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net) -  Amazon Web Services(AWS).NET Core SDK组件。每个AWS服务都有自己的NuGet包。
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) -  Azure事件中心的.NET标准客户端库。
*区块链客户
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - 用于Bittrex Web API的C#.Net包装器，包括易于访问和使用的所有功能。
  * [Binance.Net](https://github.com/JKorf/Binance.Net) -  Binance Web API的.Net API包装器。
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient) -  CakeMail API的客户端。允许您发送交易电子邮件，批量电子邮件，管理列表和联系人等。
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - 面向领事的.NET API。
* [csharp-nats](https://github.com/nats-io/csharp-nats) - 用于NATS消息传递系统的C#.NET客户端。
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) -  [Dark Sky API]的.NET标准包装器(https://darksky.net/dev/docs)。
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - 用于Docker API的.NET(C#)客户端库。
* [firebase-admin-dotnet](https://github.com/firebase/firebase-admin-dotnet) -  Firebase Admin .NET SDK
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet) - 适用于.NET的Google Cloud Client Libraries。
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello) - 一个完全面向对象的.Net包装器，用于Trello用C#编写的RESTful API。
* [Microphone](https://github.com/rogeralsing/Microphone) - 使用Consul或ETCD集群的Web Api或NancyFx运行自托管REST服务的轻量级框架。
* [octokit.net](https://github.com/octokit/octokit.net) - 用于.NET的GitHub API客户端库。
* [PreStorm](https://github.com/jshirota/PreStorm) -  ArcGIS Server的并行REST客户端。
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - 用于使用完整SendGrid API的C#客户端库。
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - 与.NET标准兼容的C#客户端与Etsy的优秀[statsd](https://github.com/etsy)接口/ statsd)服务器。
* [tweetinvi](https://github.com/linvi/tweetinvi) - 直观的.NET C#库，用于访问Twitter REST和STREAM API。

###安全
* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers) - 用于向ASP.NET Core应用程序添加安全标头的中间件。
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - 清除HTML以避免XSS攻击。
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - 用于处理JOSE对象的库(JWT，JWA，JWS及相关)。
* [Jwt.Net](https://github.com/jwt-dotnet/jwt) -  Jwt.Net，一个用于.NET的JWT(JSON Web令牌)实现。
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer) - 用于ASP.NET Core的轻量级动态jwt服务器。
* [NWebsec](https://github.com/NWebsec/NWebsec) -  ASP.NET的安全库[http://www.nwebsec.com](http://www.nwebsec.com)。
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - 用于ASP.NET Core的reCAPTCHA 2.0。
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) - 旨在帮助.NET应用程序进行安全审计的Roslyn分析器。
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) -  .NET Core中间件，用于注入Owasp推荐的HTTP标头，以提高安全性。
* [安全](https://github.com/aspnet/Security) - 用于Web应用程序安全性和授权的中间件。
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) - 允许向ASP.NET Core网站添加安全标头的小包。

###搜索
* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp) - 官方Algolia .NET客户端的存储库。
* [自动完成](https://github.com/omerfarukz/autocomplete) - 持久，简单，功能强大且可移植的自动完成库。
* [Elasticsearch.Net＆NEST](https://github.com/elastic/elasticsearch-net) -  NEST和Elasticsearch.NET的存储库，两个官方的弹性搜索.NET客户端。
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) -  Elasticsearch .NET API。
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions) -  IQueryable接口的高级搜索功能，例如Entity Framework查询。
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) - 相似度量标准库，例如从编辑距离(Levenshtein，Gotoh，Jaro等)到其他指标，(例如Soundex，Chapman)
* [SolrExpress](https://github.com/solr-express/solr-express) - 用于Solr的简单轻量级查询.NET库，采用可控，可构建和快速失败的方式。

###序列化
* [bond](https://github.com/Microsoft/bond) - 用于处理模式化数据的跨平台框架。它支持跨语言的序列化和强大的通用机制，可以有效地处理数据。 Bond广泛用于Microsoft的高规模服务。
* [频道](https://github.com/davidfowl/Channels) - 基于推送的.NET Streams。
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - 帮助读写CSV文件的库。
* [Edi.Net](https://github.com/indice-co/EDI.Net) -  EDI Serializer / Deserializer。支持EDIFact，X12和TRADACOMS格式。
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - 用于.NET的扩展Xml序列化程序。
* [Jil](https://github.com/kevin-montrose/Jil) - 基于Sigil构建的快速.NET JSON(De)串行器。
* MessagePack
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli) - 公共语言基础设施的MessagePack实现/ [msgpack.org](http://msgpack.org)。
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - 用于C#的极快MessagePack Serializer(.NET，.NET Core，Unity，Xamarin)。
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - 适用于.NET的流行高性能JSON框架。
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - 用于惯用.NET的协议缓冲库。
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) -  Schema.org对象变成了强类型的C#POCO类，用于.NET。所有类都可以序列化为JSON / JSON-LD和XML，通常用于表示html页面头部的结构化数据。
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) -  JSON，JSV和CSV文本序列化器。
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - 易于使用，易于扩展和高性能的库，用于使用.NET进行CSV解析。
* [Wire](https://github.com/rogeralsing/Wire) -  POCO对象的二进制序列化程序。
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) -  .NET
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - 用于.NET的快速二进制(de)序列化程序。
* [Utf8Json](https://github.com/neuecc/Utf8Json) - 用于C#(.NET，.NET Core，Unity，Xamarin)的绝对最快和零分配JSON序列化器。
* [YAXLib](https://github.com/sinairv/YAXLib) - 用于.NET Framework和.NET Core的XML序列化库。非常灵活和强大。

###模板引擎
* [dotliquid](https://github.com/dotliquid/dotliquid) - TobiasLütke的Liquid模板语言的.NET端口。
* [fluid](https://github.com/sebastienros/fluid) - 开源.NET模板引擎，尽可能接近Liquid模板语言。
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml) - 用于读/写xaml文件的可移植.NET库。
* [Razor](https://github.com/aspnet/Razor) - 用于MVC Web应用程序视图页面的CSHTML文件的分析器和代码生成器。
* [RazorLight](https://github.com/toddams/RazorLight) - 基于Microsoft针对.NET Core的Razor解析引擎的模板引擎。

###测试
* [Bogus](https://github.com/bchavez/Bogus) - 简单而健全的C#假数据生成器。基于并从着名的faker.js移植。
* [CoreBDD](https://github.com/stevenknox/CoreBDD) -  xUnit.net的BDD框架
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) -  .NET的简易模拟库。
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) - 一组.NET扩展方法，允许您更自然地指定TDD或BDD样式测试的预期结果。
* [GenFu](https://github.com/MisterJames/GenFu) - 可用于生成实际测试数据的库。
* [LightBDD](https://github.com/LightBDD/LightBDD) -  BDD框架允许创建易于阅读和维护的测试。
* [mockhttp](https://github.com/richardszalay/mockhttp) - 为Microsoft的HttpClient库测试图层。
* [moq.netcore](https://github.com/Moq/moq4) - 最受欢迎且最友好的.NET模拟框架。
* [MSpec](https://github.com/machine/machine.specifications) - 用于编写BDD样式测试的流行测试框架。
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - 流畅的测试
  ASP.NET Core MVC的框架。
* [Netling](https://github.com/hallatore/Netling) - 加载测试客户端，以便轻松进行Web测试。
* [NSpec](https://github.com/nspec/NSpec) - 针对C#的战斗强化测试框架，受Mocha和RSpec的启发。
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) -  .NET模拟框架的友好替代品。
* [nunit](https://github.com/nunit/dotnet-test-nunit) - 面向.NET Core的NUnit测试运行器。
* [shouldly ](https://github.com/shouldly/shouldly) - 应该测试.NET  - 断言*应该*的方式！ [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore) - 用于.NET的实用BDD解决方案。它使用Gherkin规范语言并集成到Visual Studio中。
* [Storyteller ](https://github.com/storyteller/Storyteller) -  .NET的可执行规范[http://storyteller.github.io](http://storyteller.github.io)。
* [Stubbery](https://markvincze.github.io/Stubbery/) - 一个用于在.NET中创建和运行Api存根的简单库。
* [Testavior](https://github.com/geeklearningio/Testavior) -  Testavior是一个轻量级解决方案，可帮助您开发ASP.NET Core的行为测试。
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - 最简单的BDD框架！
* [xBehave.net](https://github.com/xbehave/xbehave.net) - 一个xUnit.net扩展，用于描述使用自然语言的测试。 [http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit) - 一个免费的，开源的，以社区为中心的.NET Framework单元测试工具。

###工具
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) -  .NET Core和.NET Framework的命令行解析和实用程序。
* [docfx](https://github.com/dotnet/docfx) - 用于构建和发布.NET项目API文档的工具[http://dotnet.github.io/docfx](http://dotnet.github) .IO / docfx)
* [dotnetfiddle](https://dotnetfiddle.net) -  .NET沙箱，供开发人员快速尝试代码和共享代码片段。
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools) -  .NET Core命令行(dotnet CLI)的工具扩展列表。
  * [LibMan CLI](https://github.com/aspnet/LibraryManager) - 用于Web应用程序的客户端内容管理器。
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) -  .Net Core和.Net Framework 4.5+的可组合CLI(命令行)参数解析器。
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server) - 用于原型设计或作为CRUD后端的假REST API。无需定义类型，使用动态类型。数据存储在单个JSON文件中。具有身份验证，WebSocket通知，异步长时间运行操作，错误/延迟的随机生成以及实验性GraphQL支持。
* [gitignore.io](https://github.com/joeblau/gitignore.io) - 为您的项目创建有用的.gitignore文件[https://www.gitignore.io](https://www.gitignore。 IO)。
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - 扫描上传的packages.config文件或GitHub存储库，并确定nuget包是否针对.NET Standard [https://icanhasdot.net](https：/ /icanhasdot.net)。
* [json2csharp](http://json2csharp.com) - 从JSON生成C#类。
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) - 适用于Windows的简单ACME客户端。
* [mRemoteNG](https://github.com/mRemoteNG/mRemoteNG) - 下一代mRemote，开源，标签，多协议，远程连接管理器
* [NJsonSchema](https://github.com/RSuter/NJsonSchema) -  NJsonSchema是一个.NET库，用于读取，生成和验证JSON Schema draft v4 + schemas。
* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper) - 自动更新.NET项目中的nuget包。
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - 使用GUI创建，更新和部署Nuget软件包。
* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer) - 为一组给定的git存储库或文件夹可视化所有nuget包及其相应的版本。
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - 使用适用于GitHub的OctoLinker浏览器扩展，有效地浏览`projects.json`文件。
* [posh-dotnet](https://github.com/bergmeister/posh-dotnet) -  [dotnet CLI]的“PowerShell”标签完成(https://github.com/dotnet/cli)。
* [Rin](https://github.com/mayuki/Rin) -  ASP.NET Core的请求/响应Inspector中间件。像Glimpse。
* [scoop](https://github.com/lukesampson/scoop) -  Windows的命令行安装程序。
* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer) - 使用Serilog日志库对基于Roslyn的代码进行分析。检查常见错误和使用问题。
* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) -  #ziplib是一个完全用C#编写的适用于.NET平台的Zip，GZip，Tar和BZip2库。
* [ShareX](https://github.com/ShareX/ShareX) - 免费的开源程序，可让您捕捉或记录屏幕的任何区域，只需按一下键即可共享。它还允许将图像，文本或其他类型的文件上传到80多个支持的目的地，您可以从中选择。 [https://getsharex.com](https://getsharex.com)
* [SharpLab](https://github.com/ashmind/SharpLab) -  .NET代码游乐场，显示代码编译的中间步骤和结果。 [https://sharplab.io](https://sharplab.io)
* [sourcelink](https://github.com/dotnet/sourcelink) -  SourceLink是一个语言和源代码控制不可知系统，用于为二进制文件提供一流的源代码调试体验。
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) - 用于.NET和.NET Core的简单站点地图生成器
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) - 用于.NET和.NET Core的简单RSS Feed生成器
* [SmartCode](https://github.com/Ahoo-Wang/SmartCode) -  SmartCode = IDataSource  - > IBuildTask  - > IOutput => Build Everything !!! (包括[代码生成器])

### Web框架
* WebAssembly
  * [Blazor](https://github.com/SteveSanderson/Blazor) - 通过WebAssembly在浏览器中运行.NET的UI框架。
    * [Blazor Redux](https://github.com/torhovland/blazor-redux) - 将Redux状态存储与Blazor连接。
  * [Ooui](https://github.com/praeclarum/Ooui) - 小型跨平台UI库，可将本机UI开发的简单性带入Web。
* [ReactJS.NET](https://github.com/reactjs/React.NET) - 用于JSX编译和React组件的服务器端呈现的.NET库。
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) -  .NET应用程序的可预测状态容器。灵感来自[https://github.com/reactjs/redux](https://github.com/reactjs/redux)。

### WebSocket
* [Fleck](https://github.com/statianzo/Fleck) -  Fleck是C#中的WebSocket服务器实现。 Fleck不需要继承，容器或其他引用。
* [SignalR Server](https://github.com/aspnet/signalr) -  Web应用程序的实时Web功能，包括服务器端推送。
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - 轻量级，跨平台和可扩展的套接字服务器应用程序框架。
* [WampSharp](https://github.com/Code-Sharp/WampSharp) -  [Web应用程序消息传递协议]的C#实现(http://wamp-proto.org/) - 提供远程消息传递模式的协议过程通过WebSockets调用和发布/预订。
* [websocket-manager](https://github.com/radu-matei/websocket-manager) -  ASP .NET Core的实时库。

### Windows服务
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - 直接从.NET Core设置并运行Windows服务。
* [Topshelf](https://github.com/Topshelf/Topshelf) - 使用.NET构建Windows服务的简易服务托管框架。

###工作流程
* [CoreWF](https://github.com/dmetzgar/corewf/) -  Windows Workflow Foundation(WF)到.NET Core的端口。
* [workflow-core](https://github.com/danielgerlag/workflow-core) -  .NET Standard的轻量级工作流引擎。
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET) - 在应用程序中添加工作流程的组件。
* [Wexflow](https://github.com/aelassas/Wexflow) - 高性能，可扩展，模块化和跨平台的工作流引擎。

##路线图
* [ASP.NET核心开发人员路线图](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap) - 成为2019年ASP.NET核心开发人员的路线图。

##入门套件
* [Arch](https://github.com/Arch) -  .NET Core库的集合，由嵌入.NET Core中所有新东西的软件架构师创建。
  * [AutoHistory](https://github.com/Arch/AutoHistory) -  Microsoft.EntityFrameworkCore的插件，支持自动记录数据更改历史记录。
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) - 跨平台 - 用于SEO，Bootstrap，i18n国际化(ngx-translate)，Webpack的服务器端渲染，TypeScript，带Karma的单元测试，WebAPI REST设置，SignalR，Swagger文档等等！
* [ASP.NET核心入门套件](https://github.com/kriasoft/aspnet-starter-kit) - 基于.NET Core，Kestrel，后端GraphQL和Babel，Webpack，React进行Web开发的意见样板和Redux在前端。这个样板有C#和F#两种口味。
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) -  Yeoman生成器，用于构建全新的ASP.NET Core单页面应用程序，该应用程序使用Angular 2 / React / React与Redux / Knockout / Aurelia在客户端上。
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) -  Asp.NETCore 2.0 Vue 2(ES6)SPA入门套件，包含路由，Vuex等等！
* [bitwarden-core](https://github.com/bitwarden/core) - 核心基础设施后端(API，数据库等)[https://bitwarden.com](https://bitwarden.com)。
* [dotNetify](https://github.com/dsuryd/dotNetify) - 构建实时HTML5 / C#.NET Web应用程序的简单，轻量级但功能强大的方法。
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) - 用于ASP.NET Core的yo生成器。
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) - 在后端使用ASP.NET Core API分层架构和基于JWT的身份验证的Vue启动应用程序模板
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - 使用ASP.NET Core 1构建同构React应用程序的起点，利用现有技术。
* [saaskit](https://github.com/saaskit/saaskit) - 用于构建SaaS应用程序的开发人员工具包。

##示例项目
*微服务和服务网格
  * [coolstore-microservices](https://github.com/vietnam-devs/coolstore-microservices) - 一个基于Kubernetes的多语言微服务应用程序，带有Istio服务网格
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground) - 带有Vagrant，Consul，Docker和ASP.NET Core的分布式服务游乐场。
  * [DNC-DShop](https://github.com/devmentors) - 分布式.NET核心项目和免费课程。 (DDD，CQRS，RabbitMQ，MongoDB，Redis，监控，记录，CI，CD)
  * [dotnetcore-microservices-poc](https://github.com/asc-lab/dotnetcore-microservices-poc) - 使用.NET Core(EF Core，MediatR，Marten，Eureka)在微服务架构中制作的简化保险销售系统，Ocelot，RabbitMQ，Polly，ElasticSearch，Dapper)与博客文章系列。
  * [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - 基于微服务架构和容器的参考应用程序。
  * [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication) -  Akka.NET参考架构 -  CQRS + Sharding +内存中复制
  * [magazine-website](https://github.com/thangchung/magazine-website) - 应用DDD，CQRS，微服务，异步编程的杂志网站(使用.NET Core，ASP.NET Core，EF Core)。
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnetcore) - 我的微服务书中的代码示例 -  [https://manning.com/books/microservices-in-net -core](https://manning.com/books/microservices-in-net-core)
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - 实时交易平台演示，展示在整个应用程序堆栈中应用的反应式编程原理。
*巨石
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) -  West Wind Album Viewer ASP.NET 5示例。
  * [allReady](https://github.com/HTBox/allReady) - 开源解决方案，重点是提高准备活动的意识，效率和影响，因为它们由当地社区的人道主义和灾害响应组织提供。 [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) -  ASP.NET核心MVC Geo Elasticsearch Swashbuckle Swagger。
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - 使用ASP.NET Core实现服务发现模式的示例。
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) - 一个研讨会，用于浏览ASP.NET核心授权中的各个新部分
  * [来自微软的AppsSharing360应用程序套件](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)发布了12月Connect 2016大会，一套简洁的套装企业用户和消费者(自行车骑手)的互通应用程序：[移动应用程序](https://github.com/Microsoft/BikeSharing360_MobileApps)，[后端服务](https://github.com/Microsoft/BikeSharing360_BackendServices) ，[网站](https://github.com/Microsoft/BikeSharing360_Websites)，[单一容器应用](https://github.com/Microsoft/BikeSharing360_SingleContainer)，[多容器应用](https://github.com / Microsoft / BikeSharing360_MultiContainer)，[Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp)，
 [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps)。
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe) -  ASP.NET核心多租户Web应用程序基础。
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) - 一个开源小型本地开发活动的开源网站。
  * [DotNetClub](https://github.com/scheshan/DotNetClub) - 用ASP.NET Core编写的小型俱乐部。
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - 具有单一部署模型的分层应用程序架构。
  * [Entropy](https://github.com/aspnet/Entropy) - 用于新功能和想法的混乱实验游乐场 - 请在此处查看针对各个功能的小型和简单样本。
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - 具有DDD，CQRS和事件源的完整ASP.NET Core 2.0应用程序。
  * [GenVue](https://github.com/herbat73/GenVue) - 一个可托管的Web应用程序，允许机密用户上传和共享基于Vue.js，Vuetifyjs和NetCore WebAPI堆栈构建的私有文件
  * [guide-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - 如何管理多租户应用中的用户身份Microsoft Azure，使用Azure Active Directory进行身份验证。
  * [JustA.ML](https://github.com/mustakimali/JustA.ML) - 一个Web应用程序，允许您在使用ASP.NET Core 2.0编写的设备之间共享文件/ URL /文本。开源，现场[https://justa.ml](https://justa.ml)
  * [MegaMine](https://github.com/Nootus/MegaMine) - 开源挖掘解决方案，帮助矿工提取黄金，石英，花岗岩等。此解决方案使用ASP.NET Core和AngularJS利用多个轻量级组件构建以微服务的方式。
  * [minicompiler](https://github.com/ealsur/minicompiler) - 缩小，捆绑和编译样本。
  * [MusicStore](https://github.com/aspnet/MusicStore) - 使用MVC和Entity Framework的示例MusicStore应用程序。
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) - 带有.NET Core Preview 2的NLayerAppV3 N层架构。
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders) -  Northwind Traders是使用ASP.NET Core和Entity Framework Core构建的示例应用程序。
  * [Orchard Core  - 模块化和多租户应用](https://github.com/OrchardCMS/OrchardCore.Samples) - 使用Orchard Core Framework创建模块化和多租户应用程序。
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - 使用ASP.NET Core，Angular 2和TypeScript的跨平台单页应用程序[http://wp.me/p3mRWu-11L ](http://wp.me/p3mRWu-11L)。
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - 每日更新的ASP.NET核心功能和设施的微量示例。
  * [.NET核心CQRS REST API示例](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - 使用Clean Architecture的原始SQL和DDD的.NET Core REST API CQRS实现。
  * [StarWars](https://github.com/JacekKosciesza/StarWars) - 使用GraphQL for .NET，ASP.NET Core，Entity Framework Core的GraphQL“星球大战”示例。
 
##文章
* 基础知识
  * [具有相关视频的综合BikeSharing360演示应用程序套件的Microsoft架构概述](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [将.NET Framework库移植到.NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [在执行一行代码之前CLR执行的68件事](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-单线路的，你的代码/)
  * .NET核心和Nodejs在[这里]的比较(https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/ )，[这里](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2)和[这里](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [了解ASP.NET核心初始化](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [为什么要加入.NET Core和ASP.NET Core列车](https://codingblast.com/why-you-should-join-asp-net-core/)
*云开发
  * [在.NET Core中配置AWS开发工具包](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [使用C#和AWS Amazon Gateway Api / Lambda的无服务器架构](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-sharp-and-AWS-Amazo)
  * [在Amazon Web Services(AWS)Lambda中使用C#和.NET Core](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
*配置和部署
  * [.NET项目结构](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [将Travis CI构建添加到.NET Core应用程序](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0  - 配置ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy，nginx，Angular 2，ASP.NET Core，Redis和Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json到MSBuild转换指南](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [使用Appveyor和NuGet发布.NET项目](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [ASP.NET核心中的新配置模型](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
*实体框架核心
  * [.NET核心数据访问](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [关于EF Core的一个很好的例子](https://github.com/rowanmiller/Demo-EFCore)
  * [使用EF Core连接到Postgres](http://en.otomatikmuhendis.com/2017/05/05/connect-to-postgres-with-ef-core/)
*神奇
  * [Orchard Core作为NuGet包入门](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [如何在ASP.NET Core中将HTML导出为PDF](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [使用ASP.NET Core进行Vue.js服务器端渲染](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
*安全
  * [.NET持续交付微服务](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0身份验证和授权系统揭秘](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [ASP.NET授权实验室的演练](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [ASP.NET核心中的身份验证](https://stormpath.com/blog/authentication-asp-net-core)
*测试
  * [使用.NET Core的Selenium](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)
 -  [InfoQ .NET文章](https://www.infoq.com/dotnet) -  InfoQ网站上最好的.NET文章集

##书籍
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET核心应用程序开发：在四个sprints中构建应用程序(开发人员参考)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-net-core-in-action)
* [ASP.NET Core 1.0高性能](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [使用ASP.NET核心构建微服务：在云中开发，测试和部署跨平台服务](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp / 1491961732)
* [C#6和.NET Core 1.0：现代跨平台开发](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [.NET Core中的依赖注入，第2版](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [使用微服务，ASP.NET核心和实体框架核心探索.NET核心 - 免费电子书采样器](https://www.manning.com/books/exploring-dot-net-core)
* [.NET Core中的微服务：使用C#，Nancy框架和OWIN中间件](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [专业C#6和.NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [小ASP.NET核心](https://www.recaffeinate.co/book)

## 备忘单
* [dotnet cli Cheat Sheet](http://en.otomatikmuhendis.com/2018/07/02/cheat-sheet-for-dotnet-cli/)

##视频
* [Channel9](https://channel9.msdn.com) -  MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) -  YouTube
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)

##播客
* [.NET Rocks](https://www.dotnetrocks.com)
* [合并冲突](http://www.mergeconflict.fm/)
* [.NET的声音](http://thesoundof.net/?q=.NET+Core)

##社区
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [/r/CoolGithubProjects](http://www.reddit.com/r/coolgithubprojects)
* [ASP.NET](https://forums.asp.net)
* [Channel9](https://channel9.msdn.com)
* [令人敬畏的.NET开源和社区资源](https://discoverdot.net)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* [BuiltWithDot.Net](https://builtwithdot.net)
* 堆栈溢出
  * [.NET核心](https://stackoverflow.com/questions/tagged/.net-core)
  * [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  * [ASP.NET核心](https://stackoverflow.com/questions/tagged/asp.net-core)
  * [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  * [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  * [实体框架核心](https://stackoverflow.com/questions/tagged/entity-framework-core)
* [今天在GitHub上展示.NET存储库](https://github.com/trending?l=csharp)
