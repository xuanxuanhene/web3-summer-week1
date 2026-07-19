# Product / Protocol Reading Card

## 产品名称

**Uniswap**

官网：https://uniswap.org/

---

## 产品链接

- 官网：https://uniswap.org/
- App：https://app.uniswap.org/

---

## 解决的问题

在 Uniswap 出现之前，大多数数字资产交易依赖中心化交易所（CEX）。用户需要注册账号、完成身份验证，并将资产托管给交易所，一旦交易所出现安全问题或暂停服务，用户可能无法及时取回资产。

Uniswap 希望解决这一问题，让用户无需将资产交给第三方，也能直接完成链上 Token 交易，实现真正的去中心化交易。

---

## 核心机制

Uniswap 采用 **自动做市商（AMM，Automated Market Maker）** 机制，而不是传统交易所的订单簿模式。

其核心流程如下：

1. 流动性提供者（LP）将两种 Token 存入资金池。
2. 用户直接与资金池进行交易，而不是与其他用户撮合交易。
3. Token 价格根据资金池资产比例自动计算。
4. 每笔交易都会产生手续费，并按照流动性占比分配给 LP。

这种模式降低了交易门槛，也让任何人都可以成为流动性提供者。

---

## 主要用户

- 普通加密资产投资者
- Token 交易用户
- DeFi 用户
- 流动性提供者（Liquidity Provider）
- Web3 开发者
- DAO 与链上协议

---

## 关键数据

截至阅读时：

- TVL（Total Value Locked）约 **50 亿美元以上**（不同市场阶段会变化）。
- Uniswap 累计交易额已超过 **数万亿美元**，是目前最大的去中心化交易协议之一。

> 数据具有实时变化特点，建议提交前再次查看官方统计页面。

---

## 一个风险或疑问

### 风险

由于采用 AMM 机制，流动性提供者可能面临**无常损失（Impermanent Loss）**。当两种资产价格变化较大时，即使获得手续费收益，也可能最终低于单纯持有资产的收益。

### 我的疑问

未来是否能够在保持去中心化的前提下，进一步降低无常损失，使更多普通用户愿意提供流动性？

---

## 我的理解

我认为 Uniswap 最大的创新不是实现了 Token 交易，而是改变了交易方式。传统交易所依赖买卖双方撮合，而 Uniswap 使用资金池和自动定价机制，使任何人都可以随时完成交易，也能成为流动性提供者。这种设计推动了整个 DeFi 生态的发展，并成为许多新协议借鉴的基础。

---

## 资料来源

1. Uniswap 官网  
   https://uniswap.org/

2. Uniswap App  
   https://app.uniswap.org/

3. Uniswap Docs  
   https://docs.uniswap.org/

4. DefiLlama（TVL 数据）  
   https://defillama.com/protocol/uniswap

5. CoinMarketCap（协议介绍）  
   https://coinmarketcap.com/
