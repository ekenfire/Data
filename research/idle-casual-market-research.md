# App Store“轻量挂机/纯休闲放置”公开样本调研

> 截止日：2026-09-05（Asia/Shanghai）
> 访问日期：2026-09-05
> 范围：有限、可核验的公开样本，不是全市场盘点。

## 结论先行

- 本轮以 `放置`、`挂机`、`离线收益`、`点击/点按`、`合并`、`idle`、`clicker`、`incremental`、`tap`、`merge`、`offline`、`relaxing` 等词检索，并按 App Store `app id` 去重。
- 可确认样本数为 **12 个产品**：其中 **10 个核心样本**直接符合“自动增长/离线收益/点按或合并，目标不是深度经营”；另有 **2 个边界样本**虽明确含 idle/离线循环，但 App Store 分类为 Simulation，且有较明显的餐厅/栖息地经营内容。
- 这 12 个只是“按本轮检索词与口径能核验到的公开样本数”，**不是全市场总量，也不能据此估算市场规模**。
- App Store 官方页面公开了评分、评分数、分类、年龄分级、价格/IAP、开发者/卖家、语言、大小、兼容设备与最低系统版本、版本历史/最近更新、隐私披露等；**没有找到 App Store 页面公开下载量、安装量、DAU/MAU 或访问量**。
- 评分数只表示用户提交的 ratings 数量，**不等于下载量**。Google Play 的 `10M+`、`100K+` 等是 Google Play 侧公开的下载阈值；它们不等于 App Store 下载量，也不能与 App Store 评分数相加。

## 补充：Apple 官方搜索接口的检索集合（不是市场总量）

为估计长尾规模，我在 2026-09-05 查询了 Apple 官方 Search API。美国区用 idle、clicker、incremental、afk、tap tycoon、idle game 六组词合并后，得到 548 条标题含这些关键词的去重游戏记录；其中 425 条不含 Roleplaying，366 条同时属于 Casual 或 Simulation 且不含 Roleplaying。这个数字受关键词、地区、接口返回上限和标题命名影响，只能说明“可检索长尾至少很长”，不能当作 548 个真实竞品。

中国区用 放置、挂机、点击 三组词合并得到 278 条游戏记录，但包含大量 RPG、策略和无关结果，噪声明显更高，因此没有把 278 当作轻休闲放置游戏数量。

查询入口：
- https://itunes.apple.com/search?term=idle&country=us&media=software&entity=software&limit=200
- https://itunes.apple.com/search?term=clicker&country=us&media=software&entity=software&limit=200
- https://itunes.apple.com/search?term=incremental&country=us&media=software&entity=software&limit=200

## 样本表

“最近更新”按 App Store 页面“版本历史”中最靠前的条目记录；当页面只显示“几天前”或不显示年份时，原样保留，不自行补年。

| 产品（App Store app id） | 地区/纳入判断 | App Store 页面实际公开字段（访问日页面所见） | 最近更新（页面显示） | 可确认的下载/访问指标 | 事实来源 |
|---|---|---|---|---|---|
| **Idle Game 1**（1529082184） | 美国区；核心。官方副标题为 “Minimalist Incremental Clicker”，描述含 incremental、prestige、idle 循环。 | 免费；App 内购买；4.7/5，8.3K Ratings；年龄 4+；分类 Casual；开发者 Cem Kamiloglu；英语；6.3 MB；iPhone/iPad/Mac。 | `2026.8.1`，`2d ago` | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页面另显示 `100K+ Downloads`，仅代表 Android/Google Play 侧公开阈值。 | [App Store 美国区](https://apps.apple.com/us/app/idle-game-1/id1529082184)；[Google Play 官方页](https://play.google.com/store/apps/details?hl=en\&id=com.cem.idle1)（均访问 2026-09-05） |
| **Idle Acorns**（1552999208） | 美国区；核心。官方标题/副标题为 “Classic idle game with no ads”，描述含 mobile clicker、离线收集。 | `$1.99`；4.8/5，1.2K Ratings；年龄 4+；分类 Casual（页面同时显示 Casual 图表位）；开发者 aleros.io LLC；英语；156.2 MB；iPhone/iPad/Mac/iMessage；无 IAP。 | 首条版本历史仅显示 “Acorn AI and Bug Fixes!”；未见版本号/日期；下一条为 `2.1.9 07/22/2024`。 | **找不到下载量或访问量**（包括 App Store 侧）。 | [App Store 美国区](https://apps.apple.com/us/app/idle-acorns/id1552999208)（访问 2026-09-05） |
| **Idle Gears: Tycoon Empire**（1673587975） | 美国区；核心。官方副标题为 “Relaxing offline merge clicker”，明确写 progress continues when closed。 | 免费；App 内购买；4.5/5，180 Ratings；年龄 4+；分类 Casual；开发者 Simplicated Games Inc.；英语；289 MB；iPhone/iPad/Mac/Apple Vision。 | `1.24.0 Jan 20`（页面未显示年份） | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页显示 `100K+ Downloads`，仅代表 Android/Google Play 侧。 | [App Store 美国区](https://apps.apple.com/us/app/idle-gears-tycoon-empire/id1673587975)；[Google Play 官方页](https://play.google.com/store/apps/details?hl=en_US\&id=com.SimplicatedGames.idle.gears)（访问 2026-09-05） |
| **Droplet Idle: Cozy Rain Game**（6757197192） | 美国区；核心。官方副标题为 “Swipe, Merge & Relax”，描述明确写自动合并、离线 idle rewards。 | 免费；App 内购买；4.7/5，267 Ratings；年龄 4+；分类 Casual；开发者 MENTAL HEALTH SOLUTIONS S.R.L.；英语；114.7 MB；iPhone/iPad/Mac/Apple Vision。 | `1.2.4 Jul 17`（页面未显示年份） | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页显示 `5K+ Downloads`，仅代表 Android/Google Play 侧。 | [App Store 美国区](https://apps.apple.com/us/app/droplet-idle-cozy-rain-game/id6757197192?platform=ipad)；[Google Play 官方页](https://play.google.com/store/apps/details?hl=en-US\&id=com.mhsolutions.droplet)（访问 2026-09-05） |
| **Idle Cash – Merge Tycoon**（1621550247） | 美国区；核心但带轻经营包装。官方副标题为 “Merge, Tap & Grow Your Fortune”，描述明确写 AFK/offline idle rewards、merge、tap。 | 免费；App 内购买；4.5/5，217 Ratings；年龄 4+；分类 Casual；开发者 Twice Yazilim Teknoloji Limited Sirketi；英语等 8 种语言；269.6 MB；iPhone/iPad/Mac。 | `2.0.12 Aug 27`（页面未显示年份） | **找不到下载量或访问量**（包括 App Store 侧）。 | [App Store 美国区](https://apps.apple.com/us/app/idle-cash-merge-tycoon/id1621550247?platform=ipad)（访问 2026-09-05） |
| **Idle Light City**（1489263669） | 美国区；核心。官方副标题为 “Lighting Up The City”，描述明确写 clicker、tap tap、offline income/升级循环。 | 免费；App 内购买；4.7/5，31K Ratings；年龄 4+；分类 Casual；开发者 AppQuantum Publishing Ltd；英语；279.8 MB；iPhone/iPad。 | `3.0.2 11/06/2023` | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页显示 `10M+ Downloads`；AppQuantum 第一方页面曾公开“8,000,000 installs in 10 months”，且未按 iOS/Android 拆分，因此不能视为 App Store 下载量。 | [App Store 美国区](https://apps.apple.com/us/app/idle-light-city/id1489263669)；[Google Play 官方页](https://play.google.com/store/apps/details?id=com.nopowerup.idlelightcity)；[AppQuantum 第一方公告](https://appquantum.com/news/we-have-grown-bigger.html)（访问 2026-09-05） |
| **Balls Clicker**（1289985755） | 美国区；核心。官方副标题为 “Tap, buy balls, upgrade!”；描述明确写 tap or idle、资源自动增长。 | 免费；App 内购买；4.4/5，1K Ratings；年龄 4+；分类 Adventure；开发者 Fine Monkeys；英语；135.5 MB；iPhone/iPad。 | `3.0 04/24/2023` | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页（同系列标题为 Balls Clicker: Idler）显示 `10K+ Downloads`，仅代表 Android/Google Play 侧。 | [App Store 美国区](https://apps.apple.com/us/app/balls-clicker/id1289985755)；[Google Play 官方页](https://play.google.com/store/apps/details?id=com.FVS.IdleBalls)（访问 2026-09-05） |
| **My Oasis: Anxiety Relief Game**（1247889896） | 美国区；核心。官方描述直接称为 idle clicker/tapping game，强调无强操作与放松。 | 免费；App 内购买；4.7/5，9.3K Ratings；年龄 4+；分类 Simulation；开发者 June Inter Co., Ltd.；英语等 14 种语言；289 MB；iPhone/iPad。 | `2.64.7 Jul 16`（页面未显示年份） | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页显示 `10M+ Downloads`，仅代表 Android/Google Play 侧。 | [App Store 美国区](https://apps.apple.com/us/app/my-oasis-anxiety-relief-game/id1247889896)；[Google Play 官方页](https://play.google.com/store/apps/details?hl=en-US\&id=com.buffstudio.myoasis)（访问 2026-09-05） |
| **Tap Tap Fish - AbyssRium**（1068366937） | 美国区；核心。官方描述多次称 idle relaxing game，核心是点按、自动成长和观察式休闲。 | 免费；App 内购买；4.5/5，24K Ratings；年龄 9+；分类 Simulation；开发者 SangHeon Kim；英语等 5 种语言；1.7 GB；iPhone/iPad/iMessage。 | `1.99.2 2d ago` | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页显示 `10M+ Downloads`，仅代表 Android/Google Play 侧。 | [App Store 美国区](https://apps.apple.com/us/app/tap-tap-fish-abyssrium/id1068366937)；[Google Play 官方页](https://play.google.com/store/apps/details?hl=en_US\&id=com.idleif.abyssrium)（访问 2026-09-05） |
| **放置打砖块-无限重生**（6448981457） | 中国区；核心。官方描述明确写“简单的放置类游戏”、放置点击、离线收益、无限重生与升级。 | 免费；页面未显示 App 内购买；4.6/5，205 个评分；年龄 18+；类别 休闲；开发者 登理 郝；中文等 2 种语言；82.5 MB；iPhone/iPad。 | `1.9 2023/12/20` | **找不到 iOS/App Store 下载量或访问量。** | [App Store 中国区](https://apps.apple.com/cn/app/%E6%94%BE%E7%BD%AE%E6%89%93%E7%A0%96%E5%9D%97-%E6%97%A0%E9%99%90%E9%87%8D%E7%94%9F/id6448981457)（访问 2026-09-05） |
| **Penguin Isle**（1474314811） | 美国区；**边界样本**。官方描述为 easy/simple gameplay；Apple 编辑内容明确称其为 idle game，但产品有栖息地、扩展与装饰等轻经营元素。 | 免费；App 内购买；4.8/5，39K Ratings；年龄 4+；分类 Simulation；开发者 HABBY；英语等 11 种语言；489.6 MB；iPhone/iPad/Mac/Apple Vision。 | `1.99.0 5d ago` | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页显示 `10M+ Downloads`，仅代表 Android/Google Play 侧。 | [App Store 美国区](https://apps.apple.com/us/app/penguin-isle/id1474314811)；[Apple 编辑内容](https://apps.apple.com/us/story/id1484761204)；[Google Play 官方页](https://play.google.com/store/apps/details?hl=en\&id=com.fantome.penguinisle)（访问 2026-09-05） |
| **Cat Snack Bar: Food Games**（6443895159） | 美国区；**边界样本**。官方描述明确称 perfect idle game、离线运行，但核心同时是 restaurant tycoon/服务、扩张和管理；因此不计入严格“纯休闲”口径，作为相邻轻经营样本保留。 | 免费；App 内购买；4.9/5，119K Ratings；年龄 9+；分类 Simulation；开发者 Neptune Company；英语等 8 种语言；448.7 MB；iPhone/iPad/Mac/Apple Vision；含 Loot Boxes/Advertising。 | `1.0.218 Aug 24`（页面未显示年份） | **找不到 iOS/App Store 下载量或访问量。** Google Play 官方页显示 `10M+ Downloads`，仅代表 Android/Google Play 侧。 | [App Store 美国区](https://apps.apple.com/us/app/cat-snack-bar-food-games/id6443895159)；[Google Play 官方页](https://play.google.com/store/apps/details?hl=en_US\&id=com.tree.idle.catsnackbar)（访问 2026-09-05） |

## App Store 页面实际公开的字段

以下是本轮打开的官方页面中实际可见的字段类型；不同产品不一定每项都有，页面也会随地区、设备与时间变化：

1. **基本展示**：产品名、宣传副标题/短句、截图/视频入口、平台入口。
2. **商业信息**：免费或一次性价格；是否有 App 内购买；部分页面列出具体 IAP 名称与价格；部分页面标出广告、Loot Boxes 等内容标签。
3. **口碑字段**：平均评分（如 4.7/5）与 Ratings 数量（如 8.3K、31K、205 个）。这些是评分/评价字段，不是下载量。
4. **商店分类与审核信息**：Category/类别、Age Rating/年龄分级；部分页面还会显示分类榜单名次。
5. **开发者与技术信息**：Developer/Seller、语言、安装包大小、支持的设备、最低 iOS/iPadOS/macOS/visionOS 版本。
6. **版本与合规信息**：What’s New/版本历史、版本号与日期或“几天前”；App Privacy/隐私披露；开发者网站、隐私政策、版权；部分产品有 Game Center、Family Sharing 等支持信息。

代表性官方页面：

- [Idle Game 1 的 App Store 字段](https://apps.apple.com/us/app/idle-game-1/id1529082184)：可见免费/IAP、评分与评分数、4+、Casual、开发者、语言、大小、兼容性、IAP 与版本历史。
- [Idle Acorns 的 App Store 字段](https://apps.apple.com/us/app/idle-acorns/id1552999208)：可见 `$1.99`、评分与评分数、4+、Casual、开发者、语言、大小、兼容性、版本历史、Game Center 与 Family Sharing。
- [放置打砖块-无限重生的中国区字段](https://apps.apple.com/cn/app/%E6%94%BE%E7%BD%AE%E6%89%93%E7%A0%96%E5%9D%97-%E6%97%A0%E9%99%90%E9%87%8D%E7%94%9F/id6448981457)：可见免费、评分与评分数、18+、休闲、开发者、语言、大小、兼容性与版本历史。

## 下载量、访问量核验结果

### 能直接确认的公开数字

这些数字来自 Google Play 官方产品页或开发商/发行商第一方页面，均标明为对应平台或发行商口径：

- **Idle Game 1**：Google Play `100K+ Downloads`。
- **Idle Gears: Tycoon Empire**：Google Play `100K+ Downloads`。
- **Droplet Idle: Cozy Rain Game**：Google Play `5K+ Downloads`。
- **Balls Clicker: Idler**：Google Play `10K+ Downloads`。
- **My Oasis: Relaxing, Satisfying**：Google Play `10M+ Downloads`。
- **Tap Tap Fish AbyssRium (+VR)**：Google Play `10M+ Downloads`。
- **Penguin Isle**：Google Play `10M+ Downloads`。
- **Cat Snack Bar: Cute Food Games**：Google Play `10M+ Downloads`。
- **Idle Light City**：Google Play `10M+ Downloads`；AppQuantum 第一方公告还写过 `8,000,000 installs in 10 months`，以及[更早的首两个月 `2.8M+ installs`](https://appquantum.com/news/idle-light-city-has-reached-2.8m-downloads.html)。这些是 Android/Google Play 或发行商公开口径，未按 iOS App Store 拆分。

### 明确找不到的数字

- **全部 12 个样本**：本轮没有找到 App Store 官方页公开的 iOS 下载量、安装量、DAU、MAU 或访问量。
- **Idle Acorns、Idle Cash – Merge Tycoon、放置打砖块-无限重生**：本轮也没有找到可直接核验的 Google Play 官方下载阈值或发行商公开下载数字。
- 本轮没有采用“评分数 × 某个换算系数”推导下载量，也没有把第三方搜索摘要或未经页面核验的数字写成事实。
- 对“访问量”：没有找到这些 App Store 产品的公开页面访问量或流量数字；Google Play 的 Downloads 字段是下载阈值，不是页面访问量。

## 排除与口径边界

- 排除以 RPG、卡牌、战斗、阵容/装备、多人策略或大规模城市/帝国经营为核心的产品，即使产品名含“放置/挂机”。例如本轮中国区检索到的《放置军团》《放置与召唤》《仙侠第一放置》《单机封神》都显示了明显的策略、卡牌、RPG、装备/宠物/副本或战斗系统，不能作为“本质是纯休闲小游戏”的核心样本。
- “Penguin Isle”和“Cat Snack Bar”保留是为了展示相邻的轻经营边界：两者官方页面都明确使用 idle/离线或轻松休闲表述，但产品分类与内容比纯 clicker/merge 更重，所以单独标记，不纳入严格 10 个核心样本。
- “Idle Light City”“Idle Cash”虽有 tycoon/城市或工厂包装，但本轮官方描述仍以点按、自动/离线收益和升级循环为主，未达到排除标准；这是一个有判断成分的纳入决定。

## 限制

- App Store 的地区页、展示语言、评分数、版本历史和 IAP 价格可能随地区、设备和时间变化；本文记录的是 2026-09-05 访问时页面所见。
- `K/M` 和 `+` 是商店的展示格式/阈值，不是精确下载数；不同平台的数字不可直接合并。
- 样本数由检索词、地区优先级、是否仍在架、页面可访问性与本文纳入规则共同决定，因此只能回答“本轮可确认到多少”，不能回答“市场上总共有多少”。
