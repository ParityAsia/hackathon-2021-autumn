## 基本资料

项目名称：Eternity Network

项目立项日期 (哪年哪月)：2021年5月1日


## 项目愿景
    Eternity Network正在尝试在区块链世界web3.0时代构建量化服务的基础设施,Eternity Network将成为第一个“去中心化量化协议”着力解决交易市场中的量化服务问题.
## 项目介绍

    区块链上的量化交易通常对网络的要求很高，这意味着它们很难在链上完成。Solidity 处理起来很棘手且不适用于需要复杂业务场景的量化问题.offchain work也并不能解决链下程序可信执行问题.永恒实验室提出构建可信链下网络环境,来处理日益增长量化服务的需求.基于机密计算TEE SGX的方案来构建“去中心化量化协议”.
    Eternity Network由4部分构成.1)基于substrate 3.0 framework构建链上网络. 2)基于Intel SGX构建链下安全环境. 3) 建立链下验证节点确保执行程序可信问题. 4)智能合约经济系统.
    Intel SGX是Intel架构新的扩展, 在原有架构上增加了一组新的指令集和内存访问机制这些扩展允许应用程序实现一个被称为enclave的容器, 在应用程序的地址空间中划分出一块被保护的区域, 为容器内的代码和数据提供机密性和完整性的保护, 免受拥有特殊权限的恶意软件的破坏.通过SGX在链下构建了一个安全且无法改变的环境.量化程序则放在enclave容器中,无法更改.从而确保节点的安全性.链下节点验证网络,在整个网络中的作用是验证链下节点安全性和环境稳定的节点.验证节点对服务节点发起随机挑战检测节点的状态和量化程序的日志系统与实际环境的出入来确保节点状态.日志系统上传至IPFS网络中如果验证节点成功发现作恶节点则能够得到验证收益.整个系统都需要质押代币来确保节点安全运行.

    智能合约经济系统支持跨链交易.用户通过智能合约即可参与到整个网络到量化服务当中,而不用去担心其背后量化逻辑. 为促进量化市场的经济与流动性繁荣. 我们在经济模型上,采用亏损补偿对冲方案. 如果资金出现亏损则产生代币收益,如果盈利则能够得到USDT的收益,同时整个生态系统也能够因此获益.

## 团队介绍

      liangjun:精通数学建模、区块链顶层架构设计师、项目孵化、区块链底层开发.

      huifeng:2年区块链开发经验,精通联盟链.波卡中国大使，精通区块链底层开发.

      yifan:清华大学毕业，精通量化、机器学习.现保送清华大学硕士.

      Tom:10年技术开发经验，知名区块链开发工程师，精通密码学、隐私计算、智能合约
      
      GuoDong:工程师 ,10年以上的开发经验,北京交通大学土木工程毕业,区块链行业从业者，有丰富的技术栈以及多领域开发经验。
## 黑客松期间计划完成的事项

demo

**区块链前端**

  1)唤起智能合约

**边缘设备**

  1)基于intel SGX 部署量化节点

**substrate链**
  
  1)构建Quant-pallet
