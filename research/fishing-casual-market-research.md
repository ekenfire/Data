# App Store 钓鱼类：轻休闲/放置市场补充调研

> 截止/访问日期：2026-09-05（Asia/Shanghai）
> 数据范围：Apple App Store 公开页面、Apple Search API、Google Play 官方页面；不使用评分数推算下载量。

## 结论

- Apple Search API 用 `fishing` 查询：美国区返回 181 条软件记录，其中 115 条为 Games；中国区用 `钓鱼` 查询：返回 125 条软件记录，其中 57 条为 Games。结果混入水族箱、鱼吃鱼、赌场/捕鱼机、RPG 等，不能把这些数字当成钓鱼游戏市场总量。
- 按“钓鱼是主循环，并且有 idle/offline/passive/短时回访机制”的严格口径，本轮从公开页面人工核验到 **至少 10 个核心/近核心产品**；另有一批主动操作型或经营/多人玩法较重的边界产品。
- App Store 没有公开这些产品的 iOS 下载量、页面访问量、DAU/MAU；Apple 将 Product Page Views、Total Downloads、Active Devices 等定义为 App Store Connect Analytics 指标。公开页的 Ratings 数只能作为热度代理。
- 能公开核验的下载数主要来自 Google Play 的量级门槛，不能代表 iOS，也不能与 App Store Ratings 相加。

## Apple Search API 结果

Apple 官方 Search API 文档说明可以用 `country`、`media`、`entity` 和 `limit` 控制商店、媒体类型、实体和返回数量；本次使用 `media=software`、`entity=software`、`limit=200`，再按 `primaryGenreName=Games` 筛选。

- 美国区：[fishing 查询](https://itunes.apple.com/search?term=fishing&country=us&media=software&entity=software&limit=200)：181 条 software，115 条 Games；粗按 Casual/Simulation 相关分类筛选为 83 条，仍含大量非目标产品。
- 中国区：[钓鱼查询](https://itunes.apple.com/search?term=%E9%92%93%E9%B1%BC&country=cn&media=software&entity=software&limit=200)：125 条 software，57 条 Games；粗按 休闲/模拟相关分类筛选为 34 条，仍有明显噪声。
- API 计数是当日检索集合，不是商店全量，也不是“符合产品定义”的数量。

## 核心/近核心样本

| 产品 | App Store 公开信号 | Google Play/其他公开下载信号 | 玩法证据 |
|---|---:|---:|---|
| [Tides: A Fishing Game](https://apps.apple.com/us/app/tides-a-fishing-game/id1524699590) | 22K Ratings，4.8 | [500K+ Downloads](https://play.google.com/store/apps/details?id=com.shallotgames.tides&hl=en_US) | 页面副标题为 Idle Fishing Adventure；离线 idle income、助手、宠物、收集与小岛升级。 |
| [Fishing Food](https://apps.apple.com/us/app/fishing-food/id1462574213) | 54K，4.9 | [5M+ Downloads](https://play.google.com/store/apps/details?hl=en_US&id=com.dicedpixel.fishingfood) | 点按/滑动钓食物；offline profits；休闲、收集、升级。 |
| [Idle Fish 2: Fishing Tycoon](https://apps.apple.com/us/app/idle-fish-2-fishing-tycoon/id1534396279) | 5.7K，4.8 | [5M+ Downloads](https://play.google.com/store/apps/details?hl=en_CA&id=com.greenbuttongames.FishIdle) | 官方定位 idle fishing；离线、船只/渔夫升级。 |
| [Fishing Frenzy:Idle Hooked Inc](https://apps.apple.com/us/app/fishing-frenzy-idle-hooked-inc/id6502436718) | 10K，4.8 | [1M+ Downloads](https://play.google.com/store/apps/details?hl=en-US&id=com.cyberjoy.fishing) | idle fishing tycoon；雇佣渔夫、被动收益、船只升级；经营与广告较重。 |
| [Idle Furry Fishing!](https://apps.apple.com/us/app/idle-furry-fishing/id6449223341) | 1.8K，4.0 | 未找到官方公开下载量 | Hold/drag 钓鱼；鱼竿离线赚钱；100+鱼类收集。 |
| [Fishing Clicker](https://apps.apple.com/us/app/fishing-clicker/id1050955444) | 61，4.7 | 未找到 | 官方副标题 Idle Fishing Adventure Game；idle rewards、auto fishing、离线。 |
| [Idle Fishing: Mobile](https://apps.apple.com/us/app/idle-fishing-mobile/id6614782311) | 83，4.8 | 未找到 | Idle/Active 双模式；建筑被动收入、升级树、助手与成就。 |
| [Fish Away: Idle Fishing](https://apps.apple.com/us/app/fish-away-idle-fishing/id6787988987) | 99，4.7 | 未找到 | 官方写明离线推进、升级船和鱼竿、短时回访。 |
| [Fisherman - Idle Fishing Game](https://apps.apple.com/us/app/fisherman-idle-fishing-game/id1451894206) | 106，4.7 | 未找到 | idle incremental tycoon clicker；离线、点击、鱼类与水族箱。 |
| [我的钓鱼生活](https://apps.apple.com/cn/app/%E6%88%91%E7%9A%84%E9%92%93%E9%B1%BC%E7%94%9F%E6%B4%BB/id1658935324) | 约 3.5K，4.8 | 未找到 | 中文区页面明确写闲置钓鱼冒险、闲置收入、闲置钓鱼助手。 |

## 规模更大的边界/主动操作型产品

| 产品 | App Store 公开信号 | 可核验下载信号 | 为什么不算“纯轻放置” |
|---|---:|---:|---|
| [Hooked Inc: Fishing Games](https://apps.apple.com/us/app/hooked-inc-fishing-games/id1436213906) | 500K，4.7 | [Google Play 10M+](https://play.google.com/store/apps/details?id=se.ace.fishinc) | 最强的放置钓鱼商业样本之一，但含船队/帝国、多人锦标赛、广告与较重经营。 |
| [欢乐钓鱼大师](https://apps.apple.com/cn/app/%E6%AC%A2%E4%B9%90%E9%92%93%E9%B1%BC%E5%A4%A7%E5%B8%88/id6479696944?platform=ipad) | 约 147 万，4.7；体育榜 #4 | 未找到 iOS 下载量 | 中国区头部钓鱼产品，但核心是 3D 真实操作、竞技和对战，不是 idle。 |
| [Fishing Clash](https://apps.apple.com/us/app/fishing-clash-sport-simulator/id1151811380) | 约 158K，4.8 | [Google Play 100M+](https://play.google.com/store/apps/details?id=com.tensquaregames.letsfish2) | 竞技/多人/实时操作型。 |
| [Creatures of the Deep](https://apps.apple.com/us/app/creatures-of-the-deep/id1556204048) | 64K，4.8 | [Google Play 5M+](https://play.google.com/store/apps/details?hl=en_US&id=pl.idreams.cotd) | 有被动收入，但同时含多人、探索、PvP、公会和基地建设。 |
| [Fishing and Life](https://apps.apple.com/us/app/fishing-and-life/id1457176367) | 857，3.8 | [Google Play 10M+](https://play.google.com/store/apps/details?hl=en-US&id=com.nexelon.fishinglife) | 休闲治愈、简单操作和水族箱，但不是明确的 idle 主循环。 |
| [Fishing Break](https://apps.apple.com/us/app/fishing-break/id997811612) | 13K，4.7 | [Google Play 1M+](https://play.google.com/store/apps/details?id=ca.roofdog.fishing&hl=en_US) | 轻松、收集、短时游玩，但主要仍是主动钓鱼和装备操作。 |
| [Fishing Travel](https://apps.apple.com/us/app/fishing-travel/id6505145935) | 约 42K，4.7 | [Google Play 5M+](https://play.google.com/store/apps/details?hl=en&id=com.arkgame.ft) | 休闲/探索/装饰，但需要主动操作与技能。 |
| [Fishing Master](https://apps.apple.com/us/app/fishing-master/id6471659176) | 约 23K，4.8 | [Google Play 5M+](https://play.google.com/store/apps/details?id=com.arkgame.fishingmaster) | 真实钓鱼、实时 1v1，属于主动操作型。 |
| [钓鱼佬净化海洋](https://apps.apple.com/cn/app/%E9%92%93%E9%B1%BC%E4%BD%AC%E5%87%80%E5%8C%96%E6%B5%B7%E6%B4%8B/id6471782615) | 约 4.8K，4.9 | 未找到 | 单机休闲、钓鱼/叉鱼、收集和升级，接近轻量小游戏但不是放置主循环。 |

## 数据限制

- Apple 的公开产品页展示评分数、分类、榜单名次、价格和玩法描述；本次样本没有找到公开 iOS 下载数或 App Store 页面访问数。
- [Apple App Store Connect Analytics 指标定义](https://developer.apple.com/help/app-store-connect-analytics/reference/metrics-definitions/)列出 Product Page Views、First Time Downloads、Redownloads、Total Downloads、Active Devices 等指标；这些不等于公开产品页可见的数字。
- Google Play 的 500K+/1M+/5M+/10M+/100M+ 是平台公开安装量级门槛，不是精确下载数，也不代表 iOS。
- App Store Ratings 是用户评分数量，不能用固定倍数换算下载量或访问量。
