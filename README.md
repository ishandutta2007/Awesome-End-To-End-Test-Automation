# Awesome-End-To-End-Test-Automation

# 顶级端到端测试自动化平台生态系统

**精选 SaaS 产品与开源 GitHub 项目列表**
*聚焦于无代码/低代码测试创作、AI 自愈、云并行执行与 CI/CD 集成*
**最后更新：2026 年 9 月**

本仓库追踪**端到端测试自动化**领域的知名 **SaaS 平台**与**开源项目**。这些工具帮助 QA 团队、开发者和产品团队以更低的维护成本创建、执行和维护可靠的端到端测试，覆盖 Web、移动端和 API。

**示例**包括 Cypress Cloud、Playwright Workspaces、Testim、mabl、Autify、testRigor、Functionize、Reflect、QA Wolf 和 ACCELQ（该领域的领先者）。

**开源重点**：与众多企业软件类别不同，端到端测试自动化的**核心执行引擎**（如 Playwright、Cypress、Selenium）本身即是开源的。真正的商业价值集中在**云执行基础设施**、**AI 自愈/低代码创作层**和**分析仪表盘**。因此，本列表的开源部分重点收录**可自托管的执行框架**、**开源测试编排工具**和**AI 测试辅助库**——适合希望完全掌控测试基础设施、避免按测试运行量付费的工程团队。

欢迎贡献！提交 PR 以添加/更新条目。保持描述事实性，并链接到官方网站。

## 目录

- [SaaS/托管平台](#saas托管平台)
- [开源 GitHub 项目](#开源github项目)
- [如何贡献](#如何贡献)
- [免责声明](#免责声明)

## SaaS/托管平台

- **[Cypress Cloud](https://www.cypress.io/cloud)**
  Cypress 应用的商业配套服务。提供 Test Replay 交互式调试、Flake Detection 不稳定性检测、Smart Orchestration（测试并行化与失败优先排序）、以及 Jira/GitHub/Slack 集成。**注意**：Cypress Cloud 数据**无法自托管**。Starter 计划免费但限 500 测试结果/月；Enterprise 计划提供 30 天全功能试用，含 50,000 测试结果。

- **[Playwright Workspaces](https://learn.microsoft.com/en-us/azure/app-testing/playwright-workspaces/)**
  微软 Azure 提供的**完全托管云浏览器平台**，用于大规模运行 Playwright 测试。支持并行远程浏览器执行、跨 OS/浏览器一致性测试（Windows、Linux、Android Chrome 模拟、移动 Safari）、以及**远程 MCP 服务器**供 AI 代理驱动浏览器。测试代码保留在客户端，浏览器交互在云端执行，无需修改现有 Playwright 测试。

- **[Testim](https://www.testim.io/)**
  基于 AI 的功能与端到端 UI 测试自动化平台。核心差异化是**AI 驱动的 Smart Locators**：分析整个 DOM 为元素分配唯一标识分数，当属性变化时智能定位器继续识别元素，大幅减少维护。提供录制器、可视化编辑器、可复用步骤组，以及导出为 JavaScript 代码的灵活性。客户包括 Microsoft、Salesforce、Wix、JFrog。

- **[mabl](https://www.mabl.com/)**
  统一低代码测试自动化平台，覆盖 **UI、API、可访问性、性能、视觉、邮件和 PDF 测试**于单一系统。AI 驱动自愈（auto-heal）和智能等待（Intelligent Wait）减少浏览器测试维护。支持并行执行、临时环境测试、Jira 集成和 Slack/Teams 通知。14 天免费试用提供全功能访问。

- **[Autify](https://autify.com/)**
  AI 驱动的测试自动化工具，强调**非技术用户友好性**。用户通过可视化方式创建测试而非编写长脚本，降低自动化门槛。Autify Genesis（2026）进一步将 AI 应用于**测试设计与规格生成**：连接 GitHub 仓库和上传文件作为上下文，AI 助手可基于规格和实现细节回答问题、草拟规格和生成测试用例。

- **[testRigor](https://testrigor.com/)**
  **生成式 AI 原生**测试自动化平台，核心是**纯英文自由格式测试创作**。粘贴用户故事、Jira 工单或手动测试用例，testRigor 生成可运行的端到端测试。自愈基于生成式 AI 评估脚本是否需要变更。支持 Web、移动端（iOS/Android 原生+混合）、桌面（Windows）、API、邮件、SMS/电话、2FA。可 SaaS 或本地部署，HIPAA/SOC 2 Type II/ISO 27001/21 CFR Part 11 就绪。

- **[Functionize](https://www.functionize.com/)**
  企业级**自主工作流自动化**平台，以“数字工人”（EAI Agents）为核心理念。三种创建工作流方式：**录制**（Architect Chrome 插件收集数百万数据点）、**自然语言提示**（用英文描述流程）、**AI 观察学习**（通过 JavaScriptTag 观察真实用户行为自主识别模式）。自愈通过深度学习神经网络持续学习每次执行的数据点，当系统变更时自主更新模型。支持跨浏览器、移动 Web、视觉验证、数据驱动场景。用户评价强调实施容易、低代码、CI/CD 集成无缝。

- **[Reflect](https://reflect.run/)**
  基于云的测试自动化平台，支持**无代码测试创作**和跨浏览器测试。提供可视化回归测试、测试记录和云执行基础设施。

- **[QA Wolf](https://www.qawolf.com/)**
  **全托管**端到端测试服务，最大差异化是**测试代码由客户完全拥有**（标准 Playwright 和 Appium 代码）。AI 映射应用生成覆盖大纲，用户用自然语言描述流程，QA Wolf 生成测试。提供**完整服务选项**：QA Wolf 团队编写、维护、运行测试并调查失败。支持 Web（Canvas/WebGL、拖拽、文件上传下载、PDF 验证、多用户工作流、跨域流程、浏览器扩展、Electron）以及 iOS/Android 原生应用的真实设备测试。SOC 2 Type II 合规，HIPAA 就绪。

- **[ACCELQ](https://www.accelq.com/)**
  AI 原生云平台，核心理念是 **Application Universe**：应用的结构化蓝图，捕获页面、组件、导航路径、API 调用和端到端业务流程。自动化是**场景驱动而非脚本驱动**，支持自然语言意图、可视化交互建模和 API/数据库验证。**Autopilot** 从单一业务场景自动生成多个测试变体、数据驱动排列组合和覆盖率对齐。基于**代理架构**：Discovery Agent 建立应用理解，Automation Agent 生成可执行逻辑，Analyzer Agent 评估执行模式并识别覆盖缺口。

## 开源 GitHub 项目

- **[Playwright](https://github.com/microsoft/playwright)**
  微软开源的跨浏览器端到端测试框架。单一 API 支持 Chromium、Firefox、WebKit，覆盖 Windows、Linux、macOS 和移动模拟。自动等待、网络拦截、追踪查看器和代码生成器。**这是绝大多数商业平台（Playwright Workspaces、QA Wolf）的底层引擎**。Apache-2.0。

- **[Cypress](https://github.com/cypress-io/cypress)**
  开源端到端和组件测试框架。在浏览器中运行，提供实时重载、时间旅行调试和自动等待。Cypress App 本身开源且免费；Cypress Cloud 是可选商业配套。MIT。

- **[Selenium](https://github.com/SeleniumHQ/selenium)**
  浏览器自动化的原始标准。WebDriver 协议被所有主流浏览器原生支持。语言绑定覆盖 Java、Python、C#、Ruby、JavaScript、Kotlin。生态庞大但维护成本较高（需自行处理等待、定位器等）。Apache-2.0。

- **[Testcontainers](https://github.com/testcontainers/testcontainers-java)**
  提供一次性 Docker 容器实例用于测试的库。端到端测试中用于启动真实数据库、消息队列或依赖服务，避免 mock 与真实行为的偏差。支持 Java、Python、Go、Node.js、.NET、Rust。MIT。

- **[Dagger](https://github.com/dagger/dagger)**
  可编程 CI/CD 引擎，将流水线步骤容器化。端到端测试可编排为 Dagger pipeline，在本地和 CI 间保持一致执行环境，解决“在我机器上能跑”的问题。Apache-2.0。

- **[Gauge](https://github.com/getgauge/gauge)**
  轻量级跨平台测试自动化框架，强调**Markdown 规格作为测试**。测试用 Markdown 编写（业务可读），步骤实现用 Java、JavaScript、Python、Ruby 或 C#。适合 BDD 风格团队。Apache-2.0。

- **[Robot Framework](https://github.com/robotframework/robotframework)**
  基于 Python 的通用测试自动化框架，使用表格化语法。SeleniumLibrary 和 AppiumLibrary 提供 Web/移动端支持。丰富的库生态和报告系统。Apache-2.0。

- **[Karate](https://github.com/karatelabs/karate)**
  将 API 测试、Web UI 测试、性能测试和 mock 统一在一个框架中。DSL 用 Gherkin 风格编写，无需 Java 知识。内置并行执行、JUnit 集成和 HTML 报告。MIT。

- **[CodeceptJS](https://github.com/codeceptjs/CodeceptJS)**
  场景驱动的端到端测试框架，**用自然语言编写测试**（`I.amOnPage('/'); I.click('Login')`）。支持 Playwright、WebDriver、Puppeteer 和 Appium 作为底层驱动。适合希望测试代码更接近业务语言的团队。MIT。

- **[Puppeteer](https://github.com/puppeteer/puppeteer)**
  Chrome/Chromium 的 Node.js 控制库。提供高层 API 通过 DevTools Protocol 控制无头浏览器。常用于快速端到端脚本、截图和 PDF 生成。Apache-2.0。

- **[Appium](https://github.com/appium/appium)**
  移动端自动化的事实标准。WebDriver 协议扩展至 iOS、Android 原生/混合/移动 Web 应用。支持真实设备和模拟器。**QA Wolf 的移动端测试即基于 Appium**。Apache-2.0。

### 其他强开源选项

- **AI 测试辅助**：**Midscene.js**（自然语言 UI 操作，开源）、**AutoPlaywright**（自然语言驱动的 Playwright 测试生成）。
- **视觉回归**：**BackstopJS**（开源视觉回归测试）、**reg-suit**（视觉回归测试编排）。
- **测试报告**：**Allure**（多语言测试报告框架，支持 Playwright/Cypress/JUnit）、**ReportPortal**（AI 驱动的测试分析平台，开源）。
- **API 测试**：**Bruno**（开源 API 客户端，可编程测试）、**Hurl**（文本格式 HTTP 测试工具）。

**构建自定义系统的框架**：以 **Playwright** 或 **Cypress** 为执行引擎，**Testcontainers** 管理测试依赖，**Dagger** 编排 CI/CD 流水线，**Allure** 或 **ReportPortal** 生成报告。添加 **Appium** 扩展移动端覆盖，**Midscene.js** 引入自然语言测试创作能力。

## 如何贡献

1. Fork 仓库。
2. 在 `README.md` 中添加/编辑条目（遵循现有格式）。
3. 包含：名称、链接、1-2 句描述，以及是 SaaS 还是开源。
4. 提交 PR 并附简短说明。

如果你觉得这个仓库有用，请点星！

## 免责声明

- 这是一个**社区精选**列表——并非详尽无遗，也不构成认可。
- 端到端测试平台可能处理敏感应用数据和凭证；确保凭证存储安全并遵循最小权限原则。
- **开源现实**：执行引擎（Playwright、Cypress、Selenium）的开源程度极高且成熟。AI 自愈和低代码创作层的开源替代方案仍在早期阶段，多数生产级团队要么投资自建，要么采用商业平台。自托管意味着你自己承担基础设施维护、并行执行编排和结果分析的全部工程成本。

---

**为 QA 工程师、SDET、测试架构师和 DevOps 团队打造。**
让端到端测试自动化更开放、更可靠、更易维护。
