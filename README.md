# hello-substrate

- 记录学习 `substrate` 的一些内容

## 笔记

[substrate](./docs/substrate/)
[优化](./docs/优化.md)
[调试](./docs/调试.md)

## 框架

[框架](./docs/substrate/frame)

## 工具

- [节点浏览器](https://polkadot.js.org/apps/?rpc=ws%3A%2F%2F127.0.0.1%3A9944#/explorer)
- [合约浏览器](https://contracts-ui.substrate.io/)
- [前端不会的调用方法可以搜索查看](https://github.com/TarikGul/jsonrpsee-external-tests)
- 问题解答 https://substrate.stackexchange.com/
- 在线的 BS58 解码器
  - https://whisperd.tech/bs58-codec/
  - 或者 bs58 库的 bs58::decode("12D3KooWBmAwcd4PJNJvfV89HwE48nwkRmAgo8Vy3uQEyNNHBox2")

## 学习方法

- [Substrate 学习网站](https://www.subdev.cn/)
- [详细介绍](https://mp.weixin.qq.com/s/dsdRCZGYdzRcjqW4BvT-kA)
- [官方文档](https://docs.substrate.io/quick-start/)
- [substrate 开发人员博客](https://www.shawntabrizi.com/portfolio/)
- [哔哩令狐视频](https://space.bilibili.com/485433391?spm_id_from=333.337.search-card.all.click)
- [熟悉 frame 自带的 pallet](https://github.com/paritytech/substrate/tree/master/frame)
- [polkadot 官方文档](https://wiki.polkadot.network/docs/getting-started)
- [polkadot.js 官方文档](https://polkadot.js.org/docs/)
- [subscan 浏览器](https://www.subscan.io/)
- [substrate 开放运行时模版库](https://github.com/open-web3-stack/open-runtime-module-library)
- [nft](https://github.com/rmrk-team/rmrk-substrate)
- [swallower nft](https://github.com/NFTicket-Lab/swallower)
- [官方代码文档阅读](https://crates.parity.io)
  - 如 [frame_system](https://crates.parity.io/sc_service/index.html?search=frame_system)

## 案例/实操

https://github.com/ParityAsia/hackathon-2022-summer/tree/main/teams/08-polket
https://github.com/ParityAsia/hackathon-2022-summer/tree/main/teams/15-melody
https://github.com/ParityAsia/hackathon-2022-summer/tree/main/teams/12-Web3Hacker.Ninja

- [黑客松的项目](https://github.com/ParityAsia/hackathon-2022-summer)
  - [项目列表](https://mp.weixin.qq.com/s/2gYmLylCseA6xt3TXeqocA)
- [substrate recipes 最佳实践](https://substrate.recipes/introduction.html)
  - https://github.com/JoshOrndorff/recipes
- [substrate 练习(有用!!)](https://github.com/rusty-crewmates/substrate-tutorials/blob/main/exercises/ex03-nft/nft/src/lib.rs)
  - [练习列表](https://github.com/rusty-crewmates/substrate-tutorials/tree/main/exercises)
  - [答案](https://github.com/rusty-crewmates/substrate-tutorials/tree/solutions/exercises)
- [在 Substrate 上如何完成某些特定的功能点](https://docs.substrate.io/reference/how-to-guides/)
  - [demo 地址](https://github.com/substrate-developer-hub/substrate-how-to-guides)
- [官方案例](https://github.com/paritytech/substrate/tree/master/frame/examples)
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
- [抛硬币](https://whisperd.tech/post/substrate_coin_flip/)
  - https://docs.substrate.io/reference/how-to-guides/pallet-design/incorporate-randomness/
