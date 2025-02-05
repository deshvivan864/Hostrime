# Cursor 常见问题深度解析

## 为什么 Cursor 不是完全免费的？
大型语言模型的运行成本非常高。为了在不影响服务质量的前提下可持续地发展 Cursor，我们需要承担相应的运营成本。

## 付费计划中的 Preminum models 是什么？
GPT-4、GPT-4o 和 Claude3.5 Sonnet 被视为高级模型。这些模型每月提供 500 次快速使用和无限次慢速使用。而 Claude3.5 Haiku 每次请求仅占用 1/3 的 Premim 请求。

## 什么是 fast 和 slow use？
我们的后端优先处理 Premium 模型的快速使用。在 Pro 计划中，一旦达到快速使用限制，用户仍可使用高级模型，但在高负载时，请求可能会被排队处理。

## 什么是隐私模式（Privacy mode）？
在此模式下，你的代码将不会被存储在机器以外的任何地方，也不会被用于训练。否则，Cursor 可能会收集使用数据（包括提示词、代码片段、编辑器操作等）以改进产品。

## 是否所有的 Cursor 功能都可以使用 API key？
一些重要功能，如 Tab 键、从 chat 中使用 Apply 和 Composer 功能，无法通过 API key 使用。

## Cursor Tab 是什么？
Cursor Tab 是 Cursor 原生的自动补全功能，基于单独的模型进行上下文预测。

## Cursor 中生成的代码，版权是谁的？
无论使用哪个版本的 Cursor，所有生成的代码都属于用户，可以随意使用，包括商业用途。

## Rules for AI 的作用是什么？
这是一个自定义指令，每次使用 Chat 功能时都会添加到提示词中。你也可以将指令添加到 `.cursorrules` 文件中，以便为每个项目设置不同的指令。

## Cursor 和 VS Code 的区别是什么？
Cursor 是在 VS Code 基础上二次开发的独立应用，拥有独特的 UI 和 AI 功能。Cursor Tab、Ctrl+K 等功能无法直接作为插件存在，因此 Cursor 被设计为独立应用。

## Cursor 官方教程的地址？
官方教程地址如下：[https://docs.cursor.com/get-started/migrate-from-vscode](https://bbtdd.com/WildCard)

## 官网教程都是英文的，如何翻译成中文？
可以使用沉浸式翻译插件：[https://immersivetranslate.com/zh-Hans/](https://bbtdd.com/WildCard)，支持手机端和浏览器插件，按需安装。

如果有其他问题，欢迎在评论区留言。如果这篇文章对你有帮助，欢迎点赞、收藏和转发！

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)