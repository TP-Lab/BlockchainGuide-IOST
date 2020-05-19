# 从0到1入门IOST钱包

## 前言

自从比特币主网上线至今，区块链的发展经历了1.0-3.0三个时期的迭代，作为区块链的重要入口，钱包也逐渐发展完善。从最开始的只能储存、收发比特币的单链钱包，到后来能进行链上合约操作的以太坊钱包，再到现在钱包不止是为用户提供存储、流通的资产管理工具，更是一个公链生态服务平台，越来越多的钱包往多链方向发展。

IOST是继ETH、EOS、波场后，第四个有丰富生态的公链，采用PoB（置信度证明）共识机制和第二层扩展方案，比基于DPoS机制的EOS更去中心化，比ETH智能合约平台更具可扩展性。IOST在生态上优势明显，吸引了众多币圈用户和开发者的青睐，被称为最具潜力的第四代公链。

钱包作为连接区块链的重要工具、公链生态的一部分，是一条公链生态中极为重要的入口，同样IOST钱包也是IOST生态的重要构成要素。IOST主网正式上线后，多个主流区块链手机钱包已与IOST达成合作，将依托自己在区块链领域的技术积累和安全经验，基于IOST网络提供给钱包用户便捷、安全的数字资产管理服务和内容友好、功能强大的 DApp 体验等。IOST用户可以使用IOST钱包，享受便捷安全的数字资产管理服务，玩转IOST的丰富生态。

## IOST账号与钱包

和 BTC、ETH 使用一长串毫无规律的哈希地址不同，IOST 公链采用的是账号体系，IOST 上的基本操作都是以账号为基本单位的。

IOST 账号由5~11个字符组成，字符包括字母、数字和下划线，而且 IOST 账号类似于支付宝/微信账号那样可以进行自定义，用户可以根据自己的需要创建容易记住的账号，和其他公链相比，IOST 的账号体系更加接近我们的生活场景。

### 激活码创建

创建 IOST 账号是需要支付一定的资源费用的，对于大多数小白用户来说，并不知道如何用区块链的方式支付资源费用，因此钱包为大家提供了更简单的账号创建方式。

以 TokenPocet 钱包（以下简称TP钱包）为例，第一次创建 IOST 账号建议选择【激活码创建】，使用这种方式本质是把创建账号需要的资源费用以法币支付，可选的支付方式有支付宝、微信或 Paypal，十分便捷。

<figure class="half">
<img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589870644665.png" width="50%"><img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589858538611.png" width="50%">
</figure>

### 好友创建

好友创建本质是通过其他账号来支付创建 IOST 新账号所需的资源费用。即可以用已经持有IOST的账号来支付新账号的创建费用，或是让朋友来帮忙支付。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860085039.png "IOST钱包")

在钱包中把创建 IOST 账号产生的订单信息页面发送给好友，由好友代为支付创建 IOST 账号所产生的费用，好友支付成功后就可以激活账号使用了，当然了好友代付这一步你也可以用自己的账号支付。

###  质押创建 

使用质押创建账户，需要有另外一个账号帮忙质押10个IOST才能够完成新账户创建，用户可以使用 IOSTABC 浏览器进行质押创建，创建账号前需要先安装浏览器插件 iWallet 并登录 IOST 账号。

###  免费创建 

为了让更多用户零门槛进入IOST生态，很多节点以自费补贴账号成本的方式，让用户可以0花费创建IOST账号。

1、通过TokenPocket 免费创建

当前用户可以通过加入TP钱包IOST社区免费获得IOST激活码。

2、通过 jetstream 免费创建

Jetstream是一款web端插件钱包，在Jetstream可以帮助用户直接免费创建 IOST帐号，只需要"添加钱包”时"选择IOST"，然后"创建新钱包"、"记录私钥"、"输入用户名"，就可以免费创建IOST账号。

<figure class="half">
<img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860179912.png" width="50%"><img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860198495.png" width="50%">
</figure>


此外，由于私钥是一个长字符串，长度超过64位，并且很难记住，Jetstream还为用户提供了双重加密功能及将密码存储在Google Cloud中的选项，此功能可自选是否使用。

IOST 账号创建完成后，就可以在 IOST 钱包进行收款、转账、给节点合伙人投票等相关操作了。

## IOST Token与钱包

### IOST Token发行

IOST的总供给量为210亿枚。IOST网络后续发行的代币只是对应通缩，不会稀释现有代币价值。由于IOST的通缩补齐机制，总供给量在动态变化的同时保持基本平衡在210亿枚的总供给量不变。此外，IOST基金会于2018年-2019年底锁仓的73.5亿IOST已解锁，IOST基金会承诺将其持有的Token用作项目的长远建设以及生态发展

IOST采用的是 PoB 共识机制，它本质上是从 PoS 演化而来的，但是比起PoS共识机制，IOST独创的PoB共识机制在高扩容性能的基础上保证了去中心化和安全性能。IOST的出块工作是由出块节点来完成的。

质押投票是区块链系统中重要的自治机制，持续为IOST社区服务、贡献代码并参与社区治理的节点合伙人将会获得更多社区质押投票。

持币者手中的质押投票权可以决定哪些候选人将成为节点合伙人、运行IOST网络并参与社区治理，并进而决定IOST生态的未来发展方向，IOST希望更多社区成员参与到这个过程中来，因此IOST 会给予投票者丰厚的质押投票激励。

### IOST NFT Token

1、IOST官方NFT标准协议

我们常见的Token（如IOST）都是同质化的，每个IOST之间没有任何区别（就像2张100元人民币一样），可以互换和分割。而NFT的重要特征在于：每一个NFT拥有独特且唯一的标识，两两不可互换，最小单位是1且不可分割。 

2020年4月，IOST正式发布官方NFT标准协议，开发者可以直接调用（提供发行基础），降低了开发和接入难度，为开发者发行NFT资产降低门槛、提供便利；此外，IOST官方NFT标准协议让基于IOST公链的NFT标准统一，为NFT资产的流通提供便利（统一发行及流通标准），也为IOST链上NFT资产在不同场景或者游戏之间的复用提供了可能性。 

对于用户来说，IOST推行NFT资产的使用，可促进游戏资产等数字资产NFT化，实现数字资产确权，解决数字资产的安全性问题，并极大程度上提高IOST生态内数字资产的流通性。 可以说，NFT就是数字资产的基石。而IOST官方对NFT的战略布局，将为IOST生态发展带来极大助力。

IRC721定义了IOST生态中的NFT标准，具有6大特性： 

+ IRC721的主要特点是“Non-Fungible Token”，非同质化通证，简称为NFT。每一个IRC721代币都有唯一的NFT ID标识，只会有一个Owner；
+ 充分考虑了数字资产/藏品的应用场景，提出了跨链转移的标准化操作，让发行方有更大操作自由度；
+ 根据数字资产/藏品的特点，区分了稳定信息存储区（EXT）和附加信息区（META），更加贴近生产需要；
+ 制定了数字资产/藏品的锁定转移机制，发行NFT资产时将会有更大的灵活度；
+ 包含了黑名单管理功能，为游戏、娱乐类应用提供必要的管理手段；
+ IRC721将会是新一代NFT资产协议中的领先者。
  
如果你对接入IOST官方NFT标准感兴趣，可查阅IRC721标准文档：
https://developers.iost.io/docs/zh-CN/3-smart-contract/Token721.html 

*感谢IOST节点合伙人XPET对IRC721协议完善过程的贡献。

4月13日，IOST链上首个支持NFT跨链转移的游戏资产交易平台——掠宝网正式上线。

![掠宝网](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860229249.png "掠宝网")

掠宝网网址：www.xloot.io

作为综合型的游戏资产交易平台，掠宝网旨在促进传统游戏与区块链游戏的大融合，发挥区块链技术在“游戏资产确权”及“高效流通”的价值，实现同一游戏资产在多个独立游戏之间的映射与复用。愿景是成为游戏领域的淘宝平台，为游戏开发商及游戏玩家提供一站式的游戏资产发行及采购、售卖服务。

对于游戏开发商来说，该平台可为其提供游戏资产发行及上架售卖服务。

对于游戏用户来说，该平台可为其提供一站式游戏资产购买、售卖、抵押、租赁等功能。

掠宝网三大优势如下：

+ 兼容多种游戏类型
  
兼容传统单机游戏、互联网游戏以及区块链游戏，受众用户更广，促进不同类型游戏资产的融合与流通。

+ 支持多种加密资产协议
  
支持IOST IRC721、EOS UCAT等主流NFT标准协议，后期还将支持以太坊、Cocos等其他区块链资产协议。

+ 支持区块链游戏资产跨链转移
  
支持IOST及EOS公链主流NFT游戏资产的跨链转移功能。

目前掠宝网已上线TokenPocket钱包、BEPAL钱包、DappBirds钱包、DAppX钱包，欢迎各位社区用户前去体验。

### IOST节点投票

**1、IOST投票规则**

+ 质押1 IOST=1票，1票1投；
+ 1 个账户可以给多个候选人投票，候选人也可以给自己投票；
+ 质押并用于购买资源的Token没有投票权；
+ 赎回投票质押的Token，需要等待3天冻结期。赎回开始时刻即停止发放收益；
+ 修改投票需要先进行赎回操作，等待3天冻结期后方可改投。
  
**2、IOST赎回规则**

在进行撤票操作时，既可以撤销对一个节点的所有投票，也可以撤销部分投票，执行撤票操作后，需要3天才能够赎回投票中的 IOST。另外，如果要修改投票，也需要先撤票，等待3天后再重新投票。

**3、IOST投票奖励规则**

投票者将获得其所投节点合伙人的当选奖励和生态贡献奖励的50%作为分红，不参与造块奖励与其他奖励的分红。其中，当选奖励每天发放，贡献奖励每季度（3个月）发放一次。

投票者将获得其所投节点合伙人的当选奖励和生态贡献奖励的50%作为分红，不参与造块奖励与其他奖励的分红。其中，当选奖励每天发放，贡献奖励每季度（3个月）发放一次。

**4、多种投票方式**

+ 通过IOST钱包投票

在IOST钱包的投票页面选择要投票的节点，点击后面的"投票"按钮，并输入参与投票的 IOST 数量就可以进行投票了。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860271960.png "IOST钱包")

+ 通过IOSTABC区块浏览器投票

在IOSTABC的"节点投票"页面中选择要投票的节点，然后点击"投票给他"按钮就可以完成投票了。
![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860560351.png "IOST钱包")

+ 通过IOST投票宝投票
+ 
IOST 投票宝是由 IOST 节点合伙人 —— 猎币开发的 IOST 链上投票与分红领取工具，可以对比节点分红收益，一键领取每日分红等。

IOST投票宝作为一个H5（HTML5）型态的产品，用户可以借助钱包的DApp浏览器直接 进入投票宝并登录IOST账号，进行 IOST 节点的投票、领取收益以及赎回等操作。

投票宝支持"一键复投"，即把最新分红的IOST，再次投票给发放分红的节点，从而达到复利的效果。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860618067.png "IOST钱包")

+ 特殊的投票玩法——矿池
+ 
矿池是基于PoS建立的一种理财机制，用户使用IOST Token可以在矿池进行挖矿。

**猎币IOST矿池** 

在猎币 IOST 矿池中，挖矿的过程是将 IOST 兑换成 VOST（矿权）的过程，1 VOST = 1 IOST，兑换成功即开始计算挖矿收益。 挖矿收益将通过矿权的形式每日结算一次，结算后账号所持有的矿权总量增加，所以挖矿收益也相应增加，达到复利的效果。

与普通节点投票赎回不同的是，猎币矿池赎回的过程就是停止挖矿的过程，也就是将 VOST（矿权）赎回成 IOST，VOST（矿权）可以随时赎回。在赎回时，既可以按正常流程赎回（3天等待期），也可以使用闪电赎回，闪电赎回立即到账，但要收取一定的费用。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589860981218.png "IOST钱包")

**火币IOST矿池**

火币IOST矿池挖矿的过程是将 IOST 兑换成 HPT（火币矿池的权益证明）的过程，HPT是火币矿池的权益证明，持有HPT可深度参与火币矿池的生态建设以及获得权益派发，通过数字资产锁仓、投票、POW算力接入可进行HPT挖矿，通过火币矿池给 IOST 节点投票属于 HPT 挖矿中的投票挖矿。

在火币矿池进行投票挖矿前，需要把火币网币币账户中的 IOST 划转到矿池账户中，然后在IOST投票挖矿页面给节点进行投票。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589888981918.png "IOST钱包")

### IOST 节点合伙人

作为IOST持币者，我们需要了解各个IOST节点合伙人情况以及IOST节点合伙人运作机制。

**1、 IOST节点合伙人机制介绍**

有志于成为IOST合伙人的个人或团队，只需填写合伙人申请表，即可成为候选人。节点合伙人申请表<br/>
<div align="left">
    <img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589861261180.png">
</div>

只要获得210万票(1 IOST=1 票) 即可当选；无硬性技术要求，IOST将提供全方位技术支持；出块节点合伙人需满足最低1000万票的要求。

获票数不低于210万即可成为节点合伙人，所有节点合伙人一年共享总发行量4%（840,000,000 IOST）的节点合伙人奖励。其中25%为当选奖励，25%为出块奖励，50%为贡献奖励。

**2、认识IOST节点合伙人**

我们可在 IOST ABC区块浏览器查询 IOST 各个投票节点合伙人详细信息，可以查看节点合伙人名称、得票、年化利率以及出块数量等。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589861354839.png "IOST钱包")

此外，我们还可以通过关注每个季度IOST节点合伙人贡献评级排名，来判断我们应该投给哪些真正为IOST社区贡献且投票奖励较高的节点合伙人。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589889570981.png "IOST钱包")
<center>部分优秀IOST节点合伙人展示</center>

### 发行基于IOST公链的代币（Token）

任何人都可以在 IOST 主网上发行代币，在 IOST 发币非常简单，由节点合伙人 IOST TOOL 开发的一键发币工具可以帮助我们在 IOST 公链上发行自己的代币。

**1、通过TOKENPocket 发币**

在TP  钱包【发现】 IOST 专区找到 IOST一键发币应用并打开。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589861498803.png "IOST钱包")

输入要发行的Token名称、Token说明、发行数量和精度，输入完 Token 的参数后点击"创建"，提示成功后再点击"发行"。

需要注意的是，发币需要消耗 IOST 资源，在发币前需要账户里边有足够数量的 iRAM 资源。

**2、通过 IOST Tool 网站发币**

使用 IOST Tool 网站发币前，需要先下载iWallet插件钱包并安装，登录 iWallet 钱包后，在 "一键发Token" 网站 http://www.iosttool.com/ 中依次输入Token名称、发行量、精度、通证说明这4个关键参数，就可以发行你的个人Token啦！

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589861584335.png "IOST钱包")

在 IOST 发行完代币后，在 IOST 区块浏览器（例如IOSTABC）就可以查询到该代币，例如会显示发币者、通证名称、通证说明以及持有人数等。如果你希望能在钱包中管理自己发行的Token，你需要向各个IOST钱包申请Token收录。

### IOST Token 相关

**1、如何获得 IOST Token**

通过交易所交易、币币闪兑、法币购买这三种方式，用户可以很方便的获得IOST Token。

交易所交易

目前支持 IOST 的交易所有包括币安、火币、OKEx 等在内的100多家交易所（来源于非小号数据），在这些交易所我们都可以通过交易获得IOST Token。

如果想要获得更低成本的IOST Token，获得更好的交易深度，可以考虑到聚合交易所交易。以TP交易所为例，仅需一个账号，即可实现在币安、火币、OKEx三大交易所进行挂单交易，更好的掌握市场变化，更好的实现不同交易所之间的IOST价差收益。

币币闪兑

闪兑顾名思义就是闪电兑换，即可以通过其它 Token 来快速兑换 IOST，闪兑不同于一般交易所的订单撮合模式，它更像银行柜台模式，因此交易速度更快，几乎是实时完成兑换的。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589861688587.png "IOST钱包")

**法币购买**<br/>

在 TokenPocket 中通过币买卖直接使用法币买入IOST Token，购买完成后的IOST 将会直接转入你的IOST账号。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589861771719.png "IOST钱包")

### 如何进行IOST转账

(1）IOST转账需要消耗资源

IOST 账号在转账前，需要先保证账号内有足够的 IOST 资源，IOST 资源包括 iRAM 和 iGAS，iRAM 资源需要账号使用 IOST 来购买，iGAS 需要账号抵押 IOST 来获取。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589888249390.png "IOST钱包")

(2）三种不同的转账操作

+ 普通转账（IOST账号互转）

普通转账指的是独立的IOST账号之间的转账，普通转账并不需要输入 memo 信息，只需输入接收方IOST账号以及转账数量。

+ 从交易所账号转账到IOST账号（钱包账号）

从交易所转账到 IOST账号（钱包账号）即从交易所把 IOST 提币出来，提到自己独立的 IOST 账号中，是不需要填写 memo 信息的。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862003957.png "IOST钱包")

例如，在火币网提币 IOST 时，只需输入提币地址（IOST 钱包账号）、提币数量，不需要输入 memo 信息（选择不填或填写任意内容皆可）。

+ 从IOST账号（钱包账号）转账到交易所账号

需要注意的是，因为创建 IOST 账号需要付费，所以交易所的 IOST 充币地址是一样的，交易所是通过memo来识别不同用户的，所以往交易所充币 IOST，memo信息一定要按照交易所要求正确填写。

例如，在往火币交易所充值 IOST 时，除了转账数量和接收账号外，memo 也是需要输入的，即火币充值地址中显示的地址标签（用于区分不同的火币用户），否则可能不会到账。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862094005.png "IOST钱包")

(3）丰富便捷的转账形式

为了更好的方便用户进行转账收款操作，IOST钱包提供直接转账、地址簿转账和扫码转账等多种形式满足用户不同的需求。

[](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589888371174.png "IOST钱包")

直接转账：输入收款账号、转账数量以及 memo 后，点击"确认"即可完成 IOST 的转账。

地址簿转账：地址簿就像我们手机中的电话簿，创建完地址簿后，如果要转账就可以到地址簿中选择相应的收款 IOST 账号。如果你经常向某个IOST地址转账，可以将该地址添加到钱包的地址薄，在转账的时候可以直接选择地址薄转账，这样不仅省时，还可以避免出现地址填错的安全问题。

扫码转账：类似微信、支付宝二维码收付款，通过扫描收款二维码，即可向指定账号转账。

另外，还可以通过最近转账功能进行转账，点击"最近转账"后，就会在转账界面中自动填充该 IOST 地址，如果经常向一个 IOST 账号进行转账时，使用该功能就比较方便。

总之，无论是地址簿转账，还是扫码转账以及通过最近转账交易记录转账，都可以在一定程度上防止由于手动输入账号错误所造成的不必要的损失。

### 如何收款 IOST

收款 IOST Token 也是在钱包内完成的，在收款时把 IOST 账号发给对方，或者把 IOST 账号的二维码发给对方，然后由对方完成转账操作。

**持有IOSTToken可以做什么**

1、持有 IOST Token，可以进行转账和 IOST 节点投票

通过 IOST 钱包进行转账和收款是最常用的功能了，另外，持有 IOST 还可以给 IOST 节点投票，参与 IOST 节点投票，不但可以领取投票收益，还有利于 IOST 生态建设。

2、体验 IOST DApp

持有 IOST Token，可以体验 IOST 生态中的 DApp，IOST Token相当于体验DApp的门票。通过支持IOST DApp的钱包浏览器，可以很方便的进行DApp体验。当前IOST主链上发行的游戏超过60款，游戏类型丰富，喜欢宠物养成与卡牌策略的可以选择XPET怪兽世界，饲养自己的区块链萌宠；喜欢三国题材的可以选择IOST加密三国志，攻略城池赚取分红。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862346198.png "IOST钱包")

3、在中心化与去中心化交易所进行交易

持有 IOST Token 可以到 IOST 首家去中心化交易所 IOSTDEX 进行相关 IOST 资产的交易，也可以在支持IOST 的中心化交易所交易。

## IOST钱包使用场景

除上述提及的使用功能外，IOST钱包还为IOST持币者提供了更多便捷的账号管理与其他功能。以TokenPocket钱包为例，常见的功能还有IOST资产归集、白名单、权限管理、使用IOST浏览器、调整钱包排序、浏览IOST相关资讯。

### IOST资产归集 

资产归集是将某种资产全部转移到指定账号中的功能，此功能可以将你所有IOST账号的资产转账到一个账号，可以手动选择想要进行归集的IOST账号和被归集的账号。归集操作本质上是一次或多次转账，需要一定时间等待区块确认。被归集的账号越多，归集过程花费的时间也越长。归集操作中的某些转账有可能因为区块链网络无法确认而失败。失败的转账不会影响已经成功的转账，也不会导致资产的损失，可以在网络稳定后尝试再次进行归集。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589888539170.png "IOST钱包")

### IOST白名单 
DApp白名单就是对某一款DApp进行信任授权，将特定的合约操作加入白名单，之后相同操作将不再需要二次确认。我们在玩DApp的过程中经常需要与合约做交互，每一次的交互都需要授权一次，要高频操作每次都要重复授权，体验非常差。勾选属性旁边的单选按钮意味着您允许此操作的该属性可以更改，仅当其他属性发生变化才不会被列入白名单。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862518623.png "IOST钱包")

### 权限管理

每个IOST账号都有与之关联的密匙，而每个秘钥都有对应的权限，并且每个权限都有相应的权重，交易均需要在满足权限的情况下进行。IOST的账户体系允许用户对账号进行权限管理，默认情况下，一个IOST账户有2个权限：拥有者权限（owner）和管理者权限（active）

Owner:代表对账户的所有权，可以管理Active和其他角色。改变账户所有权需要该权限的许可。

Active：用于日常使用，如转账、节点投票，及其他高级别账户变动。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862628453.png "IOST钱包")

TokenPocket钱包在原有权限管理的基础上，新增可添加、删除、变更多个拥有者/管理者权限，目的是为了满足一些用户对于账号权限多点分配的需求。通过该功能可以新增/更改IOST账号的权限，进而更改账号的秘钥，操作过程中要注意在用秘钥生成器生成新的公钥和私钥时一定要把私钥保存好，钱包默认的权重阈值为100且不可更改。

注：该功能属于高级功能，一定要合理分配好自己的权限，同时防止私钥等泄露。

### 使用IOST浏览器

区块链浏览器是浏览区块链信息的主要窗口，每一个区块所记载的内容都可以从区块链浏览器上进行查阅。目前常用的IOST浏览器有ABC浏览器https://www.IOSTabc.com/和极简浏览器https://explorer.IOST.io/

使用IOST浏览器可以查询IOST全网的基础数据:最新区块、交易数量、账户数量、代币数量等；查询账户信息:交易信息、Token余额和抵押信息等；查询节点数据:节点排行、得票率、出块数量等。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862689325.png "IOST钱包")


### 调整钱包排序 

很多用户会有多个IOST账号，钱包排序功能通过对账号拖拉可以轻松调整钱包账号顺序，用户可以把经常使用的账号放在C位，更方便日常钱包切换与资产管理。

### 浏览IOST相关资讯 

作为IOST 生态用户，可以在钱包中便捷的浏览到IOST的最新价格变化、快讯、文章。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862776352.png "IOST钱包")

## IOST开发者与钱包

IOST作为新一代的高性能公有区块链，拥有拓展性强、稳定的基础架构，凭借其优秀的底层技术和良好的开发者支持，一直吸引着众多开发者来到IOST生态作出贡献，但开发者们没有太多开发工具来使用，加上对公链的了解不深，因此开发者在区块链上的开发往往比传统开发要难的多。<br/>
作为大量DApp流量的入口，钱包的职责不仅要帮助用户来体验DApp，还要帮助DApp来获得用户，钱包不仅要服务好用户、公链，还要赋能给开发者。因此，钱包会提供一些开发者工具来支持IOST开发者们。

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589862843129.png "IOST钱包")

以TokenPocket钱包为例，TP钱包为IOST开发者提供Android和iOS移动SDK，开发人员可用SDK唤起TP钱包进行钱包账号的授权登陆，执行合约操作等。TP钱包内部Webview 兼容 IOST 的 iwallet 协议标准，可以直接在钱包内Dapp浏览器内输入URL即可开发测试基于IOST开发的各种DAPP，实现在TP钱包内Dapp浏览器内唤起授权签名等操作。<br/>
总之，IOST因其良好的性能和极低的Gas消耗费用，为更精良的DApp的产生和大规模使用提供了可能。而钱包服务与IOST开发者，提供开发帮助和用户，二者共同为更好的应用级公链作出自己的贡献。<br/>
SDK链接：https://github.com/TP-Lab/TokenPocket-Protocol

## IOST钱包分类

+ 去中心化钱包：<br/>
  <main class="tp-main">

    <a class="tp-custom tp-customs" href="https://www.Tokenpocket.pro" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894459599.png"/>
        <div class="tp-content">
            <h5>TokenPocket</h5>
            <p>https://www.Tokenpocket.pro</p>
        </div>
    </a>
    <a class="tp-custom tp-customs" href="https://cobo.com" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894579177.png"/>
        <div class="tp-content">
            <h5>Cobo</h5>
            <p>https://cobo.com</p>
        </div>
    </a>
    <a class="tp-custom tp-customs" href="http://purewallet.org" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894636963.png"/>
        <div class="tp-content">
            <h5>PureWallet</h5>
            <p>http://purewallet.org</p>
        </div>
    </a>
    <a class="tp-custom tp-customs" href="https://www.huobiwallet.com" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894692897.png"/>
        <div class="tp-content">
            <h5>火币钱包</h5>
            <p>https://www.huobiwallet.com</p>
        </div>
    </a>
     <a class="tp-custom tp-customs" href="https://app.bepal.pro/" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894736327.png"/>
        <div class="tp-content">
            <h5>Bepal</h5>
            <p>https://app.bepal.pro/</p>
        </div>
    </a>
     <a class="tp-custom tp-customs" href="https://www.starteos.io" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894808120.png"/>
        <div class="tp-content">
            <h5>Starteos</h5>
            <p>https://www.starteos.io</p>
        </div>
    </a>
     <a class="tp-custom tp-customs" href="https://www.infinitowallet.io" target="_blank">
        <img class="tp-logo" src="hhttps://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894847574.png"/>
        <div class="tp-content">
            <h5>Infinito</h5>
            <p>https://www.infinitowallet.io</p>
        </div>
    </a>
    <a class="tp-custom tp-customs" href="https://bigfour.io" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894904243.png/>
        <div class="tp-content">
            <h5>BigFour</h5>
            <p>https://bigfour.io</p>
        </div>
    </a>
</main>
    <!-- TokenPocket：https://www.Tokenpocket.pro<br/>
    Cobo：https://cobo.com<br/>
    PureWallet：http://purewallet.org<br/>
    火币钱包：https://www.huobiwallet.com<br/>
    Bepal：https://app.bepal.pro/<br/>
    Starteos：https://www.starteos.io<br/>
    Infinito：https://www.infinitowallet.io<br/>
    BigFour：https://bigfour.io<br/> -->
+ 硬件钱包<br/>
+ <main class="tp-main">

    <a class="tp-custom tp-customs" href="https://www.coldlar.com" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589894978000.png"/>
        <div class="tp-content">
            <h5>库神</h5>
            <p>https://www.coldlar.com</p>
        </div>
    </a>
</main>
    <!-- 库神：https://www.coldlar.com<br/> -->
+ 插件钱包<br/>
  <main class="tp-main">

    <a class="tp-custom tp-customs" href="https://chrome.google.com/webstore/detail/kncchdigobghenbbaddojjnnaogfppfj" target="_blank">
        <img class="tp-logo" src="https://chrome.google.com/webstore/detail/kncchdigobghenbbaddojjnnaogfppfj"/>
        <div class="tp-content">
            <h5>iWallet</h5>
            <p>https://chrome.google.com/webstore/detail/kncchdigobghenbbaddojjnnaogfppfj</p>
        </div>
    </a>
    <a class="tp-custom tp-customs" href="https://chrome.google.com/webstore/detail/jetstream/ijancdlmlahmfgcimhocmpibadokcdfc" target="_blank">
        <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589895063706.png"/>
        <div class="tp-content">
            <h5>Jetstream</h5>
            <p>https://chrome.google.com/webstore/detail/jetstream/ijancdlmlahmfgcimhocmpibadokcdfc</p>
        </div>
    </a>
</main>
    <!-- iWallet——<br/>
    https://chrome.google.com/webstore/detail/kncchdigobghenbbaddojjnnaogfppfj<br/>
    Jetstream——<br/>
    https://chrome.google.com/webstore/detail/jetstream/ijancdlmlahmfgcimhocmpibadokcdfc<br/> -->

## IOST钱包知识自测

<div align="left">
    <img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589863134106.png">
</div>


## IOST钱包常见问题

<div align="left">
    <img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589863201176.png">
</div>


## IOST联系方式
<main class="tp-main">

<div class="tp-custom icon contact">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589869384860.png"/>
    <div class="tp-content">
        <p>IOST官网：iost.io</p>
    </div>
</div>

<div class="tp-custom icon contact">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589870220254.png"/>
    <div class="tp-content">
        <p>微博：IOST社区</p>
    </div>
</div>

<div class="tp-custom icon contact">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589870346059.png"/>
    <div class="tp-content">
        <p>Twitter:  twitter.com/iosToken</p>
    </div>
</div>

<div class="tp-custom icon contact">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589870407994.png"/>
    <div class="tp-content">
        <p>Telegram:  t.me/iostchinese</p>
    </div>
</div>

<div class="tp-custom icon contact">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589870450791.png"/>
    <div class="tp-content">
        <p>GitHub: https://github.com/iost-official</p>
    </div>
</div>

<div class="tp-custom icon contact">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589870503428.png"/>
    <div class="tp-content">
        <p>Medium: medium.com/iost</p>
    </div>
</div>

<div class="tp-custom icon contact">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589870585429.png"/>
    <div class="tp-content">
        <p>Zendesk iost.zendesk.com</p>
    </div>
</div>
</main>

![](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1589863338679.png "IOST钱包")

微信群：

## 版权申明

《从0到1入门IOST钱包》，又称为IOST钱包小白书。由TokenPocket联合IOST官方，以及TokenPocket社区志愿者（TP侠：阿华、马云儿）共同撰写，详细介绍了当前IOST钱包与IOST生态密切结合的实例，是目前市面上最为详细的IOST数字钱包科普资料。<br/>

1.本文版权归TokenPocket所有。<br/>
2.在征得作者同意的情况下，作品允许非盈利性引用，需要注明并请注明出处和作者，以尊重作者的劳动成果。<br/>
3.出处：https://tp-lab.github.io/BlockchainGuide-IOST/#/<br/>
作者：TokenPocket。<br/>
4.未经允许，严禁转载。对非法转载者，TokenPocket和作/译者保留采用法律手段追究的权利。<br/>
5.对于本文和本声明以及其修改权、更新权及最终解释权均属TokenPocket。<br/>
6.以上声明的解释权归“TokenPocket”所有。<br/>



    



































