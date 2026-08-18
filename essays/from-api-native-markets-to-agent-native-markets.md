---
layout: essay
title: "From API-Native Markets to Agent-Native Markets"
title_zh: "从 API-Native 市场到 Agent-Native 市场"
description: "Why AI may become the new interface layer of finance, sitting between human intent and market infrastructure."
description_zh: "为什么 AI 可能成为金融的新一层交互界面，位于人的意图与市场基础设施之间。"
date: 2026-08-18
author: "Seon Zhu"
series: "Agent-Native Markets"
chapter: 1
language: "en, zh-CN"
tags:
  - AI
  - Finance
  - Markets
  - Trading
  - Market Infrastructure
  - Agents
  - Interactive Brokers
---

Last month, I wrote about how a crypto-native trading firm might build a global markets trading platform.

That essay focused mostly on infrastructure: market access, data, execution, clearing, financing and the institutional architecture required to move beyond crypto.

Over the past few weeks, however, I have been using something that made me think about the problem from a completely different level.

I connected ChatGPT with my Interactive Brokers account.

At first, it felt like a useful productivity upgrade.

Instead of opening several screens, checking positions manually, pulling market data, comparing instruments and then translating a conclusion into an order, I could simply start with a question.

What is my current exposure to a particular theme?

Which positions are contributing most to portfolio risk?

How could I express a view using equities, futures or options?

What happens to the portfolio under a different market scenario?

And once the analysis is complete, the system can generate trade instructions that are passed back to Interactive Brokers for review and submission.

This may look like a small product feature.

I think it points to something much larger.

> **The next major abstraction layer in finance may not be another trading platform. It may be an AI agent sitting between human intent and market infrastructure.**

---

## The Evolution of Market Interfaces

Financial markets have always been shaped by their interfaces.

At one point, trading was primarily mediated through people.

You called a broker.

A human translated your intention into an order.

Technology gradually changed that relationship.

The interface evolved roughly like this:

> **Phone → GUI → API → Agent**

Each transition did more than improve convenience.

It changed who could interact with the market, how quickly they could do so, and what level of complexity they could manage.

### The Phone Era

The broker was effectively the interface.

The investor expressed intent in natural language, but another human had to interpret and execute it.

Access to information and execution was highly mediated.

### The GUI Era

Electronic trading terminals moved more control directly to the user.

Bloomberg terminals, broker workstations and later mobile applications transformed market access into a software experience.

But users now had to learn the language of the software.

Tickers.

Order types.

Filters.

Screens.

Menus.

Option chains.

Risk metrics.

The interface became more powerful, but the human had to adapt to the machine.

### The API Era

APIs created another abstraction layer.

Instead of a person clicking buttons, software could communicate directly with exchanges, brokers and market-data systems.

This was transformative for quantitative trading.

Once market access became programmable, firms could automate:

* data collection
* signal generation
* order placement
* risk checks
* portfolio rebalancing
* execution logic

Crypto accelerated this model dramatically.

Many crypto exchanges were API-native from the beginning. For sophisticated trading firms, the API effectively became the primary interface while the graphical interface became secondary.

But APIs introduced their own barrier.

To use them effectively, you needed software engineers, infrastructure and clearly specified logic.

The machine could act directly on the market, but only after humans had translated their intentions into code.

AI agents may now change that relationship again.

---

## From APIs to Intent

The most interesting thing about the current generation of AI systems is not that they can generate text.

It is that they are increasingly able to use tools.

That creates a fundamentally different interface.

With an API, the user or developer specifies:

> Get endpoint X.  
> Pass parameter Y.  
> Parse field Z.  
> Apply rule A.  
> Send order B.

With an agent, the user increasingly begins with:

> Here is what I am trying to achieve.

The model then translates intent into a sequence of tools and actions.

That difference sounds subtle.

It is not.

It moves the abstraction layer one level higher.

Instead of requiring humans to understand the structure of the software, the software begins to understand the structure of human intent.

---

## The Real Opportunity Is Not AI Stock Picking

Much of the discussion around AI and financial markets still focuses on a relatively narrow question:

> Can an LLM predict stock prices?

Perhaps models will eventually become better at generating alpha.

Perhaps they will not.

But I increasingly think this is not the most important near-term question.

The much more immediate change is:

> **AI can compress the entire investment workflow.**

Consider a fairly ordinary investment question:

> I think AI infrastructure spending will remain strong, but I am worried my portfolio is already too exposed to the same factor. How can I express the view without simply buying more semiconductor stocks?

Traditionally, answering that properly could involve several separate systems.

You might need to:

1. inspect your existing portfolio;
2. calculate sector and factor exposure;
3. research related companies;
4. compare valuations;
5. analyse futures or options;
6. model alternative positions;
7. estimate portfolio impact;
8. open a broker interface;
9. construct the trade;
10. monitor the resulting exposure.

That process might involve a broker terminal, Bloomberg, Excel, Python, research platforms and multiple browser tabs.

An AI agent connected to those systems can potentially compress much of that workflow into one conversational environment.

The important change is therefore not necessarily:

**better prediction.**

It may initially be:

* faster research
* faster synthesis
* lower decision latency
* easier scenario analysis
* easier trade construction
* easier portfolio interrogation
* easier access to complex financial tools

The first major impact of AI on trading may therefore not be autonomous alpha generation.

It may be the compression of the entire investment workflow.

---

## Finance Is Becoming Intent-Driven

I increasingly think the next generation of financial software can be understood in three layers.

### Layer 1: Intent

The human expresses a goal.

For example:

> Reduce my exposure to US technology without materially reducing expected portfolio return.

Or:

> Find a capital-efficient way to hedge a 10% drawdown in the Nasdaq over the next three months.

Or:

> Show me where my portfolio is implicitly short volatility.

These are not software commands.

They are intentions.

### Layer 2: Intelligence

The AI agent interprets the intention.

It can potentially:

* inspect the portfolio
* retrieve market data
* search research
* calculate exposures
* run scenarios
* compare instruments
* construct candidate trades
* explain trade-offs
* interact with external financial tools

### Layer 3: Infrastructure

The underlying financial system still performs the actual work.

This includes:

* market-data providers
* brokers
* exchanges
* OMS and EMS systems
* clearing firms
* custodians
* banks
* prime brokers

The architecture begins to look like:

> **Human Intent → AI Agent → Financial Infrastructure → Market**

This may become the defining interface architecture of the next generation of finance.

---

## The Broker May Become Invisible

This leads to a more provocative possibility.

What happens to a broker when users stop spending most of their time inside the broker’s own interface?

Today, brokers compete partly through their front ends.

They build:

* desktop terminals
* mobile applications
* screeners
* charting systems
* research interfaces
* portfolio tools
* order-entry workflows

But if an investor increasingly interacts with markets through an AI agent, many of those functions can move outside the broker.

The relationship could become:

> **Investor → AI Agent → Broker Infrastructure → Market**

The broker does not disappear.

In many ways, its underlying infrastructure becomes even more important.

But its visible interface may matter less.

The competitive advantage shifts toward things such as:

* breadth of market access
* execution quality
* API openness
* MCP and agent connectivity
* financing
* margin efficiency
* securities lending
* custody
* reliability
* permissioning
* data accessibility

The future broker may increasingly resemble an operating system for financial agents.

The front end becomes replaceable.

The infrastructure underneath becomes strategic.

---

## Institutional Intelligence, Consumer-Grade Interaction

There is another consequence that may be even larger.

AI dramatically reduces the interface cost of financial complexity.

Professional investors routinely work with concepts such as:

* duration
* convexity
* option Greeks
* implied volatility
* factor exposure
* portfolio beta
* correlation
* margin
* futures curves
* financing costs
* scenario analysis

The mathematics behind these concepts does not become easier.

But interacting with them can.

Instead of learning where a particular function sits inside a terminal, a user can increasingly ask:

> Why did my portfolio lose money today even though the S&P 500 was flat?

Or:

> How much of my risk actually comes from long-duration growth exposure?

Or:

> Explain the trade-off between hedging this position using puts, futures and reducing the underlying.

The agent can translate institutional financial language into conversational language while still using institutional tools underneath.

That combination could be extremely powerful:

> **Institutional-grade analytical capability with consumer-grade interaction.**

This does not mean every retail investor suddenly becomes a hedge fund manager.

Access to tools is not the same as investment skill.

But the historical separation between professional and consumer financial interfaces may narrow considerably.

---

## The More Powerful the Agent, the More Important the Controls

There is an uncomfortable side to all of this.

The easier financial systems become to operate, the easier it may also become to take risks that users do not fully understand.

A traditional interface exposes friction.

If you construct an options trade manually, you normally see:

* expiry
* strike
* quantity
* price
* contract multiplier
* buying-power effect

That friction is annoying.

But some of it is useful.

Now imagine telling an agent:

> Hedge my downside while minimising carry.

The system could potentially construct a sophisticated options strategy in seconds.

Operational friction has disappeared.

But economic complexity has not.

In fact, it may have become less visible.

This creates a new design problem:

> **When the interface becomes simpler, risk must become more explicit.**

The future of agentic finance therefore cannot simply be autonomous execution.

It will require a strong control architecture around the agent.

That likely includes:

* explicit permissions
* position and notional limits
* human confirmation for material actions
* explainability
* audit trails
* scenario analysis
* tool-level access controls
* authentication independent from the model
* separation between recommendation and execution

One durable architecture may therefore be:

> **Machine intelligence, human authority.**

The machine can dramatically expand the human’s analytical and operational bandwidth.

But authority over capital remains explicitly controlled.

---

## From Trading Software to Financial Agents

If this direction continues, financial software itself may start to look very different.

Today, software products are largely defined by interfaces.

A broker has a trading interface.

A data provider has a data interface.

A research platform has a research interface.

A risk system has a risk interface.

In an agent-native environment, these products increasingly become collections of capabilities that an AI system can call when required.

The agent becomes the interface.

The financial products become tools.

This is structurally similar to what APIs did for software, but at a higher level of abstraction.

APIs made applications programmable.

Agents may make applications composable through intent.

A single financial agent could eventually coordinate:

* broker accounts
* market-data systems
* research services
* banking relationships
* prediction markets
* tax records
* portfolio analytics
* private investments
* corporate treasury

The user may not think in terms of which software product they are using.

They may simply think in terms of what they want their capital to do.

---

## What This Means for Financial Institutions

If this thesis is directionally correct, financial institutions should probably begin asking a different set of questions.

Not only:

> How do we add AI to our existing product?

But:

> How does our institution become usable by AI agents?

That means thinking about infrastructure differently.

### Brokers

Can an authorised agent securely retrieve portfolio information, market data, margin information and order status?

Can it construct transactions without compromising final user authority?

### Exchanges

Can agents understand instrument metadata, trading rules, market structure and market state programmatically?

### Market-Data Providers

Can agents retrieve data together with sufficient context, licensing and provenance to reason about it correctly?

### Asset Managers

Can investment processes become partially agentic without losing accountability?

### Banks

Can treasury, FX, liquidity and financing workflows be exposed through controlled machine interfaces?

### Regulators

How should responsibility be allocated when an AI system participates meaningfully in financial decisions?

These will increasingly become infrastructure questions rather than chatbot questions.

---

## From Crypto-Native to AI-Native

This is also where I see an important connection with crypto.

Crypto-native markets were among the first large financial ecosystems where APIs were not secondary interfaces.

They were core infrastructure.

That encouraged a generation of trading firms to think in terms of programmable markets.

AI introduces the next abstraction.

The market is no longer merely programmable.

It becomes increasingly interpretable and operable through natural language.

That creates an interesting progression:

> **Electronic Markets → API-Native Markets → Agent-Native Markets**

Crypto-native trading firms may have an advantage in this transition.

They are already accustomed to:

* programmable execution
* fragmented venues
* continuous markets
* automated risk
* rapid infrastructure integration
* machine-driven workflows

Traditional institutions, meanwhile, bring something equally important:

* regulated market access
* custody
* clearing
* financing
* trust
* deep pools of assets

The next financial system may emerge from the combination of these two worlds, with AI sitting above them as the new interaction layer.

---

## The Bigger Shift

When new technologies enter finance, we tend to focus first on the asset.

Crypto created new assets.

Tokenisation brings existing assets onto new rails.

AI is different.

Its largest impact may not initially be a new asset at all.

It may change the way humans interact with **every existing asset**.

Stocks.

Bonds.

Futures.

Options.

Currencies.

Crypto.

Private markets.

Prediction markets.

The interface itself becomes intelligent.

And when the interface becomes intelligent, complexity that was previously hidden behind specialised software, technical skills and institutional workflows becomes increasingly accessible through conversation.

That does not eliminate the need for expertise.

If anything, it may increase the value of judgment.

But the division of labour changes.

Humans spend less time operating financial software.

Machines spend less time waiting for perfectly structured commands.

The interface between the two becomes intent.

---

## Conclusion

When I first connected ChatGPT to my brokerage account, I mostly expected a faster way to research and manage trades.

What surprised me was how quickly the traditional trading interface started to feel less important.

I was no longer thinking:

> Which screen do I need to open?

I was thinking:

> What do I actually want to know or accomplish?

That difference may sound small.

I think it is the beginning of something much larger.

For decades, humans learned how to operate financial software.

The next generation of financial software may learn how to operate on human intent.

The transition from phone to GUI changed market access.

The transition from GUI to API changed quantitative trading.

The transition from API to agent may change the entire relationship between investors and financial infrastructure.

The next financial revolution may therefore not come from a new asset class.

> **It may come from a new way of interacting with every asset class.**

And if that is true, the financial institutions that matter most in the next era may not be those with the best interface.

They may be the ones whose infrastructure is most useful to intelligent agents.

---

# 从 API-Native 市场到 Agent-Native 市场

## 为什么 AI 可能成为金融的新一层交互界面

上个月，我写了一篇文章，讨论一家 Crypto-native 交易机构如何搭建全球市场交易平台。

上一篇主要讨论的是基础设施：市场准入、行情、执行、清算、融资，以及一家 Crypto 交易机构走向全球传统市场时所需要建立的机构化体系。

但过去几周，我开始使用一种新的交易方式，它让我从完全不同的层面重新思考这个问题。

我把 ChatGPT 和 Interactive Brokers 账户连接了起来。

最初，我只是觉得这是一种效率提升。

过去，我需要打开多个页面，手动检查持仓、读取行情、比较不同工具，然后再把判断转化成交易指令。现在，我可以直接从一个问题开始。

我目前对某个主题到底有多少敞口？

哪些持仓对组合风险贡献最大？

如果我要表达某个观点，应该用股票、期货还是期权？

如果市场进入另一个情景，我的组合会发生什么？

分析完成之后，系统还可以生成交易指令，并传回 Interactive Brokers，由用户最终确认和提交。

这看起来像一个很小的产品功能。

但我认为，它指向的是一场更大的变化。

> **金融的下一层核心抽象，可能不是另一个交易平台，而是一个位于“人的意图”和“市场基础设施”之间的 AI Agent。**

---

## 市场交互界面的演化

金融市场一直都被它的交互方式所塑造。

曾经，交易主要通过“人”来完成。

你打电话给经纪人。

另一个人把你的意图翻译成订单。

技术逐步改变了这种关系。

交互界面的演化大致可以概括为：

> **电话 → 图形界面 → API → Agent**

每一次变化都不仅仅是让交易变得更方便。

它还改变了谁可以进入市场、可以多快完成操作，以及一个人能够处理多大程度的复杂性。

### 电话时代

经纪人本身就是交易界面。

投资者用自然语言表达意图，但必须由另一个人来理解并执行。

市场信息和交易执行高度依赖中介。

### 图形界面时代

电子交易终端把更多控制权直接交给了用户。

Bloomberg 终端、券商工作站，以及后来的移动应用，把市场准入变成了一种软件体验。

但代价是，用户必须开始学习软件的语言。

Ticker。

订单类型。

筛选器。

页面。

菜单。

期权链。

风险指标。

界面变得更强大，但人开始需要适应机器。

### API 时代

API 又创造了下一层抽象。

不再需要人点击按钮，软件可以直接与交易所、券商和行情系统通信。

这彻底改变了量化交易。

一旦市场准入变得可编程，交易机构就可以自动化：

* 数据采集
* 信号生成
* 订单发送
* 风险检查
* 组合再平衡
* 执行逻辑

Crypto 极大加速了这一模式。

很多 Crypto 交易所从一开始就是 API-native 的。对于成熟交易机构而言，API 才是主要界面，而图形界面反而变成了辅助工具。

但 API 也带来了新的门槛。

要真正有效使用 API，你需要工程师、基础设施，以及被明确编码的逻辑。

机器可以直接作用于市场，但前提是人先把自己的意图翻译成代码。

AI Agent 可能正在再次改变这种关系。

---

## 从 API 到 Intent

这一代 AI 最有意思的地方，并不是它们会生成文字。

而是它们越来越能够调用工具。

这会带来一种根本不同的交互方式。

使用 API 时，用户或开发者通常会明确指定：

> 调用接口 X。  
> 传入参数 Y。  
> 解析字段 Z。  
> 执行规则 A。  
> 发送订单 B。

而使用 Agent 时，用户越来越可能从一句话开始：

> 这是我想实现的目标。

然后模型将“意图”翻译成一系列工具调用与行动。

这个变化听起来很细微。

其实并不是。

它把整个抽象层又向上抬了一层。

过去，是人理解软件的结构。

现在，软件开始理解人的意图。

---

## 真正的机会不是 AI 选股

今天围绕 AI 与金融市场的大量讨论，仍然集中在一个相对狭窄的问题上：

> 大模型到底能不能预测股票？

也许未来模型会越来越擅长生成 Alpha。

也许不会。

但我越来越认为，这并不是短期内最重要的问题。

更现实、也更大的变化可能是：

> **AI 可以压缩整个投资工作流。**

假设有一个很普通的投资问题：

> 我认为 AI 基础设施资本开支仍然会保持强劲，但我担心我的组合已经对同一个因子暴露过多。除了继续买半导体股票，我还可以怎样表达这个观点？

过去，要认真回答这个问题，往往需要多个系统。

你可能需要：

1. 检查现有持仓；
2. 计算行业和因子敞口；
3. 研究相关公司；
4. 比较估值；
5. 分析期货和期权；
6. 建模不同交易方案；
7. 评估对组合的影响；
8. 打开券商交易界面；
9. 构建交易；
10. 监控新形成的风险敞口。

这个过程可能需要券商终端、Bloomberg、Excel、Python、研究平台，以及大量浏览器标签页。

如果 AI Agent 与这些系统打通，那么整个工作流中的很大一部分，都可以被压缩进一个对话环境。

所以真正重要的变化未必是：

**更好的预测。**

它最先改变的可能是：

* 更快研究
* 更快信息整合
* 更低决策延迟
* 更容易进行情景分析
* 更容易构建交易
* 更容易理解自己的组合
* 更容易使用复杂金融工具

因此，AI 对交易最先产生的重大影响，可能并不是自主 Alpha 生成。

而是整个投资工作流的压缩。

---

## 金融正在变成 Intent-Driven

我越来越倾向于用三个层次来理解下一代金融软件。

### 第一层：Intent

人表达目标。

例如：

> 降低我对美国科技股的风险暴露，但不要明显牺牲预期收益。

或者：

> 找一个资本效率较高的方法，对冲未来三个月 Nasdaq 下跌 10% 的风险。

或者：

> 告诉我，我的组合实际上在哪些地方隐含做空了波动率。

这些不是软件命令。

它们是意图。

### 第二层：Intelligence

AI Agent 负责理解这个意图。

它可以进一步：

* 检查组合
* 获取行情
* 搜索研究资料
* 计算风险敞口
* 进行情景测试
* 比较不同金融工具
* 设计备选交易
* 解释不同方案的权衡
* 调用外部金融工具

### 第三层：Infrastructure

真正完成交易和资金处理的，依然是底层金融基础设施。

包括：

* 行情供应商
* 券商
* 交易所
* OMS 与 EMS
* 清算机构
* 托管机构
* 银行
* Prime Broker

整个架构开始变成：

> **人的意图 → AI Agent → 金融基础设施 → 市场**

这可能会成为下一代金融最具代表性的交互架构。

---

## 券商可能逐渐“隐形”

这也引出了一个更激进的可能性。

如果用户越来越少停留在券商自己的界面里，会发生什么？

今天，券商的竞争力有一部分来自前端。

它们会建设：

* 桌面终端
* 手机应用
* 筛选器
* 图表系统
* 研究界面
* 组合工具
* 下单流程

但如果投资者越来越多通过 AI Agent 与市场交互，那么这些功能中的很多都可以移出券商本身。

未来的关系可能变成：

> **投资者 → AI Agent → 券商基础设施 → 市场**

券商不会消失。

恰恰相反，它的底层基础设施会变得更加重要。

只是它“可见的前端”可能会变得没那么重要。

竞争优势可能开始转向：

* 市场覆盖范围
* 执行质量
* API 开放性
* MCP 与 Agent 接入能力
* 融资能力
* 保证金效率
* 融券能力
* 托管
* 稳定性
* 权限管理
* 数据可访问性

未来的券商，可能越来越像 AI 金融 Agent 的操作系统。

前端界面变得可替代。

而底层基础设施变得更具战略价值。

---

## 机构级智能，消费者级交互

还有一个影响可能更大。

AI 大幅降低了金融复杂性的“交互成本”。

专业投资者每天都在使用这些概念：

* 久期
* 凸性
* 期权 Greeks
* 隐含波动率
* 因子暴露
* 组合 Beta
* 相关性
* 保证金
* 期货曲线
* 融资成本
* 情景分析

这些概念背后的数学并不会因此变简单。

但与它们交互，可以变得简单。

用户不再需要学习某个功能位于终端里的哪个菜单，而是可以直接问：

> 为什么今天 S&P 500 没怎么跌，我的组合却亏了钱？

或者：

> 我的风险里，到底有多少来自长期成长股暴露？

或者：

> 解释一下，使用 Put、期货，或者直接降低现货仓位，这三种对冲方式之间的权衡。

Agent 可以把机构金融语言翻译成自然语言，同时底层仍然使用机构级工具。

这种组合可能非常强大：

> **机构级分析能力，消费者级交互体验。**

这不意味着每一个普通投资者都会突然变成对冲基金经理。

获得工具，不等于获得投资能力。

但专业金融界面与普通消费者界面之间长期存在的巨大鸿沟，可能会快速缩小。

---

## Agent 越强，控制体系越重要

但这一切也有一个令人不安的另一面。

金融系统越容易操作，人们也越容易承担自己并不完全理解的风险。

传统界面会暴露出一定的操作摩擦。

如果你手动构建一个期权交易，通常会看到：

* 到期日
* 行权价
* 数量
* 价格
* 合约乘数
* 对购买力和保证金的影响

这种摩擦很烦。

但其中一部分其实是有价值的。

现在想象你直接对 Agent 说：

> 在尽量降低持有成本的情况下帮我对冲下行风险。

系统可能几秒内就构建出一套复杂期权组合。

操作摩擦消失了。

但经济复杂性并没有消失。

甚至，它可能变得更不容易被看到。

这带来了一个新的设计问题：

> **当界面变得更简单时，风险必须变得更显性。**

因此，Agentic Finance 的未来不能只是“让 AI 自主交易”。

它必须围绕 Agent 建立非常强的控制架构。

这很可能包括：

* 明确权限
* 持仓与名义金额限制
* 重大操作由人确认
* 可解释性
* 审计记录
* 情景分析
* 工具级权限控制
* 独立于模型本身的身份认证
* 建议与执行分离

因此，一种长期有效的架构可能是：

> **机器负责智能，人保留最终权力。**

机器可以极大扩展人的分析能力和操作带宽。

但对资本的最终控制权仍然清晰地掌握在人手里。

---

## 从交易软件到金融 Agent

如果这个方向继续发展，金融软件本身也会变得完全不同。

今天，软件产品通常由自己的界面来定义。

券商有自己的交易界面。

行情商有自己的数据界面。

研究平台有自己的研究界面。

风险系统有自己的风险界面。

而在 Agent-native 环境中，这些产品越来越可能变成一组可以被 AI 按需调用的能力。

Agent 本身成为界面。

金融产品则变成工具。

这和 API 对软件的影响很类似，只是抽象层更高。

API 让应用程序变得可编程。

Agent 则可能让不同应用可以围绕“意图”被动态组合。

未来，一个金融 Agent 可能同时协调：

* 券商账户
* 行情系统
* 研究服务
* 银行关系
* 预测市场
* 税务记录
* 组合分析
* 私募投资
* 企业资金管理

用户可能不再关心自己究竟正在使用哪一个软件产品。

他们只会关心：

> **我希望我的资本做什么。**

---

## 这对金融机构意味着什么

如果这个判断大方向正确，那么金融机构可能应该开始问一些完全不同的问题。

不应该只问：

> 我们如何给现有产品加上 AI？

而应该问：

> **我们的机构如何成为 AI Agent 可以直接使用的基础设施？**

这意味着需要重新思考基础设施。

### 券商

获得授权的 Agent，能否安全读取组合、行情、保证金和订单状态？

能否在不削弱用户最终控制权的前提下，构建交易？

### 交易所

Agent 能否程序化理解产品信息、交易规则、市场结构和实时市场状态？

### 行情供应商

Agent 能否获取同时具备上下文、授权信息和数据来源说明的数据，从而进行正确推理？

### 资产管理机构

投资流程能否在保持责任边界的前提下部分 Agent 化？

### 银行

资金管理、外汇、流动性和融资流程，能否通过受控机器接口开放？

### 监管机构

当 AI 深度参与金融决策时，责任应该如何分配？

这些问题最终会越来越像基础设施问题，而不是 Chatbot 产品问题。

---

## 从 Crypto-Native 到 AI-Native

这也是我认为 Crypto 和 AI 真正开始发生结构性连接的地方。

Crypto-native 市场是最早一批真正把 API 当作核心界面的金融生态。

API 不是辅助工具，而是基础设施本身。

这培养了一代以“可编程市场”为默认思维方式的交易机构。

AI 则引入了下一层抽象。

市场不再只是可编程。

它开始变得可以通过自然语言被理解和操作。

这形成了一个很有意思的演化路径：

> **电子化市场 → API-Native 市场 → Agent-Native 市场**

Crypto-native 交易机构可能会在这一转型中拥有天然优势。

它们已经习惯：

* 可编程执行
* 碎片化交易场所
* 连续市场
* 自动化风险管理
* 快速基础设施接入
* 机器驱动的工作流

而传统机构则带来另一组同样重要的能力：

* 受监管的市场准入
* 托管
* 清算
* 融资
* 信任
* 深厚资本池

下一代金融系统，很可能来自这两个世界的融合，而 AI 则位于它们之上，成为新的交互层。

---

## 更大的变化

当新技术进入金融时，我们往往首先关注资产本身。

Crypto 创造了新资产。

Tokenisation 把现有资产放到新的基础设施上。

但 AI 不一样。

它最大的影响，可能根本不是创造一种新资产。

它可能改变人类与**所有现有资产**交互的方式。

股票。

债券。

期货。

期权。

外汇。

Crypto。

私募市场。

预测市场。

界面本身开始拥有智能。

当界面拥有智能之后，过去隐藏在专业软件、技术能力和机构流程背后的复杂性，会越来越多地通过对话被访问。

这并不会消灭专业能力。

恰恰相反，它可能进一步提高“判断力”的价值。

只是人与机器之间的分工会发生改变。

人会花更少时间操作金融软件。

机器也不再需要等待完美结构化的命令。

两者之间的接口，变成了意图。

---

## 结语

当我第一次把 ChatGPT 和券商账户连接起来时，我原本只是期待一个更高效的研究和交易管理工具。

但让我意外的是，传统交易界面很快开始显得没那么重要了。

我不再思考：

> 我应该打开哪个页面？

而是开始思考：

> **我真正想知道什么，或者我究竟想实现什么？**

这个变化听起来很小。

但我认为，它可能是一个更大变化的开始。

几十年来，人一直在学习如何操作金融软件。

下一代金融软件，可能会开始学习如何理解并执行人的意图。

从电话到 GUI，改变了市场准入。

从 GUI 到 API，改变了量化交易。

而从 API 到 Agent，可能会改变投资者与金融基础设施之间的整个关系。

因此，下一场金融革命也许不会来自一种新的资产类别。

> **它可能来自一种与所有资产类别进行交互的新方式。**

如果这个判断成立，那么下一个时代最重要的金融机构，未必是拥有最好前端界面的机构。

它们更可能是那些最适合被智能 Agent 调用的基础设施提供者。
