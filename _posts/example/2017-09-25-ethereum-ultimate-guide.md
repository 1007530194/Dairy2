---

layout: post
title: 为什么以太坊不仅仅是一个加密货币
tag: Ethereum
categories: example
published: true

---

尽管比特币（Bitcoin）和以太坊（Ethereum）是经常被一起提及的两个词，但实际上，比特币与以太坊有着很大的区别。它们唯一的共同点是，以太坊也是一个在区块链之上运行的加密资产。

与比特币仅仅是一个加密货币不同，以太坊还有很多其他特性。正是这些特性，才使得以太坊成为了一个去中心化的超级电脑。

在理解 [以太坊](https://www.ethereum.org/) 之前，我们必须要理解区块链是如何工作的。如果你已经了解了区块链，或者读过 [理解区块链终极指南](https://hackernoon.com/wtf-is-the-blockchain-1da89ba19348)，可以直接进入下一节。

## 什么是区块链？

**简单点说，区块链就是一个数据库**。它是一个不断增长的数据库，里面存储着特定类型的数据，并且有着一些独特的属性：

1. 一旦数据被存储到数据库中，它就永远也无法再被修改或是删除。区块链上的每一条记录都是永久存在的。
2. 这个数据库，并不是由一个单一的个人或是组织维护，而是由成千上万的人在共同维护，其中的每个人都有着一份数据库的拷贝。

为了理解为什么几个人能够持有一份拷贝，并且能够与其他人进行同步，让我们来假设现在网络里面有 10 个人，每个人的面前都有一个空的文件夹，并且有着一页空的纸。无论何时，网络中任何一个人做了一些事情，比如转账，他们必须要将这件事告诉网络里面的其他人。


![ten individuals](http://upload-images.jianshu.io/upload_images/127313-8a9f6e9d2e0da178.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

每个人都会在纸上记录这件事，直到填满这张纸。这个时候，每个人都必须通过解决一个数学难题来封装这页纸。通过解决数学难题，保证了每个人手中的纸都有着同样的内容，并且无法被修改。谁第一个解出了题，谁就会得到一定数量的加密货币的奖励。更多内容可见：[the ultimate guide to understand blockchain](https://hackernoon.com/wtf-is-the-blockchain-1da89ba19348).

一旦封装完毕，这一页就会被加到文件夹里面，然后拿出新的一页，继续重复上述过程。

![blockchain](http://upload-images.jianshu.io/upload_images/127313-eaedc1ec1b63bb36.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

随着时间不断增长，这些包含了重要记录（也就是交易，transaction）的页（也就是区块，block）不断地被加入到文件夹（链）里面，最终形成了数据库（区块链）。

## 区块链存储了什么？

**区块链可以用于存储各种类型的数据**，它所存储的数据，赋予了区块链价值。比特币区块链存储的是金融交易，因此，看起来像是美元或者英镑这样的货币。除了跟美元所承载的功能以外，比特币没有任何额外的功能。但是，以太坊则不同。

以太坊不仅仅是一个像美元，英镑或者比特币一样的货币。以太坊的目标不仅是成为一个货币，更是成为下图中的事物：

![Ethereum](http://upload-images.jianshu.io/upload_images/127313-bbeda1d6c5b0d786.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

以太坊实际是一个巨型电脑！但是，它是一个非常慢的电脑 -- 大概比今天的普通电脑慢上 100 倍，并且非常昂贵。“以太坊电脑” 有着跟 [90 年代智能手机](http://www.businessinsider.in/The-worlds-first-smartphone-Simon-was-created-15-years-before-the-iPhone/articleshow/47665223.cms) 类似的境遇。除了一些非常简单的事情以外，它几乎做不了任何事情。

这听起来好像并不怎么吸引人，那么，为什么以太坊还有这么多人趋之若鹜呢？这是一个非常好的问题。不夸张的说，以太坊正在席卷整个世界，因为它是一个完全去中心化的电脑，分布在世界各地。理解以太坊区块链是如何工作的，就会看出它是如何承担了一个世界电脑的角色。

## 以太坊是如何工作的？

与其他所有的区块链一样，以太坊需要数以千计的人在他们的个人电脑上运行一个软件来支撑整个网络。网络中的每个节点（电脑），运行一个叫做以太坊虚拟机（Ethereum Virtual Machine, EVM）的东西。可以把 EVM 想象成是一个操作系统，它能够理解并且执行用以太坊上特定的编程语言编写的软件。由 EVM 所执行的软件或者应用叫做 “智能合约（Smart Contract）”。

为了在这台世界电脑上做一些事情，你需要进行付出一定的费用。但是，你并不是付美元或者英镑这样普通的货币。而是通过叫做以太（ether，ETH）的以太坊网络原生的加密货币，来支付相关费用。以太跟比特币几乎一模一样，唯一不同的是它被用于支付在以太坊上执行智能合约的费用。

无论是一个人，还是一个智能合约，都被视作为以太坊上的用户（user）。一个人可以以太坊上做什么，一个智能合约就可以做什么。

![human user and smart contract](http://upload-images.jianshu.io/upload_images/127313-533795e468784395.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

智能合约看起来就跟网络的其他任何人一样。它们都可以发送或者是接收以太，就跟其他的货币一样。

![smart contract](http://upload-images.jianshu.io/upload_images/127313-c469ec5c5cfc4d07.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

但是智能合约又不是完全跟人类相同。跟人类用户不同的是，智能合约也可以执行一个预先定义好的计算机程序来执行各种操作，执行的操作可以根据事件进行触发。为了感受一下智能合约的威力，让我们来考虑一个例子：

## 智能合约的威力

假设你和我对明天的天气进行打赌，我打赌明天是晴天，但是你打赌是雨天。双方同意输的一方必须给赢的一方 100 美元。那么，我们如何才能够做到这一点，并且确保输的一方不会耍赖呢？我可以想到三种不同的方式：

### 1. 信任对方

最简单的方式是信任对方。如果我们是老朋友了，那么信任对方是非常容易的。我知道你住哪儿，你也知道关于我的各种糗事。但是如果我们是完全不认识的陌生人，事情就会变得复杂的多。我没有理由去信任你，你也没有理由去信任我。

### 2. 签一个法律协议

另一个貌似可行的方案是，将我们的赌约正式形成一个有法律效力协议。我们双方签署一个定义了赌约所有细节的协议 -- 包括如果输的一方违反协议会怎样。

这个协议将会使得我们有义务付给赢的一方，但是它没有任何实用性，因为通过合法途径强制协议执行的成本，要比这个赌约的价值高得多。

### 3. 请一个共同的朋友帮忙

我们可以找一个双方都信得过的朋友，然后各给这个朋友 100 美元进行保管。第二天，他会检查天气，然后把全部的 200 美元给打赌赢的一方。非常简单和方便，除了有一点：如果这个双方都信任的朋友把钱卷走了怎么办？

现在，我们有了三种不同的方案来实施赌约，但是每种方案都有缺点：

- 因为是陌生人，所以我们无法信任彼此。
- 强制执行一个协议是如此的昂贵，以至于不具有任何实用性。
- 求助一个共同的朋友同样又会遇到信任的问题。

以太坊的智能合约就是为了解救这个问题。一个智能合约就像是可信赖的共同的朋友，只不过是用代码写的而已。我们可以在以太坊上写一个合约，这个合约从我们双方获得 100 美元的输入，然后在第二天，通过开放的天气 API 来检查天气，并将所有的以太转给赢的一方。

![smart contract](http://upload-images.jianshu.io/upload_images/127313-ff3ff86df9bf269b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

一个合约写好以后，就无法再被编辑或者修改。因此，你可以保证无论合约的内容是什么，它都会无条件执行。

但是，智能合约是如何执行？跟区块链又有什么关系呢？

## 智能合约是如何与区块链关联的？

无论智能合约何时被执行，它都会在一个区块上被记录为一个交易。概括来讲，一笔以太坊上的交易看起来就像是这样：

![image.png](http://upload-images.jianshu.io/upload_images/127313-21f58ba2fb5f9a52.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

除了最后的 `Data`，其他字段相信大家一眼就能看出来是干什么的。也正是这个 `data` 字段，才使得以太坊与众不同。`data` 用于记录智能合约的创建和执行，就像记录交易一样。在以太坊区块链上，任何一个块都可能包含以下三种交易：

### 1. 从一个人转移到另一个人的普通交易

这些普通交易，就像是比特币交易。如果你直接发送以太给你的朋友，那么 data 字段就是空的，这样的交易就是普通交易。

![transfer from one user to a human user](http://upload-images.jianshu.io/upload_images/127313-dd00cf4d2747e7f9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 2. 只有发送方却没有接收方

如果一笔交易中没有接收方，这意味着此次交易是用 `data` 字段的内容在网络中创建一个智能合约。`data` 字段包含了代码，这些代码就像是网络中的其他用户一样。

![transfers of ether from one user to no one](http://upload-images.jianshu.io/upload_images/127313-5b3c6248875f228a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 3. 将以太转到一个智能合约

无论何时，只要一个用户（或是一个智能合约）想要执行一个智能合约，他/她/它 都会创建一个智能合约的交易，并在 `data` 字段放置执行指令。

![transfers of ether from a user to a smart contract](http://upload-images.jianshu.io/upload_images/127313-48bb6da99a09c6c4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

与其他区块链一样，无论上面提到的三种事件何时发生，都会被公布到网络中，并且网络中的每个人都会对它进行记录。除了记录，每个节点还会执行智能合约，来使得他们的 EVM 状态与网络的其他部分同步。

每个节点都执行软件的一部分，因此，使得整个网络像一个巨大（但是缓慢）的分布式电脑。每次无论多么小的执行，都会被记录到区块链上，永久存在。

## 等一下，Gas 是什么东西？

如果用户想要使用和执行智能合约，就必须要为执行该智能合约付出一定费用。这笔费用是给了实际花费了内存，存储，计算和电力等资源来执行合约的节点。

为了计算智能合约的费用，合约中的每条语句都有收费标准。比如，如果执行的语句用到了节点的内存，这个语句会有一个价格。如果执行一个语句用到了节点的硬盘存储，这些语句又是另一个价格。在这里，定义成本的单位就叫做 Gas。最终，Gas 会通过汇率转换成以太（ETH）。

无论何时执行一个智能合约，你都必须要定义一个可以花费的 Gas 的最大值。当智能合约执行完成，或是达到了 Gas 的限额，就会停止执行。这是为了避免在智能合约中出现无限循环，防止出现一些反复执行的语句导致程序停滞。

因为程序员的一些错误，很可能会导致这样的事情发生。所以每次重复执行时，都会消耗掉一些分配的 Gas，因此使得不会出现无限循环这样的事情。没有必要因为程序员的错误，导致一个节点在执行时崩溃。使用 Gas 就解决了这个问题。

## 这就是以太坊

以太坊不仅仅是一个用于交易的加密货币，它的实际价值在于其目的 -- 以太坊的目的，是为了让人们使用由几千个节点支撑的分布式世界电脑。

当然，由于每条语句必须被网络的中每个节点所执行，去中心化的分布式电脑会变得很慢，而且很贵。不过，这里所说的慢是跟谁相比较呢？是跟更快，但是由中心化控制的服务器。

为了能够享受中心化电脑带来的低成本，我们交出了我们的控制权。但是如果中心化服务器宕机或是被黑客攻击，那么所有与它连接的客户端都会挂掉。而一个去中心化的分布式电脑，只有在每个节点都停止工作的情况下，才会挂掉。换句话说，这使得它永远不会宕机。无论在哪里，只要有网络，就有以太坊。

原文：
[WTF is Ethereum?
The ultimate guide to understand why Ethereum is not just another cryptocurrency.](https://hackernoon.com/wtf-is-ethereum-c65e0d67ac09)