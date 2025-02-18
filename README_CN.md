[![](./images/describe-en.png)](https://dify.ai)

<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README_CN.md">简体中文</a> |
  <a href="./README_JA.md">日本語</a> |
  <a href="./README_ES.md">Español</a>
</p>

#### [![](https://dcbadge.vercel.app/api/server/FngNHpbcY7?style=flat&theme=clean&compact=true)](https://discord.gg/FngNHpbcY7) [![](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/dify_ai)  

Dify 是一个 LLM 应用开发平台，已经有超过 10 万个应用基于 Dify.AI 构建。它融合了 Backend as Service 和 LLMOps 的理念，涵盖了构建生成式 AI 原生应用所需的核心技术栈，包括一个内置 RAG 引擎。使用 Dify，你可以基于任何模型自部署类似 Assistants API 和 GPTs 的能力。

![](./images/demo.png)

## 为什么选择Dify

Dify 具有模型中立性，相较 LangChain 等硬编码开发库 Dify 是一个完整的、工程化的技术栈，而相较于 OpenAI 的 Assistants API 你可以完全将服务部署在本地。

| 功能 | Dify.AI | Assistants API | LangChain |
| --- | --- | --- | --- |
| 编程方式 | 面向 API | 面向 API | 面向 Python 代码 |
| 生态策略 | 开源 | 封闭且商用 | 开源 |
| RAG 引擎 | 支持 | 支持 | 不支持 |
| Prompt IDE | 包含 | 包含 | 没有 |
| 支持的 LLMs | 丰富 | 仅 GPT | 丰富 |
| 本地部署 | 支持 | 不支持 | 不适用 |


## 特点

![](./images/models.png)

**1. LLM支持**：与 OpenAI 的 GPT 系列模型集成,或者与开源的 Llama2 系列模型集成。事实上，Dify支持主流的商业模型和开源模型(本地部署或基于 MaaS)。

**2. Prompt IDE**：和团队一起在 Dify 协作，通过可视化的 Prompt 和应用编排工具开发 AI 应用。 支持无缝切换多种大型语言模型。

**3. RAG引擎**：包括各种基于全文索引或向量数据库嵌入的 RAG 能力，允许直接上传 PDF、TXT 等各种文本格式。

**4. Agent**：基于函数调用的 Agent框架，允许用户自定义配置，所见即所得。Dify 提供了基本的插件能力，如谷歌搜索。

**5. 持续运营**：监控和分析应用日志和性能，使用生产数据持续改进 Prompt、数据集或模型。

## 在开始之前

- [网站](https://dify.ai)
- [文档](https://docs.dify.ai)
- [部署文档](https://docs.dify.ai/getting-started/install-self-hosted)
- [常见问题](https://docs.dify.ai/getting-started/faq)

## 安装社区版

### 系统要求

在安装 Dify 之前，请确保您的机器满足以下最低系统要求：

- CPU >= 2 Core
- RAM >= 4GB

### 快速启动

启动 Dify 服务器的最简单方法是运行我们的 [docker-compose.yml](docker/docker-compose.yaml) 文件。在运行安装命令之前，请确保您的机器上安装了 [Docker](https://docs.docker.com/get-docker/) 和 [Docker Compose](https://docs.docker.com/compose/install/)：

```bash
cd docker
docker compose up -d
```

运行后，可以在浏览器上访问 [http://localhost/install](http://localhost/install) 进入 Dify 控制台并开始初始化安装操作。

### Helm Chart

非常感谢 @BorisPolonsky 为我们提供了一个 [Helm Chart](https://helm.sh/) 版本，可以在 Kubernetes 上部署 Dify。
您可以前往 https://github.com/BorisPolonsky/dify-helm 来获取部署信息。

### 配置

如果您需要自定义配置，请参考我们的 [docker-compose.yml](docker/docker-compose.yaml) 文件中的注释，并手动设置环境配置。更改后，请再次运行 `docker-compose up -d`。您可以在我们的[文档](https://docs.dify.ai/getting-started/install-self-hosted/environments)中查看所有环境变量的完整列表。

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=langgenius/dify&type=Date)](https://star-history.com/#langgenius/dify&Date)


## 社区与支持

我们欢迎您为 Dify 做出贡献，以帮助改善 Dify。包括：提交代码、问题、新想法，或分享您基于 Dify 创建的有趣且有用的 AI 应用程序。同时，我们也欢迎您在不同的活动、会议和社交媒体上分享 Dify。

- [GitHub Issues](https://github.com/langgenius/dify/issues)。👉：使用 Dify.AI 时遇到的错误和问题，请参阅[贡献指南](CONTRIBUTING.md)。
- [电子邮件支持](mailto:hello@dify.ai?subject=[GitHub]Questions%20About%20Dify)。👉：关于使用 Dify.AI 的问题。
- [Discord](https://discord.gg/FngNHpbcY7)。👉：分享您的应用程序并与社区交流。
- [Twitter](https://twitter.com/dify_ai)。👉：分享您的应用程序并与社区交流。
- [商业许可](mailto:business@dify.ai?subject=[GitHub]Business%20License%20Inquiry)。👉：有关商业用途许可 Dify.AI 的商业咨询。
## 安全问题

为了保护您的隐私，请避免在 GitHub 上发布安全问题。发送问题至 security@dify.ai，我们将为您做更细致的解答。

## License

本仓库遵循 [Dify Open Source License](LICENSE) 开源协议。
