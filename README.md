bridge 去中心化跨链桥
每个公链部署一个跨链桥，以及对于的跨链资产合约。

跨链流程
跨链流程：例如qki主网的a token，跨链到heco主网，先在qki主网跨链桥转入a，然后跨链验证节点在heco主网给同一个地址mint出相等数量的a。

取回流程：在heco主网把a token存入跨链桥并销毁，然后跨链验证节点在qki主网给同一个地址转账相等数量的a。