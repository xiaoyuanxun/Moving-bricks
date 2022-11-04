# Moving-bricks
- 由GALA搬砖套利所引发的一些思考与准备

## [GALA事件](https://twitter.com/pNetworkDeFi/status/1588266897061031936)

- 概述：项目方部署合约配置跨链桥错误，导致黑客利用bug增发给自己了几百亿的GALA代币。黑客利用大量的代币掏空了pancake的池子，导致人们可以以很低的价格在链上买到大量的GALA代币。

- GALA代币区别为ERC和BSC两条链，而出问题的是BSC链的合约，其他CEX平台及时的关闭了BSC链的冲提（所以其他CEX所受影响不是很大)，而Huobi没有及时关闭而且秒到。所以链上的用户以低价大量购买提到huobi抛售，导致huobi的GALA直接被砸了84%

- GALA价格被砸的很低的时候，Huobi还是没有关闭冲提，并且可以买了提到ERC链然后在冲到Binance卖，所以又一波搬砖。

- [套利者赚的钱比攻击者还多](https://www.panewslab.com/zh/sqarticledetails/2ssqmgfw.html)

## 下一次再发生类似事件如何操作？如何未雨绸缪？

### 如何监听发现？
- 熬夜党
- 开启媒体快讯推送，律动、PanNews...；twitter订阅一些大V消息提醒
- 程序化监听？
    
    ：监控链上，链下相互之间价格差异 -> 警报(邮件？ 电话？)

### 如何搬砖？

- 注册好各个平台的CEX，弄好KYC。

- 熟悉链上的SWAP：
    
    1. 区别ERC，BSC等链的区别
    2. 钱包准备好：MetaMask
    3. 熟悉如何Swap：常用的 Swap dAPP， 滑点设置等...
    
- 程序化搬砖：

    1. dex低价购入充到cex：可以脚本实现
    2. dex搬砖到另一个dex：可以脚本实现
    3. cex搬砖cex： 冲提有各种验证码，估计不行？拼手速，临危不乱

