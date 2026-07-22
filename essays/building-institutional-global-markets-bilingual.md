---
layout: essay
title: "Building an Institutional Global Markets Setup from a Crypto-Native Starting Point"
title_zh: "从 Crypto-Native 起点搭建机构级全球市场交易体系"
description: "Entering traditional markets is not simply a matter of connecting another API. It requires a new institutional architecture across legal structure, market access, data, execution, clearing and financing."
description_zh: "进入传统市场，并不只是再接入一个 API，而是要围绕法律主体、市场准入、行情、执行、清算与融资，重新搭建一套机构级基础设施。"
date: 2026-07-23
author: "Seon Zhu"
series: "Institutional Global Markets"
chapter: 1
language: "en, zh-CN"
tags:
  - Institutional Trading
  - Global Markets
  - Crypto
  - TradFi
  - Market Infrastructure
  - Prime Brokerage
  - Market Data
  - Execution
---

> **Entering traditional markets is not simply an API integration project. It is an institutionalisation project.**

*This is Chapter 1 of **Institutional Global Markets**, a series on how crypto-native trading firms can build the market access, data, execution, clearing and financing capabilities required to operate across global traditional markets.*

---

## Introduction

For many crypto-native trading firms, entering traditional markets initially looks straightforward:

- Open a brokerage account.
- Connect an API.
- Purchase market data.
- Deploy an existing strategy to equities, futures or options.

That was also how I initially thought about the problem.

But the deeper we went into traditional markets, the clearer it became that accessing a new asset class is not simply a matter of adding another execution venue. It requires a different institutional architecture.

Crypto gave trading firms something historically unusual: relatively direct market access, unified collateral, continuous trading, API-native infrastructure and low barriers to experimentation. A capable team could open an institutional exchange account, integrate a relatively standardised API and begin trading spot, perpetual futures and options through a compact operating setup.

Traditional markets evolved differently.

Market access, data, execution, clearing, custody, financing and risk are frequently provided by different institutions, under different legal agreements, regulatory frameworks and technical arrangements. Even when the front end appears simple, the institutional structure behind it is not.

This distinction is becoming more important as the boundary between crypto and traditional assets continues to weaken.

Crypto platforms are already offering tokenised equities, stock perpetual futures, commodity-linked products and other forms of traditional-asset exposure. Kraken offers xStocks, tokenised representations of stocks and ETFs backed by underlying securities. Coinbase has launched stock perpetual futures for eligible non-US traders, providing continuous synthetic exposure to listed equities. Robinhood has combined brokerage, crypto, stock tokens and blockchain infrastructure within an increasingly global product strategy.[^1][^2][^3]

These products are still developing, and their legal, economic and market structures differ. But collectively, they point in the same direction:

> **Crypto market infrastructure and global capital markets are beginning to converge.**

For crypto-native trading firms, the strategic question is no longer simply whether to trade traditional assets.

The more important question is:

> **What institutional capabilities must we build before that convergence becomes fully investable?**

---

## Crypto-Native Strengths Are Real — but Incomplete

Crypto trading firms are not entering traditional markets from a position of weakness.

Many already possess capabilities that traditional institutions have spent years trying to develop:

- API-first execution infrastructure
- Real-time risk monitoring
- High-frequency market-making systems
- Cross-venue inventory management
- Continuous operational coverage
- Rapid product integration
- Experience with fragmented liquidity
- Familiarity with volatile collateral and fast-changing market structure
- A culture that favours experimentation and short implementation cycles

These are meaningful advantages.

A crypto-native team can often integrate a new venue faster than a traditional asset manager can complete its internal approval process. It may be more comfortable operating across multiple exchanges, collateral types and execution models. Its technology stack may also be more modular and easier to adapt.

However, these strengths can create a dangerous misconception:

> **Because the trading technology is portable, the entire operating model must also be portable.**

It is not.

A strategy may be economically transferable from crypto to equities, futures or options, but the infrastructure surrounding that strategy often has to be rebuilt.

Traditional markets introduce different assumptions around:

- Legal entities and licensing
- Broker and counterparty onboarding
- Market-data entitlements
- Exchange and venue fragmentation
- Trading hours and settlement cycles
- Pre-trade and post-trade controls
- Clearing and custody
- Securities lending
- Financing and collateral
- Corporate actions
- Reconciliation and operational accountability

The most common mistake is therefore to treat entry into traditional markets as an execution project.

In reality, it is an institutionalisation project.

---

## A Brokerage Account Is Not an Institutional Setup

A brokerage account can be sufficient to begin testing a strategy.

It is not, by itself, an institutional global markets platform.

A scalable institutional setup must answer at least five separate questions:

1. **Which legal entity can and should face the market?**
2. **Through which broker, FCM, clearing broker or prime relationship will the firm obtain market access?**
3. **Where will the strategy obtain authoritative and sufficiently granular market data?**
4. **How will orders, positions, limits and operational controls be managed?**
5. **How will the firm clear, finance, custody and hedge its positions as the business scales?**

These are not independent decisions.

The right broker depends on the products being traded, the legal entity, expected volumes, financing needs, strategy profile and operating model.

The right market data depends on the strategy’s latency sensitivity, depth requirements, venue coverage and licensing obligations.

The right execution architecture depends on whether the firm is running a directional book, a medium-frequency statistical strategy, an options portfolio or latency-sensitive market making.

The right clearing and financing relationship depends on balance-sheet usage, stock borrow, leverage, collateral eligibility, cross-margin opportunities and the economics the firm can generate for its counterparties.

A firm that answers only the execution question may be able to trade.

It may not be able to scale.

---

## The Five-Layer Institutional Global Markets Stack

I now think about the problem through five interconnected layers:

1. **Legal and regulatory structure**
2. **Market access**
3. **Market data**
4. **Execution and operational infrastructure**
5. **Clearing, financing and capital efficiency**

These layers should not be viewed as a purely linear technology stack. They interact with one another, and weaknesses in any one layer can constrain the entire platform.

---

## 1. Legal and Regulatory Structure

Before selecting technology, a firm must determine which entity will actually face the market.

This includes:

- The jurisdiction and regulatory status of the trading entity
- Whether the activity is proprietary trading or involves external capital
- Ownership, governance and authorised signatories
- Know-your-business and source-of-funds requirements
- Tax and reporting implications
- Product and jurisdiction restrictions
- Financial statements and audit history
- Whether counterparties will accept the firm’s structure and operating background

Crypto-native firms often underestimate this layer because crypto exchanges have historically been more willing to onboard offshore entities, distributed teams and relatively young companies.

Traditional counterparties may evaluate the same structure differently.

A firm can have substantial capital, sophisticated technology and experienced traders, yet still struggle to onboard because its legal structure, governance, documentation or compliance framework does not fit the counterparty’s risk appetite.

This is especially relevant for crypto-native firms seeking relationships with:

- Institutional securities brokers
- Futures commission merchants
- Prime brokers
- Banks
- Securities lenders
- Swap counterparties
- Traditional custodians

The first institutional lesson is therefore simple:

> **In traditional markets, institutional credibility is itself a form of infrastructure.**

It is built through legal clarity, governance, financial transparency, operational discipline and a coherent explanation of how the business works.

---

## 2. Market Access

“Broker” is not a single institutional category.

Depending on the product and stage of development, a firm may need some combination of:

- A broad electronic broker
- An institutional agency broker
- A futures commission merchant
- A clearing broker
- A prime broker
- A securities-lending counterparty
- A swap or derivatives counterparty
- Direct market access
- Sponsored access
- Multiple execution brokers connected to a common clearing arrangement

At the early stage, a broad electronic broker may be the correct choice.

It can provide access to multiple asset classes, mature APIs, basic financing, custody and operational tooling without requiring the firm to support an expensive institutional stack from day one.

For an emerging traditional-markets business, this can be an effective minimum viable setup.

But it has limits.

As the business scales, the firm may require:

- Better stock-borrow availability
- More competitive and predictable financing
- Higher message and order limits
- Lower-latency execution
- FIX connectivity
- More flexible account structures
- Better allocation and give-up workflows
- Portfolio or cross-product margin
- More responsive institutional support
- Multiple execution and clearing relationships
- Better control over where orders are routed and positions are held

The correct question is not:

> **Which broker is the best?**

It is:

> **Which type of market-access relationship matches our current strategy, scale, operational maturity and expected counterparty economics?**

A broker that is ideal for initial strategy validation may be unsuitable for a mature market-making operation. A prime broker with extensive capabilities may be economically irrational before the firm can generate sufficient financing, custody, clearing or execution revenue.

Institutional market access is therefore a maturity curve, not a one-time vendor selection.

---

## 3. Market Data

Crypto-native teams are accustomed to receiving usable order-book data directly from exchanges through relatively accessible APIs.

Traditional market data is more fragmented.

A strategy trading US equities, for example, may need to distinguish between:

- Consolidated data and direct exchange data
- Top-of-book and full-depth feeds
- Trades and quotes
- Auction and imbalance information
- Real-time and delayed entitlements
- Display and non-display usage
- Internal use and redistribution rights
- Broker-normalised data and native exchange protocols
- Historical and real-time datasets from the same or different sources

The cheapest available feed is not always sufficient.

The most comprehensive feed is not always necessary.

The decision should be driven by the strategy.

A medium-frequency strategy may operate effectively using consolidated trades and quotes. A market-making or microstructure strategy may require direct order-book depth, auction imbalance data or more deterministic delivery.

The key principle is not maximal data consumption.

It is **data-source awareness and independence**.

A trading firm should understand whether its pricing and risk decisions rely on:

- The market where the underlying asset actually trades
- A consolidated market feed
- A broker-normalised feed
- A third-party data vendor
- A derived benchmark or index
- Another exchange’s representation of the same asset

This becomes especially important as crypto venues list stock perpetuals, tokenised equities and other traditional-asset-linked products.

The quality of a derivative market ultimately depends on the quality, resilience and governance of its reference price.

If a crypto venue’s traditional-asset product depends heavily on a narrow set of external feeds, the trading team must understand how that dependency affects:

- Index robustness
- Mark-price behaviour
- Funding calculations
- Liquidation risk
- Trading during underlying-market closures
- Corporate actions
- Extraordinary market events

Market data is therefore not only a technical input.

It is part of the product’s risk architecture.

---

## 4. Execution and Operational Infrastructure

The execution stack should evolve with the business.

A firm does not need to purchase an expensive institutional order and execution management system on day one. Nor should it assume that a simple exchange-style API integration will remain sufficient indefinitely.

Depending on the strategy and scale, the stack may eventually include:

- Broker and venue gateways
- An internal order management system
- An execution management layer
- Pre-trade risk controls
- Position, cash and margin monitoring
- Drop copies
- Kill switches
- Order throttling and pacing controls
- Smart order routing
- Allocation and give-up workflows
- Transaction-cost analysis
- Automated reconciliation
- Monitoring and alerting
- Business-continuity procedures
- Independent recovery and failover paths

The objective is not maximum complexity.

It is controlled scalability.

> **The right architecture is the simplest setup that can safely support the firm’s current strategy while preserving a credible path to the next stage.**

This is where crypto-native firms have a genuine advantage.

Teams that already operate internal risk engines, exchange gateways, real-time monitoring systems and multi-venue execution do not need to recreate every legacy component of a traditional institution.

But they must understand which controls exist for a reason before deciding to remove, outsource or rebuild them.

For example, an internal execution stack may be technically capable of sending orders. That does not automatically mean it provides sufficient:

- Auditability
- Entitlement control
- Position reconciliation
- Exception management
- Corporate-action handling
- Operational ownership
- Business continuity
- Counterparty reporting

The distinction between a trading system and an institutional operating platform is often found in these less visible functions.

---

## 5. Clearing, Financing and Capital Efficiency

Execution attracts the most attention.

But financing and clearing often determine whether a strategy is economically scalable.

At small size, differences in margin, financing, custody and settlement may appear secondary. At institutional scale, they can determine the return on capital.

Important considerations include:

- Initial and maintenance margin
- Portfolio margin
- Cross-product offsets
- Cash and securities financing
- Stock-borrow availability and pricing
- Collateral eligibility and haircuts
- Settlement obligations
- Counterparty concentration
- Clearing and custody fees
- Minimum revenue expectations
- Capital fragmentation across brokers
- The operational cost of moving cash and positions
- The ability to net risk across products or entities

Prime brokerage is therefore not simply an upgraded execution service.

It is a balance-sheet relationship.

A prime broker or institutional clearing partner will evaluate not only whether the firm wants access, but whether its activity can generate sufficient financing, custody, clearing, borrow or execution revenue to justify the relationship.

This is one of the largest conceptual differences for crypto-native firms.

On a crypto exchange, a high-volume trader is often immediately valuable because it contributes fees and liquidity.

In traditional markets, a firm may trade meaningful volume while remaining commercially unattractive to a particular prime broker if it generates limited financing, borrow, clearing or custody revenue.

The firm must therefore understand not only its own economics, but also the economics of its counterparties.

> **Counterparty economics is part of infrastructure design.**

Without that understanding, a trading firm may pursue a relationship it cannot economically support—or select a setup whose fixed costs exceed the value it creates.

---

## A Three-Stage Institutionalisation Path

Emerging trading firms should not attempt to build the final institutional architecture immediately.

A staged approach is usually more capital-efficient.

---

### Stage 1: Market-Entry MVP

The objective is validation.

A typical setup may include:

- One suitable trading entity
- A broad electronic broker or FCM
- Broker APIs or a lightweight gateway
- Independent third-party market data where necessary
- Internal strategy and risk monitoring
- Manual operational controls supported by clear procedures
- Limited initial capital and carefully defined product scope

At this stage, the firm should test:

- Whether the strategy survives a different market microstructure
- Real execution and slippage costs
- Market-data quality
- Operational workload
- Trading-hour and settlement constraints
- Capital and margin requirements
- Reconciliation processes
- The revenue potential of the new asset class
- Whether the existing technology is genuinely portable

The goal is not institutional prestige.

The goal is to learn cheaply without creating an architecture that prevents later migration.

---

### Stage 2: Professional Institutional Setup

Once the strategy generates consistent activity and the constraints of the MVP become measurable, the firm can add:

- Institutional broker or FCM relationships
- FIX connectivity where justified
- More robust market data
- Automated reconciliation
- Stronger pre-trade controls
- Better sub-account and allocation workflows
- Improved financing or stock borrow
- More formal operational and compliance documentation
- Better monitoring of counterparty, collateral and concentration risk

At this point, the firm should be able to demonstrate:

- Expected and realised trading volume
- Assets and capital allocation
- Strategy characteristics
- Financing and borrow requirements
- Operational controls
- Revenue contribution to counterparties
- A credible growth plan

That evidence materially improves onboarding and commercial negotiations.

The firm is no longer asking counterparties to underwrite a concept. It can present an operating business.

---

### Stage 3: Prime and Multi-Asset Platform

The final stage is not simply “more brokers.”

It is an integrated capital and execution architecture.

This may involve:

- Prime brokerage
- Multiple execution brokers
- Centralised or optimised clearing
- Cross-product financing
- Securities lending
- An internal OMS and execution layer
- Multiple independent data sources
- Counterparty and collateral optimisation
- Multi-asset risk management
- Business continuity across providers
- A deliberate build-versus-buy strategy for each critical component

Only at this stage does the firm begin to operate as a genuine global markets platform rather than a crypto trading company with several traditional brokerage accounts.

The transition is not defined by prestige or the names of the counterparties.

It is defined by whether the firm can manage capital, risk, execution and operations coherently across products and institutions.

---

## What Should Be Built Internally?

A crypto-native firm should not outsource every traditional-market function.

Nor should it build everything internally.

The correct boundary depends on where the firm’s competitive advantage actually resides.

Capabilities are more likely to justify internal ownership when they are:

- Directly connected to strategy performance
- Latency-sensitive
- Highly differentiated
- Required across multiple counterparties
- Critical to real-time risk management
- Difficult to replace without operational disruption

These may include:

- Strategy logic
- Pricing models
- Real-time risk
- Position and inventory management
- Execution logic
- Venue and broker gateways
- Internal monitoring
- Capital-allocation logic

Capabilities are more likely to be purchased or outsourced when they are:

- Standardised
- Compliance-heavy
- Operationally mature in third-party products
- Expensive to maintain without creating trading edge
- Better supported by specialised providers

These may include:

- Certain market-data delivery services
- Reference and corporate-action data
- Standard OMS or EMS functions
- Regulatory reporting
- Reconciliation tooling
- Archival and audit infrastructure
- Selected middle- and back-office functions

The decision should not be ideological.

It should be based on:

- Strategic differentiation
- Time to market
- Total cost of ownership
- Operational risk
- Scalability
- Vendor concentration
- Portability across counterparties

A useful principle is:

> **Build the components that create or protect edge. Buy the components that merely reproduce institutional hygiene—unless buying them creates an unacceptable dependency.**

---

## The Future Is Not Crypto versus TradFi

The long-term direction is not that crypto firms become traditional institutions, or that traditional institutions simply adopt blockchain.

Both sides are moving toward a new market structure.

Crypto platforms are expanding into equities, commodities, event contracts, tokenised funds and private-market-linked products. Traditional platforms are extending trading hours, introducing digital assets and exploring programmable issuance and settlement.

The Bank for International Settlements has argued that tokenisation could integrate messaging, reconciliation and asset transfer on programmable platforms, potentially changing the structure of securities markets and cross-border finance.[^4]

The final form remains uncertain.

Tokenised securities, perpetual derivatives, traditional shares, centralised exchanges, decentralised protocols and regulated market infrastructure may coexist for a long time. Jurisdictional fragmentation will also remain important.

But the strategic direction is increasingly visible.

The eventual winners may be firms that combine:

- Crypto-native speed
- Traditional-market credibility
- Global product access
- Efficient collateral
- Institutional risk controls
- Programmable infrastructure
- Continuous distribution
- The ability to operate across multiple legal and market structures

For crypto-native trading firms, this creates a significant opportunity.

They do not need to abandon their operating culture or rebuild themselves in the image of a legacy bank.

But they must learn to operate across both systems.

---

## The Strategic Questions for Founders

Founders should not begin by asking which broker, market-data vendor or OMS to purchase.

They should begin with a smaller set of strategic questions:

1. **Which strategies and asset classes are strategically important to us?**
2. **What level of market access do those strategies actually require?**
3. **Which capabilities must remain internal sources of competitive advantage?**
4. **Which capabilities should be purchased or outsourced?**
5. **What institutional milestones will trigger the next stage of investment?**
6. **What economics can we realistically generate for brokers, clearers and financing counterparties?**
7. **Which early-stage decisions could create expensive migration problems later?**

The answers will differ by firm.

A medium-frequency futures strategy, an equity statistical-arbitrage book and an options market-making operation should not share the same infrastructure roadmap.

What they should share is a disciplined sequence:

> **Validate the strategy. Identify the binding constraints. Institutionalise the critical layers. Then optimise the platform.**

---

## Conclusion

Entering traditional markets is not primarily an API integration project.

It is the process of transforming a crypto-native trading organisation into a credible, scalable and capital-efficient global markets institution.

The biggest advantage of a crypto-native firm is not that it can copy its existing stack into another market.

It is that it can combine the speed and technical flexibility of crypto with the market access, financing and institutional discipline of traditional finance.

The firms that begin building this capability today will not merely gain access to additional products.

They will be better positioned for a future in which crypto, equities, futures, options, commodities and tokenised assets increasingly trade through interconnected—and eventually more continuous—global markets.

The opportunity is not simply to enter TradFi.

> **It is to help build what comes after it.**

---

## Institutional Global Markets Series

1. **Building an Institutional Global Markets Setup from a Crypto-Native Starting Point**
2. *What Crypto Trading Teams Underestimate About Traditional Markets* — Coming soon
3. *The Minimum Viable Stack for Trading US Equities and Futures* — Coming soon
4. *From Retail APIs to FIX: The Institutional Execution Maturity Curve* — Coming soon
5. *From IBKR to Prime Brokerage: When Should a Trading Firm Upgrade?* — Coming soon
6. *Market Data, Execution and Clearing Infrastructure for Emerging Trading Firms* — Coming soon

---

# 从 Crypto-Native 起点搭建机构级全球市场交易体系

> **进入传统市场，并不只是一个 API 接入项目，而是一场机构化升级。**

*本文是 **Institutional Global Markets（机构级全球市场）** 系列的第一章。该系列将讨论 Crypto-native 交易机构如何搭建进入全球传统市场所需的市场准入、行情、执行、清算与融资能力。*

---

## 引言

对于许多 Crypto-native 交易机构而言，进入传统市场最初看起来并不复杂：

- 开立一个券商账户；
- 接入一套 API；
- 购买所需行情；
- 将已有策略部署到股票、期货或期权市场。

我最初也是这样理解这个问题的。

但随着我们逐步深入传统市场，我越来越清楚地意识到：进入一个新的资产类别，并不只是增加一个交易场所。它要求交易机构重新搭建一套不同的机构基础设施。

Crypto 市场为交易机构提供了一种历史上并不常见的环境：相对直接的市场准入、统一抵押品、连续交易、API-native 基础设施，以及较低的试错门槛。一支能力足够强的团队，可以开立机构账户，接入相对标准化的 API，并通过一套较为紧凑的运营架构，开始交易现货、永续合约和期权。

传统市场的演化路径并不相同。

市场准入、行情、执行、清算、托管、融资和风险管理，往往由不同机构分别提供，并受不同的法律协议、监管框架和技术安排约束。即使前端交易体验看起来很简单，背后的机构结构也并不简单。

随着 Crypto 与传统资产之间的边界不断弱化，这种差异正在变得越来越重要。

目前，Crypto 平台已经开始提供代币化股票、股票永续合约、大宗商品挂钩产品，以及其他形式的传统资产敞口。Kraken 推出了 xStocks，即由底层股票或 ETF 支持的代币化资产；Coinbase 面向符合条件的非美国用户上线了股票永续合约，提供连续的合成股票敞口；Robinhood 则逐步将传统券商、Crypto、股票代币和区块链基础设施整合进其全球产品体系。[^1][^2][^3]

这些产品仍在快速演化，其法律属性、经济结构和市场机制也不完全相同。但它们共同指向了同一个趋势：

> **Crypto 市场基础设施与全球资本市场正在逐步融合。**

对于 Crypto-native 交易机构而言，战略问题已经不再只是“是否应该交易传统资产”。

更重要的问题是：

> **在这种融合真正形成大规模可交易机会之前，我们需要提前建立哪些机构能力？**

---

## Crypto-Native 的优势真实存在，但并不完整

Crypto 交易机构并不是以弱者身份进入传统市场。

许多团队已经具备传统机构花费多年才逐步建立的能力：

- API-first 的执行基础设施
- 实时风险监控
- 高频做市系统
- 跨交易场所库存管理
- 连续运营能力
- 快速产品接入
- 对碎片化流动性的理解
- 对高波动抵押品和快速变化市场结构的适应能力
- 偏好快速试验与短迭代周期的组织文化

这些都是实质性的优势。

Crypto-native 团队接入一个新交易场所的速度，往往快于传统资产管理机构完成内部审批的速度。它们通常也更习惯同时管理多个交易所、多种抵押品和不同执行模式，技术架构往往更加模块化，更容易调整。

但这些优势也可能带来一个危险的误判：

> **因为交易技术可以迁移，所以整套运营模式也可以直接迁移。**

事实并非如此。

一个策略的经济逻辑也许能够从 Crypto 迁移到股票、期货或期权市场，但围绕该策略运行的基础设施，通常需要重新建设。

传统市场带来了不同的制度与运营假设，包括：

- 法律主体与牌照
- 券商和交易对手 onboarding
- 行情授权
- 交易所与执行场所碎片化
- 交易时段与结算周期
- 盘前、盘中与盘后风险控制
- 清算与托管
- 融券
- 融资与抵押品管理
- 公司行动
- 对账与运营责任

因此，Crypto-native 机构最常见的错误，是将进入传统市场理解为一个执行接入项目。

实际上，它是一场机构化升级。

---

## 一个券商账户不等于机构级交易体系

券商账户可以帮助团队开始测试策略。

但一个账户本身，并不等于一套机构级全球市场平台。

一套可扩展的机构架构，至少必须回答五个问题：

1. **由哪个法律主体面对市场，且该主体是否适合长期使用？**
2. **通过哪类券商、FCM、清算经纪商或 Prime 关系获得市场准入？**
3. **策略从哪里获得权威、稳定且粒度足够的行情？**
4. **订单、持仓、限额与运营控制如何管理？**
5. **业务规模扩大后，如何完成清算、融资、托管与对冲？**

这些决策并不是彼此独立的。

合适的券商取决于交易产品、法律主体、预期成交量、融资需求、策略特征和运营模式。

合适的行情取决于策略对延迟、深度、交易场所覆盖和授权合规的要求。

合适的执行架构取决于团队运行的是方向性策略、中频统计策略、期权组合，还是对延迟敏感的做市策略。

合适的清算和融资关系，则取决于资产负债表使用方式、融券、杠杆、抵押品资格、跨产品保证金，以及团队能够为交易对手创造何种商业价值。

只回答了执行问题的机构，也许能够开始交易。

但未必能够扩大规模。

---

## 机构级全球市场体系的五个层次

我目前会从五个相互关联的层次理解这套体系：

1. **法律与监管结构**
2. **市场准入**
3. **市场数据**
4. **执行与运营基础设施**
5. **清算、融资与资本效率**

它们不是一套单纯从下到上的技术栈。每一层都会与其他层相互影响，任何一层的短板，都可能成为整个平台的约束。

---

## 1. 法律与监管结构

在选择技术之前，机构首先必须确定：究竟由哪个主体面对市场。

需要考虑的问题包括：

- 交易主体的注册地与监管状态
- 业务属于自营交易，还是涉及外部资本
- 股权、治理与授权签字人结构
- KYB 与资金来源要求
- 税务与申报义务
- 产品和司法辖区限制
- 财务报表及审计历史
- 交易对手是否接受该主体的结构与运营背景

Crypto-native 机构经常低估这一层，因为 Crypto 交易所过去通常更愿意接受离岸主体、分布式团队和成立时间较短的公司。

传统交易对手对同一主体可能有完全不同的判断。

一家公司即使拥有充足资本、成熟技术和优秀交易员，也可能因为法律结构、治理、文件或合规框架不符合交易对手的风险偏好，而难以完成 onboarding。

当 Crypto-native 机构尝试接入以下机构时，这个问题尤其明显：

- 机构证券经纪商
- 期货佣金商（FCM）
- Prime Broker
- 银行
- 融券交易对手
- 掉期或其他衍生品交易对手
- 传统托管机构

因此，第一条机构化经验非常简单：

> **在传统市场中，机构可信度本身就是一种基础设施。**

这种可信度来自清晰的法律结构、治理、财务透明度、运营纪律，以及对业务模式的完整说明。

---

## 2. 市场准入

“券商”并不是一个单一类别。

根据产品和发展阶段的不同，交易机构可能需要以下一种或多种关系：

- 综合型电子券商
- 机构代理经纪商
- 期货佣金商
- 清算经纪商
- Prime Broker
- 融券交易对手
- 掉期或衍生品交易对手
- 直接市场接入
- Sponsored Access
- 多个执行券商与统一清算安排

在初始阶段，综合型电子券商可能是正确选择。

它可以提供多资产类别准入、成熟 API、基础融资、托管和运营工具，又不要求机构第一天就承担昂贵的完整架构成本。

对于刚刚开始进入传统市场的交易机构而言，这往往是一套有效的最小可行方案。

但它存在上限。

随着业务规模扩大，机构可能逐渐需要：

- 更稳定、更充足的融券
- 更有竞争力和可预测的融资
- 更高的消息与订单限额
- 更低延迟的执行
- FIX 连接
- 更灵活的账户结构
- 更成熟的分配和 give-up 流程
- 组合保证金或跨产品保证金
- 更及时的机构服务支持
- 多执行、多清算关系
- 对订单路由和持仓托管位置更强的控制能力

因此，正确的问题不是：

> **哪一家券商最好？**

而是：

> **哪一类市场准入关系，最适合我们当前的策略、规模、运营成熟度，以及可为交易对手创造的经济价值？**

适合策略验证阶段的券商，未必适合成熟做市业务。能力完整的 Prime Broker，如果团队暂时无法产生足够的融资、托管、清算或执行收入，也可能并不具备经济合理性。

机构准入是一条成熟度曲线，而不是一次性的供应商选择。

---

## 3. 市场数据

Crypto-native 团队习惯于通过交易所 API，较容易地获得可用的订单簿数据。

传统市场的行情结构更加碎片化。

以美国股票为例，策略可能需要区分：

- Consolidated Feed 与交易所直连行情
- Top-of-book 与全深度行情
- 成交与报价
- 集合竞价与 imbalance 信息
- 实时与延迟授权
- Display 与 Non-display 使用
- 内部使用与再分发权利
- 券商标准化行情与交易所原生协议
- 实时数据和历史数据是否来自相同源头

最便宜的行情不一定足够。

最完整的行情也不一定必要。

选择应该由策略决定。

中频策略可能可以依靠 Consolidated Trades and Quotes 正常运行；做市或微观结构策略，则可能需要直接订单簿深度、集合竞价 imbalance 或更加确定性的行情传输。

关键并不是消费最多的数据。

而是保持对数据源的清晰认知与独立性。

交易机构应该明确，其定价与风险判断究竟依赖于：

- 底层资产实际交易的市场
- Consolidated Feed
- 券商标准化行情
- 第三方行情供应商
- 派生基准或指数
- 另一家交易所对同一资产的价格表达

随着 Crypto 交易所开始上线股票永续、代币化股票和其他传统资产挂钩产品，这一点变得尤其重要。

一个衍生品市场的质量，最终取决于其参考价格的质量、韧性和治理。

如果 Crypto 交易所的 TradFi 产品高度依赖少量外部数据源，交易团队必须理解这种依赖将如何影响：

- 指数稳健性
- Mark Price 表现
- Funding 计算
- 强平风险
- 底层市场休市期间的交易
- 公司行动
- 极端市场事件

因此，行情不仅是一个技术输入。

它也是产品风险架构的一部分。

---

## 4. 执行与运营基础设施

执行体系应当随着业务逐步演化。

交易机构没有必要在第一天就购买昂贵的机构级 OMS 或 EMS；但也不应假设，一套简单的交易所式 API 接入能够长期满足所有需求。

根据策略和规模，完整体系可能逐渐包括：

- 券商和交易场所 Gateway
- 内部订单管理系统
- 执行管理层
- 盘前风险控制
- 持仓、现金与保证金监控
- Drop Copy
- Kill Switch
- 订单节流与 Pacing 控制
- Smart Order Routing
- 分配与 Give-up 流程
- 交易成本分析
- 自动对账
- 监控与告警
- 业务连续性方案
- 独立恢复与故障切换路径

目标不是最大化复杂度。

而是实现可控的规模化。

> **正确的架构，是能够安全支持当前策略、同时为下一阶段保留可信升级路径的最简单方案。**

这是 Crypto-native 机构真正具有优势的地方。

已经运行内部风险引擎、交易所 Gateway、实时监控和多交易场所执行的团队，没有必要复制传统机构的每一个遗留组件。

但在删除、外包或重建之前，必须理解这些控制为什么存在。

例如，一套内部执行系统也许能够成功发送订单，但它未必自动具备充分的：

- 审计能力
- 权限控制
- 持仓对账
- 异常处理
- 公司行动处理
- 运营责任归属
- 业务连续性
- 交易对手报告

交易系统与机构级运营平台之间的差异，往往就存在于这些不容易被看见的环节。

---

## 5. 清算、融资与资本效率

执行最容易获得关注。

但真正决定策略能否经济性扩张的，往往是融资与清算。

在资本规模较小时，保证金、融资、托管和结算差异看起来可能并不重要；但进入机构规模后，它们会直接决定资本回报率。

关键问题包括：

- 初始保证金与维持保证金
- Portfolio Margin
- 跨产品风险抵扣
- 现金与证券融资
- 融券可得性与价格
- 抵押品资格与折扣
- 结算义务
- 交易对手集中度
- 清算与托管费用
- 最低收入要求
- 资金分散在多个券商造成的资本碎片化
- 现金与持仓迁移的运营成本
- 跨产品或跨主体风险净额结算能力

因此，Prime Brokerage 并不是更高级的执行服务。

它是一种资产负债表关系。

Prime Broker 或机构清算合作方评估的，不仅是机构是否希望获得接入，也包括该机构能否带来足够的融资、托管、清算、融券或执行收入，使双方关系具备商业合理性。

这是 Crypto-native 机构最需要理解的差异之一。

在 Crypto 交易所中，高成交量客户通常可以直接创造手续费与流动性价值。

在传统市场中，即使一家机构拥有可观成交量，如果无法产生足够的融资、融券、清算或托管收入，对某一家 Prime Broker 而言，仍然可能缺乏商业吸引力。

因此，交易机构不仅要理解自己的经济模型，还要理解交易对手的经济模型。

> **交易对手经济性，也是基础设施设计的一部分。**

缺乏这种理解，机构可能会追求一段自身无法经济性支持的关系，或者选择一套固定成本高于实际价值的架构。

---

## 三阶段机构化路径

新兴交易机构不应该试图一次性搭建最终形态。

分阶段推进，通常更加节约资本。

---

### 第一阶段：市场准入 MVP

这一阶段的目标是验证。

典型架构可能包括：

- 一个合适的交易主体
- 一家综合电子券商或 FCM
- 券商 API 或轻量 Gateway
- 必要时使用独立第三方行情
- 内部策略与风险监控
- 有明确流程支持的人工运营控制
- 有限的初始资本与清晰的产品边界

这一阶段应当测试：

- 策略能否适应不同的市场微观结构
- 实际执行成本与滑点
- 行情质量
- 运营工作量
- 交易时段与结算限制
- 资本与保证金需求
- 对账流程
- 新资产类别的收入潜力
- 现有技术是否真的能够迁移

目标不是获得机构光环。

目标是以较低成本学习，同时避免建立一套阻碍未来迁移的架构。

---

### 第二阶段：专业机构架构

当策略开始产生稳定交易活动，并且 MVP 的约束已经可以被量化时，机构可以逐步增加：

- 机构券商或 FCM 关系
- 在具备合理性时接入 FIX
- 更稳定、完整的市场数据
- 自动对账
- 更强的盘前风险控制
- 更成熟的子账户与分配流程
- 更好的融资或融券
- 更正式的运营与合规文件
- 对交易对手、抵押品和集中度风险的系统监控

到这一阶段，机构应当能够向交易对手展示：

- 预期与实际成交量
- 资产规模与资本配置
- 策略特征
- 融资与融券需求
- 运营控制
- 可以为交易对手贡献的收入
- 可信的增长计划

这些证据会实质性改善 onboarding 与商业谈判。

此时，机构不再要求交易对手为一个概念承担风险，而是在展示一项已经运行的业务。

---

### 第三阶段：Prime 与多资产平台

最终阶段并不是简单地增加更多券商。

而是形成一套整合的资本与执行架构。

它可能包括：

- Prime Brokerage
- 多家执行券商
- 集中化或优化后的清算
- 跨产品融资
- 融券
- 内部 OMS 与执行层
- 多个独立行情源
- 交易对手与抵押品优化
- 多资产风险管理
- 跨供应商业务连续性
- 针对每个关键组件明确的 Build-versus-Buy 策略

只有达到这一阶段，机构才真正开始从“一家拥有多个传统券商账户的 Crypto 交易公司”，转变为“全球市场交易平台”。

这种转变并不由合作机构的品牌或声望定义。

真正的标准是：机构是否能够跨产品、跨交易对手，统一管理资本、风险、执行与运营。

---

## 哪些能力应该自建？

Crypto-native 机构不应该外包所有传统市场能力。

也不应该什么都自己开发。

正确的边界，取决于机构的竞争优势究竟来自哪里。

更适合内部掌握的能力，通常具有以下特征：

- 与策略表现直接相关
- 对延迟敏感
- 具有较强差异化
- 需要跨多个交易对手重复使用
- 对实时风险至关重要
- 一旦替换会造成较大运营中断

例如：

- 策略逻辑
- 定价模型
- 实时风险
- 持仓与库存管理
- 执行逻辑
- 券商与交易场所 Gateway
- 内部监控
- 资本分配逻辑

更适合采购或外包的能力，通常具有以下特征：

- 标准化程度较高
- 合规负担重
- 第三方产品已经相对成熟
- 自建成本高但无法带来交易优势
- 专业供应商具备更强支持能力

例如：

- 部分行情传输服务
- Reference Data 与公司行动数据
- 标准 OMS 或 EMS 功能
- 监管报告
- 对账工具
- 归档与审计基础设施
- 部分中后台能力

决策不应建立在意识形态上，而应取决于：

- 战略差异化
- 上线速度
- 总拥有成本
- 运营风险
- 可扩展性
- 供应商集中度
- 跨交易对手可迁移性

一个实用原则是：

> **自建能够创造或保护交易优势的组件；采购只负责提供机构运营基本卫生的组件——除非采购会形成不可接受的依赖。**

---

## 未来并不是 Crypto 对 TradFi

长期来看，未来并不是 Crypto 机构变成传统机构，也不是传统机构简单采用区块链。

双方都在向一种新的市场结构靠近。

Crypto 平台正在扩展到股票、大宗商品、事件合约、代币化基金和私募市场挂钩产品；传统平台则在延长交易时段、引入数字资产，并探索可编程发行与结算。

国际清算银行认为，代币化有可能在可编程平台上整合消息传递、对账与资产转移，并进一步改变证券市场和跨境金融的结构。[^4]

最终形态仍然存在高度不确定性。

代币化证券、永续衍生品、传统股票、中心化交易所、去中心化协议和受监管市场基础设施，可能会长期共存。司法辖区之间的碎片化也不会很快消失。

但战略方向已经越来越清晰。

最终的赢家，可能是能够同时具备以下能力的机构：

- Crypto-native 的速度
- 传统市场的机构可信度
- 全球产品准入
- 高效抵押品
- 机构级风险控制
- 可编程基础设施
- 连续分发能力
- 跨多种法律与市场结构运营的能力

这为 Crypto-native 交易机构创造了重要机会。

它们不需要放弃原有运营文化，也不需要将自己完全重建成传统银行。

但它们必须学会同时在两个体系中运行。

---

## 创始人真正需要回答的战略问题

创始人不应从选择哪家券商、哪家行情供应商或哪套 OMS 开始。

更合理的起点，是回答以下问题：

1. **哪些策略和资产类别对我们具有真正的战略意义？**
2. **这些策略实际上需要什么级别的市场准入？**
3. **哪些能力必须保留为内部竞争优势？**
4. **哪些能力应该采购或外包？**
5. **哪些机构里程碑会触发下一阶段投入？**
6. **我们能够为券商、清算方和融资交易对手创造怎样的经济价值？**
7. **哪些早期决策可能在未来制造高昂的迁移成本？**

不同机构的答案不会相同。

中频期货策略、美股统计套利和期权做市，不应该共享同一套基础设施路线图。

但它们应该遵循相同的推进顺序：

> **先验证策略，再识别真正的约束；先完成关键层的机构化，再优化整个平台。**

---

## 结语

进入传统市场，本质上并不是一个 API 接入项目。

它是将一家 Crypto-native 交易组织，逐步转化为可信、可扩展、资本效率足够高的全球市场机构的过程。

Crypto-native 机构最大的优势，并不是可以将原有系统原封不动复制到另一个市场。

真正的优势在于，它能够将 Crypto 的速度和技术灵活性，与传统金融的市场准入、融资能力和机构纪律结合起来。

今天开始建立这些能力的交易机构，未来获得的不仅是更多可交易产品。

它们还将更有能力参与一个逐渐形成的新市场：Crypto、股票、期货、期权、大宗商品和代币化资产，将通过越来越相互连接、最终也可能更加连续的全球基础设施进行交易。

真正的机会，并不只是进入 TradFi。

> **而是参与构建 TradFi 之后的下一代市场。**

---

## Institutional Global Markets 系列

1. **Building an Institutional Global Markets Setup from a Crypto-Native Starting Point**
2. *What Crypto Trading Teams Underestimate About Traditional Markets* — 即将发布
3. *The Minimum Viable Stack for Trading US Equities and Futures* — 即将发布
4. *From Retail APIs to FIX: The Institutional Execution Maturity Curve* — 即将发布
5. *From IBKR to Prime Brokerage: When Should a Trading Firm Upgrade?* — 即将发布
6. *Market Data, Execution and Clearing Infrastructure for Emerging Trading Firms* — 即将发布

---

## References

[^1]: Kraken, “[Tokenized Stocks and ETFs on Kraken](https://www.kraken.com/xstocks).” xStocks are tokenised representations of stocks and ETFs and are subject to jurisdictional availability and product-specific terms.

[^2]: Coinbase, “[Coinbase Launches Stock Perpetual Futures](https://www.coinbase.com/blog/coinbase-launches-stock-perpetual-futures),” March 20, 2026. Availability is limited to eligible users and jurisdictions.

[^3]: Robinhood, “[Robinhood Accelerates Global Expansion with Robinhood Chain Mainnet, Stock Tokens, Agentic Trading and New Suite of DeFi Products](https://robinhood.com/us/en/newsroom/robinhood-accelerates-global-expansion-robinhood-chain-mainnet-stock-tokens-agentic-trading/),” July 1, 2026.

[^4]: Bank for International Settlements, “[The Next-Generation Monetary and Financial System](https://www.bis.org/publ/arpdf/ar2025e3.htm),” *Annual Economic Report 2025*, Chapter III.

---

*The views expressed in this essay are personal and do not represent those of any employer or affiliated organisation. This article is provided for informational purposes only and does not constitute investment, legal, regulatory or tax advice.*

*本文仅代表作者个人观点，不代表任何雇主或关联机构的立场。本文仅供信息交流，不构成投资、法律、监管或税务建议。*
