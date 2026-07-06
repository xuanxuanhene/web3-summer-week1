# MessageBoard v0.1
项目简介
这是一个部署在 Monad Testnet 上的最小 Solidity 智能合约，用于学习智能合约开发流程。
该合约实现了一个简单的留言板功能：
- writeMessage(string)：写入一条留言
- readMessage()：读取当前保存的留言
整个项目主要用于学习 Solidity 编写、Remix 编译部署、MetaMask 钱包连接、Monad Testnet 部署以及链上交互流程。
### writeMessage(string)

用于修改链上的 message。

示例：

```
Hello Monad!
```

调用后会发起一笔链上交易，因此需要支付少量测试网 Gas。

---

### readMessage()

读取当前保存的 message。

这是一个 view 函数，不会修改区块链状态，因此不会消耗 Gas。

---

## 开发环境

- Solidity ^0.8.20
- Remix IDE
- MetaMask
- Monad Testnet

---

## 部署步骤

1. 打开 Remix IDE。
2. 创建 MessageBoard.sol。
3. 编译 Solidity 合约。
4. MetaMask 切换到 Monad Testnet。
5. Deploy Environment 选择 Browser Extension。
6. 点击 Deploy。
7. MetaMask 确认交易。
8. 获得合约地址。

---

## 合约交互

### 写入

调用：

```
writeMessage("Hello Monad!")
```

点击 Transact。

MetaMask 确认交易。

---

### 读取

调用：

```
readMessage()
```

即可读取当前保存的信息。

---

## 学习收获

通过本项目，我完成了：

- Solidity 最小智能合约开发
- Remix 编译部署
- MetaMask 连接测试网
- Monad Testnet 部署
- 链上交易确认
- 合约读写交互
- 区块浏览器查看 Transaction Hash

