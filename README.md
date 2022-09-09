# hello-substrate

- 记录学习 `substrate` 的一些内容

## 笔记

[新增一个 pallet](./docs/新增一个pallet.md)

## 工具
- 问题解答 https://substrate.stackexchange.com/
- 在线的 BS58 解码器
  - https://whisperd.tech/bs58-codec/
  - 或者 bs58库的 bs58::decode("12D3KooWBmAwcd4PJNJvfV89HwE48nwkRmAgo8Vy3uQEyNNHBox2")

## 学习方法

- [Substrate学习网站](https://www.subdev.cn/)
- [详细介绍](https://mp.weixin.qq.com/s/dsdRCZGYdzRcjqW4BvT-kA)
- [官方文档](https://docs.substrate.io/quick-start/)
- [substrate recipes 最佳实践](https://substrate.recipes/introduction.html)
  - https://github.com/JoshOrndorff/recipes
- [substrate 开发人员博客](https://www.shawntabrizi.com/portfolio/)
- [在 Substrate 上如何完成某些特定的功能点](https://docs.substrate.io/reference/how-to-guides/)
  - [demo 地址](https://github.com/substrate-developer-hub/substrate-how-to-guides)
- [哔哩令狐视频](https://space.bilibili.com/485433391?spm_id_from=333.337.search-card.all.click)
- [熟悉 frame 自带的 pallet](https://github.com/paritytech/substrate/tree/master/frame)
- [polkadot 官方文档](https://wiki.polkadot.network/docs/getting-started)
- [polkadot.js 官方文档](https://polkadot.js.org/docs/)
- [subscan 浏览器](https://www.subscan.io/)
- [抛硬币](https://whisperd.tech/post/substrate_coin_flip/)
  - https://docs.substrate.io/reference/how-to-guides/pallet-design/incorporate-randomness/

## 案例 examples

- [swallower](https://github.com/NFTicket-Lab/swallower)
- [官方案例](https://github.com/paritytech/substrate/tree/master/frame/examples)
- [官方代码文档阅读](https://crates.parity.io)
  - 如 [frame_system](https://crates.parity.io/sc_service/index.html?search=frame_system)
- [部署公开测试网](https://whisperd.tech/post/substrate_launch_public_testnet/)
- [文件存在证明应用程序](https://github.com/hello-substrate/substrate-pallet/tree/file-exists-claim)
  - [源码](https://github.com/hello-substrate/substrate-pallet/tree/file-exists-claim)
  - https://docs.substrate.io/tutorials/work-with-pallets/use-macros-in-a-custom-pallet/
- [简单的链上众筹应用程序](https://github.com/hello-substrate/substrate-pallet/tree/simple-crowd-fund)
  - [源码](https://github.com/hello-substrate/substrate-pallet/tree/simple-crowd-fund)
  - https://substrate.recipes/crowdfund.html
- [kitties chain 加密猫 demo](https://github.com/hello-substrate/substrate-pallet/tree/kitties)
  - [源码](https://github.com/hello-substrate/substrate-pallet/tree/kitties)
  - [推荐教程](https://sacha-l.github.io/substrate-collectables-workshop/#/) 与 [源码](https://github.com/substrate-developer-hub/substrate-node-template/tree/tutorials/solutions/kitties)
  - [教程地址](https://doc.deepernetwork.org/tutorials/v3/kitties/pt1/)
