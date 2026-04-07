# DMIT LAX AN4 EB WEE 深度评测：年付 $39.9，9929+CMIN2 联通移动专属神机

> 联通和移动用户找美国 VPS，真的不用再将就了。

---

## 起因：一次让人上头的购机经历

故事要从一个经典场景说起——

你在用某家 VPS 看 Netflix，速度还行。白天挺流畅，一到晚高峰就开始转圈。你换节点，换服务商，换了三家，电信还好，联通就是慢，移动更像在用 2G。

后来有人在群里扔了一条信息：DMIT 补货了，LAX EB WEE，年付 $39.9，不用优惠码，直接买。

你去看了看，1 核 1G 内存，20G SSD，1000GB 流量，1Gbps 带宽，洛杉矶机房，Eyeball 线路——电信联通去程走 9929，移动走 CMIN2，三网回程全走 CMIN2。

这配置，这价格，这线路……联通移动用户直接就跪了。

这就是 **DMIT LAX AN4 EB WEE** 被叫做"联通移动神机"的原因。

---

## DMIT 是谁？为什么大家都叫它"大妈"

DMIT（全称 DMIT Inc.）2017-2018 年起在美国纽约注册运营，有中国人背景，有中文客服，支持支付宝付款——光这三条，对国内用户来说已经很加分了。

它的核心竞争力只有两个字：**线路**。

在 VPS 这行，很多商家说自己"优化线路"，其实就是 163 普通路由包了层皮。DMIT 不一样，它直接拿了 CN2 GIA、9929（AS9929）、CMIN2 这几条顶级资源，然后按用途拆成三个产品线：

- **Premium（Pro 系列）**：三网 CN2 GIA，电信用户首选，延迟低且稳定
- **Eyeball（EB 系列）**：电信联通走 9929，移动走 CMIN2，三网回程全 CMIN2，联通移动首选
- **Tier 1（T1 系列）**：国际路由，无中国大陆优化，适合落地或拉国际流量

机器全部基于 KVM 虚拟化，AMD EPYC 处理器，NVMe/SSD 固态硬盘，不超售。这一点对于用过某些"共享邻居资源"商家的人来说，感受会很直接。

👉 [了解 DMIT 全系套餐，看看有没有适合你的](https://www.dmit.io/aff.php?aff=13832)

---

## LAX AN4 EB WEE 是什么来头

LAX AN4 EB WEE 的完整名字是 `LAX.AN4.EB.WEE`，拆开来读就是：

- **LAX**：美国洛杉矶数据中心
- **AN4**：Stable Platform，使用 AMD EPYC 9004（EPYC 9654）处理器
- **EB**：Eyeball 线路，电信/联通去程 9929，移动去程 CMIN2，三网回程 CMIN2
- **WEE**：DMIT 的入门特价档，限量提供，不定期补货

**WEE 系列的背景：**

这个套餐不是 DMIT 的常规产品，是特价补货款——第一次推出是 2024 年 5 月，此后多次限量补货。每次放出来基本上都是秒空状态，所以圈内有了"抢 WEE"这个习惯动作。

AN4 平台的 CPU 在 Geekbench 5 单核跑分约 1400 分，虽然不如 AN5（9005 系列，约 2000 分）那么猛，但对于普通建站、科学上网、轻量级应用来说，完全够用。特别是考虑到年付才 $39.9，跟很多家 E5 平台的机器相比，这个性价比实在没什么好说的。

---

## 线路实测：联通移动用户的真实体验

很多人问，EB 线路到底好不好？跟 Pro 系列的 CN2 GIA 差多少？

简单说几个关键点：

**回程线路（国外 → 国内）**：三网全走 CMIN2，这条线路在移动网络下表现很出色，晚高峰稳定性明显优于普通国际路由。联通走 9929 回程，电信也有 CN2 去程，整体不弱。

**去程线路（国内 → 国外）**：电信和联通去程走 9929，移动走 CMIN2。对于移动用户来说，CMIN2 是中国移动自己的骨干网，去程和回程都走自家线路，延迟和稳定性都比绕路强。

**测试 IP**：154.17.226.2 / 2605:52c0:1:3:2c2a:59ff:fe05:65c2（洛杉矶 EB 节点测试地址）

**超量限速**：1000GB 用完后限速 2Mbps——WEE 系列超量限速比较低，如果你是重度流量用户，建议考虑更高配套餐。

**IP 被封政策**：Premium 和 Eyeball 系列均支持免费换 IP，需要满足条件（IP 全端口被封），每 15 天可免费申请一次，其他情况收费 $5/次。月付套餐换 IP 另有规定，建议季付及以上购买。

---

## DMIT LAX EB 系列完整套餐对比

以下是 DMIT 洛杉矶 Eyeball（EB）系列全部在售套餐，包含 WEE 特价款和常规 AN4 标准款，数据来源于官网页面（价格/库存以官网实时为准）：

### LAX.AN4.EB 特价款（限量，不定期补货）

| 套餐名称 | vCPU | 内存 | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|---|---|---|---|---|---|---|---|
| LAX.AN4.EB.WEE | 1 核 | 1 GB | 20 GB SSD | 1000 GB/月 | 1 Gbps | $39.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=188) |
| LAX.AN4.EB.CORONA | 1 核 | 1 GB | 20 GB SSD | 2000 GB/月 | 1 Gbps | $49.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=189) |

> 注：WEE 和 CORONA 均为限量特价款，有货时无需优惠码直接购买，售完即止。

### LAX.AN4.EB 常规款（长期有货）

| 套餐名称 | vCPU | 内存 | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|---|---|---|---|---|---|---|---|
| TINY | 1 核 | 2 GB | 20 GB SSD | 1500 GB/月 | 2 Gbps | $9.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=245) |
| Pocket | 2 核 | 2 GB | 40 GB SSD | 3000 GB/月 | 4 Gbps | $14.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=246) |
| STARTER | 2 核 | 2 GB | 80 GB SSD | 5000 GB/月 | 10 Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=247) |
| MINI | 4 核 | 4 GB | 80 GB SSD | 10000 GB/月 | 10 Gbps | $58.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=248) |
| MICRO | 4 核 | 4 GB | 160 GB SSD | 14000 GB/月 | 10 Gbps | $74.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=249) |
| MEDIUM | 6 核 | 8 GB | 160 GB SSD | 30000 GB/月 | 10 Gbps | $168.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=250) |
| LARGE | 8 核 | 16 GB | 320 GB SSD | 50000 GB/月 | 10 Gbps | $338.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=251) |
| GIANT | 12 核 | 24 GB | 640 GB SSD | 100000 GB/月 | 10 Gbps | $619.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=252) |

---

## DMIT 其他产品线一览（洛杉矶、香港、东京）

如果 EB WEE 已经售罄，或者你需要 CN2 GIA / 国际线路 / 香港东京节点，以下是 DMIT 全系主流套餐概览：

### 洛杉矶 Premium（Pro）系列 — 三网 CN2 GIA

适合电信用户和对延迟要求高的场景，三网去程和回程全走 CN2 GIA。

| 套餐 | vCPU | 内存 | 流量 | 带宽 | 价格 | 购买 |
|---|---|---|---|---|---|---|
| WEE（特价限量） | 1 核 | 1 GB | 500 GB | 500 Mbps | $39.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=183) |
| TINY | 1 核 | 2 GB | 1000 GB | 1 Gbps | $9.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=237) |
| Pocket | 2 核 | 2 GB | 1500 GB | 4 Gbps | $14.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=238) |
| STARTER | 2 核 | 2 GB | 3000 GB | 10 Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=239) |
| MINI | 4 核 | 4 GB | 5000 GB | 10 Gbps | $58.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=240) |
| MICRO | 4 核 | 4 GB | 7000 GB | 10 Gbps | $74.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=241) |
| MEDIUM | 6 核 | 8 GB | 15000 GB | 10 Gbps | $168.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=242) |
| LARGE | 8 核 | 16 GB | 25000 GB | 10 Gbps | $338.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=243) |
| GIANT | 12 核 | 24 GB | 50000 GB | 10 Gbps | $619.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=244) |

### 洛杉矶 Tier 1 系列 — 国际线路，适合落地

| 套餐 | vCPU | 内存 | 流量 | 带宽 | 价格 | 购买 |
|---|---|---|---|---|---|---|
| WEE（年付）| 1 核 | 1 GB | 1000 GB | 4 Gbps | $36.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=71) |
| TINY | 1 核 | 1 GB | 2000 GB | 4 Gbps | $6.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=116) |
| STARTER | 2 核 | 2 GB | 4000 GB | 10 Gbps | $12.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=117) |
| MINI | 2 核 | 4 GB | 8000 GB | 10 Gbps | $21.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=118) |
| MICRO | 4 核 | 4 GB | 16000 GB | 10 Gbps | $32.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=119) |

### 香港 Premium（Pro）系列 — 三网 CN2 GIA，延迟最低

| 套餐 | vCPU | 内存 | 流量 | 带宽 | 价格 | 购买 |
|---|---|---|---|---|---|---|
| TINY | 1 核 | 1 GB | 500 GB | 1 Gbps | $39.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=123) |
| STARTER | 1 核 | 2 GB | 1000 GB | 1 Gbps | $79.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=124) |
| MINI | 2 核 | 2 GB | 1500 GB | 1 Gbps | $119.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=125) |
| MICRO | 4 核 | 4 GB | 2000 GB | 1 Gbps | $159.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=126) |
| MEDIUM | 4 核 | 8 GB | 2500 GB | 1 Gbps | $179.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=127) |
| LARGE | 8 核 | 16 GB | 3000 GB | 1 Gbps | $239.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=128) |
| GIANT | 8 核 | 24 GB | 6000 GB | 1 Gbps | $499.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=129) |

### 香港 Eyeball（EB）系列 — 三网 CMI

| 套餐 | vCPU | 内存 | 流量 | 带宽 | 价格 | 购买 |
|---|---|---|---|---|---|---|
| TINYv2 | 1 核 | 1 GB | 1000 GB | 1 Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=210) |
| STARTERv2 | 1 核 | 2 GB | 2000 GB | 2 Gbps | $59.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=211) |
| MINIv2 | 2 核 | 2 GB | 3000 GB | 2 Gbps | $89.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=212) |
| MICROv2 | 4 核 | 4 GB | 4000 GB | 4 Gbps | $129.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=213) |
| MEDIUMv2 | 4 核 | 8 GB | 6000 GB | 4 Gbps | $199.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=214) |
| LARGEv2 | 8 核 | 16 GB | 12000 GB | 4 Gbps | $389.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=215) |
| GIANTv2 | 8 核 | 24 GB | 24000 GB | 4 Gbps | $789.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=216) |

### 香港 Tier 1 系列

| 套餐 | vCPU | 内存 | 流量 | 价格 | 购买 |
|---|---|---|---|---|---|
| WEE（年付）| 1 核 | 1 GB | 1000 GB | $36.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=197) |
| TINY | 1 核 | 1 GB | 2000 GB | $6.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=198) |
| STARTER | 1 核 | 2 GB | 4000 GB | $12.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=199) |
| MINI | 2 核 | 2 GB | 8000 GB | $21.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=200) |

---

## 谁适合买 DMIT LAX AN4 EB WEE？

说几个典型场景：

**联通用户** — 无脑闭眼入。EB 系列对联通的 9929 回程是加持最大的，联通走 AS9929 这条精品网，访问体验远超普通路由。

**移动用户** — 同样是主力推荐对象。去程 CMIN2 + 回程 CMIN2，移动自家骨干网全程护航，不用担心绕路问题。

**轻量建站用户** — 1 核 1G 内存够跑 WordPress 或静态站点，流量 1000GB 对小流量网站来说基本用不完，年付 $39.9 很有性价比。

**科学上网节点用户** — 这是很多人购买 WEE 套餐的主要原因。优化线路 + 稳定的商家背景，体验明显比乱用便宜机器要好。

**不太适合的情况** — 如果你是重度流量用户（每月需要超过 1000GB），超量后 2Mbps 限速会是比较明显的瓶颈，这时候建议直接上 EB TINY（月付 $9.99，1500GB 流量）或更高配。

---

## 优惠码与购买建议

DMIT 的优惠码政策有些特殊：**WEE 特价套餐本身就是折后低价，无法叠加使用优惠码**。常规套餐可以用以下优惠码：

- **LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF** — LAX EB 系列季付及以上享 8 折循环折扣
- **PVM-LAX-LAUNCH-NON-MONTHLY-RECURRING-20OFF** — LAX Pro 系列季付及以上享 8 折循环折扣

注意：月付订单不适用大多数优惠码，季付或年付才能触发折扣。

**退款政策**：购买后 3 天内全额退款（使用流量不超过 30GB）；30 天内可按剩余价值比例退款。WEE 这类特价套餐历来补货后很快售罄，如果看到有货，建议直接出手，不用纠结太久。

👉 [查看 DMIT 最新套餐，有货赶快下单](https://www.dmit.io/aff.php?aff=13832&pid=188)

---

## 最后说几句

DMIT 在 VPS 圈子里不算便宜，但在"贵有贵的理由"这件事上，它基本上兑现了承诺：线路真实、不超售、中文客服响应。

LAX AN4 EB WEE 之所以受欢迎，是因为它把一件事做对了：让联通和移动用户用上了本来只有花大价钱才能享受的优化线路，而且只要 $39.9 一年。

这个套餐不是每天都有，而且每次补货数量有限。如果刚好在看这篇文章的时候它还有货，那你运气不错——直接去买就行了。

👉 [DMIT LAX AN4 EB WEE，年付 $39.9，点击查看库存](https://www.dmit.io/aff.php?aff=13832&pid=188)
