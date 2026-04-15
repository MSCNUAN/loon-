<div align="center">

# 🦄 Loon 懒人配置 (新手免流版)

**专为小白打造的 Loon 懒人配置 | 国内免流 | 自动测速 | 精准分流**

[![](https://img.shields.io/badge/Author-NuanNuan-ff69b4.svg)](https://t.me/NUAN114514)
[![](https://img.shields.io/badge/Configuration-Loon-blue.svg)](https://github.com/Loon0x00/Loon)
[![](https://img.shields.io/badge/Telegram-Channel-blue.svg)](https://t.me/NUAN114514)

</div>

## 📖 简介 (Introduction)

欢迎使用 **Loon 懒人配置 (新手免流版)**！
这份配置是基于可莉 (Kelee) 大佬的开源项目修改而来，专门针对**新手用户**和**免流需求**进行了深度优化。

如果你不知道什么是策略组、分流规则，或者不想折腾复杂的设置，只想**复制粘贴、填个订阅、马上能用**，那么这份配置就是为你准备的！✨

> 🛑 **关键提醒：请自备国内机场并且提前修改好对应的混淆**，否则无法实现免流效果！
---

## ⚙️ 核心功能 (Features)

1. **🇨🇳 国内免流特化**
   * 内置 `国内手动策略`，所有国内流量强制走该策略。
   * 支持手动切换：想免流就选节点，想省电/稳定就选 `DIRECT` (直连)。
   * 彻底告别“开了代理国内应用也跑通用流量”的尴尬。

2. **⚡️ 地区自动测速**
   * **告别手动选节点！** 配置已内置 香港、台湾、新加坡、美国、日本、韩国 的自动测速组。
   * 系统会自动选择当前延迟最低的节点，看视频、网页秒开。

3. **🎯 应用精准分流**
   * **TikTok** 🔒 锁定 台/日/新 (自动解锁区域限制)
   * **Spotify** 🔒 锁定 香港 (适配低价区)
   * **AI (ChatGPT)** 🔒 锁定 台/日/新 (稳定访问)
   * **Telegram/X/YouTube** 🚀 自动走最快节点

4. **🍼 极致小白友好**
   * 预装去广告、防 DNS 泄漏、节点检测等基础插件。
   * 结构清晰，注释详细，一看就懂。

---

## 🚀 快速开始 (Usage)

### 1. 下载配置
下载本仓库中的 `.lcf` 配置文件，或者直接复制内容到 Loon 的配置文本中。

### 2. ⚠️ 必做步骤：填入订阅
**这是最重要的一步！如果不做，里面全是空的！**
请在配置文件中找到 `[Remote Proxy]` 区域，参考下方格式填入你的机场订阅链接：

```ini
[Remote Proxy]
# 👇 把下面的链接换成你自己的！
我的订阅 = [https://example.com/api/v1/client/subscribe?token=xxxx](https://example.com/api/v1/client/subscribe?token=xxxx), parser-enable=true


```
### 3. 开始使用
保存配置，Loon 会自动拉取节点。

* **日常使用**：`全球手动策略` 建议选择各地区的 `自动策略`（如 `香港自动策略`）。
* **免流使用**：在 `国内手动策略` 中选择你的免流节点。

> 📖 **新手详细教程**：[点击查看 Loon 第一次使用设置指南](https://t.me/ibilibili/165)

---

### ⚠️ 免责声明 (Disclaimer)
* **关于免流**：由于本人手中没有免流卡，本配置中的免流规则全凭经验修改制作。**可能会造成大量跳点 (即免流失败导致扣除通用流量)**。请务必先小范围测试，风险自负！
* **关于维护**：本项目随缘更新，欢迎各位大佬复刻 (Fork) 或二改！

---

### 💬 反馈 & 定制 (Feedback)
* 🐞 **Bug 反馈**：欢迎在 TG 群内反馈测试结果，或提出修改/新增建议。
* 🛠️ **专属定制**：如果你想要属于自己的定制化配置文件（如特殊分流、UI定制等），可以在 TG 群内找我定制（需支付一点辛苦费 ☕️）。

---

## 📢 关注我 & 实用资源推荐
这里汇总了我的联系方式以及我亲测好用的工具与服务，欢迎自取！

### ✈️ 关注我的 Telegram
* **频道 (资源发布/动态)**：[👉 点击订阅](https://t.me/NUAN114514)
* **群组 (吹水/交流)**：[💬 点击加入](https://t.me/MSC4652)

### 🧰 自用工具 & 资源库
* **📦 个人资源站 (综合导航)**：[👉 点此访问](https://nuannuan-tools.vercel.app/)
* **☁️ PikPak 磁力下载**：[⚡️ 点击注册](https://mypikpak.com/drive/activity/invited?invitation-code=66396543)
* **📂 123 网盘资源**：[📂 点击查看](https://www.123684.com/s/R2hjVv-6Pg13) *(提取码: NUAN)*
* **🔧 自用内网穿透工具**：[👉 立即试用 cpolar](https://www.cpolar.com/?channel=0&invite=6DaX)

### 🛒 流量 & 账号服务
* **📶 正规运营商流量卡**：[📶 点击下单](https://bankala.cn/s/f25188b9)
* **💳 Bit Mart (免费外币卡)**：[👉 点击申请](https://www.bitmart.com/zh-CN/invite/ctVj68)
* **🔶 币安 (Binance) 交易所**：[💰 注册领新手礼](https://www.bmwweb.academy/referral/earn-together/refer2earn-usdc/claim?hl=zh-TC&ref=GRO_28502_RAE9X&utm_source=default)
* **🍎 Apple ID / 充值卡 / 代理**：[🍎 购买链接](https://goso002.com/?from=24529)
* **🌍 海外账号 / AI / 流媒体 / 游戏**：[🛍️ 购买链接](https://accboyytbnn.acceboy.com/)

### 🚀 网络加速
* **🌐 自用机场推荐**：[🌐 查看详情](https://t.me/NUAN114514/5)

---

### 🙌 致敬 (Credits)
本配置文件基于 **Kelee** 大佬的懒人配置修改而来，衷心感谢大佬的开源精神！

* Original Project: [ProxyResource](https://github.com/luestr/ProxyResource/tree/main)
* Plugin Hub: [Kelee Hub](https://hub.kelee.one)

> ⚠️ **提示**：部分资源链接可能随时间失效，请以我的 TG 频道最新动态为准。此配置专为 **Loon** 客户端设计。
