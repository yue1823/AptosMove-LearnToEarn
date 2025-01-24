# AptosMove LearnToEarn

Aptos Move Learn To Earn 是由 Faintlight x KeyMap 联合发起的 Aptos Move 共学营。

帮助大家学习 Aptos Move 合约以及更高级的合约操作以及 typescript sdk 、React 中的 wallet 组件的用法等。

希望大家可以用更轻松的心态学习一门新的语言，接触新的公链技术

## 任务列表

| 任务编号 | 任务名称 | 任务奖励 |
|--------|--------|--------|
| Task 1 | 完成 Aptos Testnet 上的 hello  world 合约部署 | 1 USDT |


### Task 1

任务简要： 完成 Aptos Testnet 上的 hello  world 合约部署
任务奖励： 1 USDT 
任务详情：

- 完成 hello world 合约，并将 event 输出改为 "hello <Your github id>"
- 将合约部署 txn 写入合约的注释部分
- 将合约源码用 pull request 的方式提交至当前仓库（合约应该放入 一个以你的 Github id 作为名字的文件夹）
- 等待 PR 审核，完成修改
- 将已经合并的 PR 链接发送至 Build3 的 Proof 等待审核并领取奖励

#### Task 1 操作步骤（Task 1 为示例教学关，后续不会由操作步骤演示）：

1. **Fork 本项目**  
   点击右上角的 `Fork` 按钮，将项目 fork 到你的 GitHub 账户。

2. **Clone 本地仓库**  
   在本地将 fork 后的仓库 clone 到你的本地：

   **注意修改 <your-username> 部分为你的 Github id，否则 clone 失败**
  
   ```bash
   git clone https://github.com/<your-username>/AptosMove-LearnToEarn.git
   cd AptosMove-LearnToEarn
   ```
3. **创建文件夹结构**
  在根目录下创建一个以你的 GitHub ID 命名的文件夹，然后在该文件夹下创建 task1 文件夹，并将 Hello World 合约放入该文件夹中
  
  例如，假设你的 GitHub ID 为 username，文件夹结构应如下所示：

  ```
  username/
  └── task1/
      └── sources
          └── hello_world.move
      └── Move.toml
  ```

  1. 可以使用 `mkdir username` 创建外层文件夹

  2. 然后使用 `mkdir task1` 创建 task 1 文件夹

  3. 并执行 `aptos move init --name task1` 创建 Aptos 项目目录结构

  4. 在 sources 目录下创建 hello_world.move 文件
