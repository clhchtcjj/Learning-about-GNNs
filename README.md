## 图神经网络(Graph Neural Networks, GNNs)

GNNs是专用于处理图数据的神经网络模型。综述 《[Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/abs/1812.08434)》将这一技术大致分为三大类：基于半监督的方法：图卷积网络；基于无监督的方法：图自编码器；近期新的研究方法：图循环神经网络和图强化学习。

下面就个人的学习轨迹做一个简单的记录。



## 1 基于半监督的方法

### 1.1 图卷积神经网络 (GraphConvolutional Network, GCN)

**图卷积神经网络 **是由Thomas Kpif 在2017年在 [Semi-supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907) 论文中首次提出。它是一种利用end-to-end训练方法学习Graph Embedding的技术。

### Day 1- Day 3:

|   Type   |                  Title                   |                 Tutorial                 |
| :------: | :--------------------------------------: | :--------------------------------------: |
|  Paper   | [Semi-supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907) | [从CNN到GCN的联系与区别——GCN从入门到精（fang）通（qi）](https://www.zhihu.com/question/54504471/answer/332657604),[图卷积网络(GCN)新手村完全指南](https://zhuanlan.zhihu.com/p/54505069)|
|   Code   |      <https://github.com/tkipf/gcn>      | [GCN代码分析](https://www.jianshu.com/p/ad528c40a08f) |
| practice |       https://github.com/tkipf/gcn       | [GCN实践——可视化cora-network](https://www.jianshu.com/p/47425c02d779) |



