# [DAGX | 基于DAG的价值互联与交换网络](http://dagx.io "dagx官网")

DAGX Networks 是基于 DAG 技术开发的价值交换网络，新一代基于有向无环图的分布式账本技术（DLT）。“ X ” 代表基于 DAG 区块链技术的 “价值互联与交换”，赋能保险科技、医疗健康等行业。 DAGX 公链1.0已完成并上线测试。依托中钰资本在医疗健康和保险科技的丰富资源，Bsure DAPP落地。DAGX基金会打造健康与保险行业数字资产公链生态，并助力企业运用 DAGX 开放的平台与技术实现企业资产上链和价值互联、交换。

- 高并发
- 可扩展
- 双合约
- BAAS
- 快支付
- 挖矿
- 高安全
- 应用多
## 基于DAG的价值交换网络
DAGX Networks 是新一代基于有向无环图分布式账本技术（DAG）的商用价值交换网络， X 代表“价值互联与交换”。DAGX Networks 致力推动实体经济与价值互联网连接融合，赋能行业与企业资产价值上链、流通与交换，实现数字经济价值重构和价值创造。 DAGX团队认为：下一代价值互联网将会是多维多链的网络生态，就像繁荣的生物世界。目前行业主流专家依然从传统历史进行推断，认为未来DLT生态发展类似操作系统，只有3-4种主流区块链得以延续发展。DAGX团队对未来有更宏远而不同的判断： 区块链正在带来生产关系的彻底变革，实现价值互联和流通交换体系的重构。区块链通过全球多个价值交换网络和分布式多维逻辑功能链层进行资产价值互联、流通交换， 从而构筑崭新繁荣的多维多链新世界。 

DAGX团队创造性提出了DAGX Value Layers分层架构体系，由不同功能层次化的逻辑功能链组成DAGX Network价值交换网络，积极推动多维多链的下一代价值互联网应用落地。

DAGX公链1.0已完成开发和上线测试，并在医疗健康、保险科技等多行业展开落地合作。依托中钰资本等合作方丰富的医疗健康资源，DAGX重点赋能 “医疗健康、保险互助” 行业，打造健康与保险行业数字资产公链生态，推动各行业企业实现资产上链和价值互联、交换。

# DAGX钱包客户端


Install [bower](http://bower.io/) and [grunt](http://gruntjs.com/getting-started) if you haven't already:

```sh
npm install -g bower
npm install -g grunt-cli
```

Build:

```sh
bower install
npm install
grunt
```
If you are on Windows or using NW.js and Node.js versions other than recommended, see [NW.js instructions about building native modules](http://docs.nwjs.io/en/latest/For%20Users/Advanced/Use%20Native%20Node%20Modules/).

After first run, you'll likely encounter runtime error complaining about node_sqlite3.node not being found, copy the file from the neighboring directory to where the program tries to find it, and run again. (e.g. from `/node_modules/sqlite3/lib/binding/node-v47-darwin-x64` to `/node_modules/sqlite3/lib/binding/node-webkit-v0.14.7-darwin-x64`)

Then run desktop client:

```sh
/path/to/your/nwjs/nwjs .
```

### Android

- Install Android SDK
- Run `make android-debug`

### iOS

- Install Xcode 7 (or newer)
- Install Cordova 6 `npm install cordova@6 -g`
- Run `make ios-debug`

