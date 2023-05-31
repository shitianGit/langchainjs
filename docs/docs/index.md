欢迎来到LangChain
=============

LangChain是一个基于语言模型开发应用程序的框架。我们相信，最强大和有差异化的应用程序不仅会通过API调用语言模型，还将：

*   _具备数据意识_: 将语言模型连接到其他数据源
*   _具有代理能力_: 允许语言模型与其环境进行交互

LangChain框架是根据上述原则设计的。

入门指南[​](#getting-started "Direct link to Getting Started")
----------------------------------------------------------

请查看下面的指南，了解如何使用LangChain创建语言模型应用程序。

*   [快速入门，使用LLMs](/docs/getting-started/guide-llm)
*   [快速入门，使用聊天模型](/docs/getting-started/guide-chat)

组件[​](#components "Direct link to Components")
----------------------------------------------

LangChain提供支持的几个主要模块。对于每个模块，我们都提供了一些示例来开始并熟悉一些概念。每个示例链接到所使用模块的API文档。

这些模块按照复杂度递增的顺序排列：

*   [模式](/docs/modules/schema/): 这包括整个库中使用的接口和基类。
    
*   [模型](/docs/modules/models/)：这包括与各种LLM、聊天模型和嵌入式模型的集成。
    
*   [提示](/docs/modules/prompts/)：这包括提示模板和与输出解析器和示例选择器等提示相关的功能
    
*   [索引](/docs/modules/indexes/)：这包括用于处理您自己的数据并使其准备好与语言模型交互的模式和功能（包括文档加载器、向量存储、文本分割器和检索器）。
    
*   [内存](/docs/modules/memory/)：内存是在链/代理的调用之间保持状态的概念。LangChain提供了一个标准接口来管理内存，一组内存实现以及使用内存的链/代理示例。
    
*   [链路](/docs/modules/chains/)：链不仅限于单个LLM调用，而是一系列调用（无论是对LLM还是其他实用程序）。LangChain为链提供了标准接口、许多与其他工具的集成以及常见应用的端到端链。
    
*   [代理人](/docs/modules/agents/)：代理人涉及使用LLM做出决策，选择该动作，看到观察结果，并重复此过程直至完成。LangChain为代理人提供了标准接口、可供选择的代理人以及端到端代理人示例。
    

API 参考文档[​](#api-reference "Direct link to API Reference")
----------------------------------------------------------

[在这里](/docs/api/)您可以找到LangChain中所有模块的API参考，以及所有导出类和函数的完整文档。

生产[​](#production "Direct link to Production")
----------------------------------------------

当您从原型设计进入生产阶段时，我们正在开发资源来帮助您实现这一目标。其中包括：

*   [部署](/docs/production/deployment)：有关如何将您的应用程序部署到生产环境的资源。
*   [事件/回调](/docs/production/callbacks)：有关LangChain模块公开的事件的资源。
*   [跟踪](/docs/production/tracing)：有关如何使用跟踪来记录和调试应用程序的资源。

其他资源[​](#additional-resources "Direct link to Additional Resources")
--------------------------------------------------------------------

我们认为以下资源可能对您开发应用程序有所帮助！

*   [LangChainHub](https://github.com/hwchase17/langchain-hub): LangChainHub是一个分享和探索其他提示、链条和代理的地方。
    
*   [Discord聊天室](https://discord.gg/6adMQxSpJS)：加入我们的Discord，讨论所有关于LangChain的事情！
    
*   [生产支持](https://forms.gle/57d8AmXBYp8PP8tZA)：当您将LangChains投入生产时，我们很乐意提供更全面的支持。请填写此表格，我们将设置一个专用的支持Slack频道。
    
