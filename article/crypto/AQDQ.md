# Accumulator（AQ）与 De-ccumulator（DQ）

---

## 一、概念总览

| 名称           | Accumulator (AQ)       | De-ccumulator (DQ)       |
|----------------|------------------------|---------------------------|
| 中文名         | 累积式认购 / 买入      | 累积式认沽 / 卖出         |
| 投资方向       | 看跌不破，逐步建仓      | 看涨不强，逐步止盈         |
| 预期市场       | 震荡或小幅下行          | 震荡或小幅上行             |
| 投资行为       | 越跌越买                | 越涨越卖                   |
| 常见用途       | 平均买入成本 / 建仓     | 平均卖出价格 / 减仓        |
| 常见机制       | Double-Up、敲出条款等   | Double-Down、敲出条款等    |

---

## 二、Accumulator（累积式认购）

### ✅ 定义
在约定的行权价以下，按固定频率买入标的资产（如股票或加密货币），在价格越低时可能触发 **Double-Up**，即买入数量翻倍。

### ✅ 参数说明
- **行权价（Strike Price）**：买入价格，通常低于当前市价
- **Double-Up机制**：当市价低于某个阈值（如 Spot 的95%）时，买入数量翻倍
- **敲出价（Knock-Out Level）**：价格上涨至此水平时产品终止（可选）

### ✅ 风险与收益
- 优势：低价买入，摊低持仓成本
- 风险：熊市或单边下跌时被迫买入大量资产，浮亏显著

---

## 三、De-ccumulator（累积式认沽）

### ✅ 定义
在设定的行权价以上，按固定频率卖出持有的标的资产，在价格越高时可能触发 **Double-Down**，即卖出数量翻倍。

### ✅ 参数说明
- **行权价（Strike Price）**：卖出价格，通常高于当前市价
- **Double-Down机制**：当市价高于某个阈值时，卖出数量翻倍
- **敲出价（Knock-Out Level）**：价格下跌至此水平时终止（可选）

### ✅ 风险与收益
- 优势：在较高价格逐步减仓，控制风险
- 风险：若价格持续上涨，可能错失更高收益

---

## 四、Crypto 场景特别说明

### 🔑 特点
- 高波动性导致结构易触发 Double-Up / Down
- 可用于主流币（BTC、ETH、SOL等）
- 支持链上结构（如 DeFi 自动执行）
- T+0结算、7x24小时运行
- 无本金保障，需严格风险管理

---

## 五、BTC Accumulator 模拟示例

- **币种**：BTC  
- **市场价**：$105,000  
- **行权价**：$110,000  
- **每日买入**：0.1 BTC  
- **期限**：30天  
- **Double-Up 触发**：$105,000 以下  
- **敲出条款**：无  

### 📈 模拟结果
- **最大浮亏**：约 -$180,000  
- **盈亏平衡点**：约 $110,060  

结论：BTC 需收盘价 > $110,060 才能整体盈利；低于此则因高价买入和加仓机制，浮亏加重。

---

## 六、适用建议

| 适合人群               | Accumulator                               | De-ccumulator                             |
|------------------------|--------------------------------------------|-------------------------------------------|
| 资产配置               | 想低价建仓，看好长期走势                   | 持有较多资产，想高价止盈                   |
| 市场观点               | 短期震荡或小跌，看好长期                   | 短期震荡或小涨，但不希望继续暴涨           |
| 风控能力要求           | 较高（需有足够资金应对持续加仓）           | 中等（有序退出资产）                       |

