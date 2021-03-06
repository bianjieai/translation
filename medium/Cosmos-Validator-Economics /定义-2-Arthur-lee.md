### 光子

Cosmos 网络当前计划的提案是[引进一个第二令牌](https://blog.cosmos.network/cosmos-fee-token-introducing-the-photon-8a62b2f51aa)，目的是补充原生的权益令牌atom，用来在网络中支付费用。这样做的想法是通过引进一个第二费用令牌，现在暂且叫它“光子(Photon)”,因为它降低了atom的流动性，进而使得网络的安全性得以加强。推理的过程是这样的降低atom的流动性使得一个攻击者在网络中获得足够大量的权益来发动攻击变得更加困难。使用atom作为权益证明的意图被基于前面描述过的使用过权益的atom的总数来动态的通胀atom的供给的做法进一步的激励了。以这种方式铸造的atom被分发给冒险下注他们的atom的验证者和授权者，在过程中有效的降低没有冒险下注的atom的价值。光子(photon)作为第二令牌[被设计的具有高流动性，并且具有通胀率逐渐地达到0的特征](https://drive.google.com/file/d/1jtyYtx7t1xy9gxEi2T5lXFNd8xUY7bhJ/view)。新产生的光字(photon)将被分配给验证者和授权者来作为它们做出的贡献的奖励。验证者将会在这些奖励中抽取佣金。在写作的时候，是否Cosmos 网络会在初创时上线光字(photon)仍然是一个未定的需要通过在Cosmos Hub上投票来解决的问题。

### 硬勺子(hard spoon:将一个已经存在的区块链上的状态信息，如令牌余额，复制到另一个区块链上。两者不互相竞争，而是为了提供更广阔的访问)

光子(photon)很可能通过一个硬勺子(hard spoon)使用一次在以太坊的某个区块高度的状态快照被分配给atom和/或者ether的持有者,硬勺子(hard spoon)可以比得上一次空投。这个操作可以通过在Cosmos 网络中专门为声明光子(photon)创造一个区域来实现。这个区域镜像了ether持有者的账户余额，然后将它传递到其他区域中(例如：Ethermint 区域)来支付在其他区域中的交易费用。硬勺子(hard spoon)的过程在[官方介绍的博客公告](https://blog.cosmos.network/introducing-the-hard-spoon-4a9288d3f0df)中被详细的解释了。硬勺子(hard spoon)的目的是刺激ether的用户迁移到Cosmos网络中来从更高的网络性能中获益。硬勺子(hard spoon)的相关参数计划由一个管理投票来决定，[在这个投票中硬勺子(hard spoon)的形式将被决定，如光子(photon)在ether持有者和atom持有者中怎么分配和它的通胀率](https://cosmos.network/staking)。关于硬勺子(hard spoon)将会被怎么样执行和会有什么样的关于光子的经济参数的核心问题会在主网上线后被确定。

### 佣金率

为了鼓励经营一个验证者而不是仅仅授权atom给唯一一个验证者，验证者们将可以为他们提供的服务收取佣金。验证者们可以自己选择设定一个佣金率，例如15%，这个佣金率默认被统一地应用于所有的费用和区块奖励(比如：atoms和photons)。进而，产生的收入的85%将会给授权者，而剩下的15%将会因验证者提供的服务而被其持有。验证者可以在特性、安全和佣金率等方面竞争。同时，授权者可以选择在出价、服务和安全阀值方面最适合他的验证者。

验证者可以在以atom、photons来支付的区块奖励中和来自白名单的令牌的交易费用中收取某个可以变化的佣金率。目前为止，默认的模式是对atom和photon的区块奖励，以及交易费用采取单一佣金率。然而，如果社区选择在以后将这个设置换成针对每一个费用令牌的变化的佣金率，社区可以通过管理来完成这一目标。

### 白名单令牌

为了补充两个Cosmos令牌，atom和photon,等到其他令牌在Cosmos Hub上面可以使用后，计划将其他加密货币(例如：比特币和以太币)加入白名单来在网络上面支付交易费用。哪个令牌将会被接受会通过管理投票的方式来决定。[令牌模型文件](https://github.com/cosmos/cosmos/blob/master/Cosmos_Token_Model.pdf)详细讲述了这些将来可能发生的事情。通过验证者自己对每个令牌的估价是多少来决定，是否被列入白名单的令牌可以被接受作为费用的报酬。