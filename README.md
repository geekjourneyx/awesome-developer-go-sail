<p align="center">
  <a href="https://www.gosail.dev/">
    <img src="docs/assets/logo.png" alt="GoSail Logo" width="120" />
  </a>
</p>

<h1 align="center">Developer Go‑Sail Handbook</h1>

<p align="center">
  <a href="https://www.gosail.dev/">https://www.gosail.dev/</a>
</p>

<p align="center">面向中文开发者的「扬帆出海」实战指南：聚焦银行账户办理、全球收款与合规落地，提供经验证的路径与避坑建议。</p>

<p align="center">
  <a href="https://github.com/geekjourneyx/awesome-developer-go-sail/stargazers"><img alt="GitHub Stars" src="https://img.shields.io/github/stars/geekjourneyx/awesome-developer-go-sail?style=flat-square"></a>
  <a href="https://github.com/geekjourneyx/awesome-developer-go-sail/forks"><img alt="GitHub Forks" src="https://img.shields.io/github/forks/geekjourneyx/awesome-developer-go-sail?style=flat-square"></a>
  <a href="https://github.com/geekjourneyx/awesome-developer-go-sail/issues"><img alt="GitHub Issues" src="https://img.shields.io/github/issues/geekjourneyx/awesome-developer-go-sail?style=flat-square"></a>
  <a href="./LICENSE"><img alt="License" src="https://img.shields.io/github/license/geekjourneyx/awesome-developer-go-sail?style=flat-square"></a>
</p>

## 📚 内容概览
- 第一章：香港银行账户办理指南 → [docs/01-hk-bank-account/README.md](docs/01-hk-bank-account/README.md)
  - [HSBC 指南](docs/01-hk-bank-account/hsbc-guide.md)
  - [BOCHK 渣打/ZA/蚂蚁/众安/工银亚洲/恒生等](docs/01-hk-bank-account/README.md)
  - [开户路径对比](docs/01-hk-bank-account/comparison.md)
- 第二章：全球支付网关配置 → [docs/02-payments/README.md](docs/02-payments/README.md)
  - [Stripe 配置](docs/02-payments/stripe.md)
  - [Wise 收款](docs/02-payments/wise.md)
- 贡献指南 → [CONTRIBUTING.md](CONTRIBUTING.md)

## ✨ 亮点
- 实操为先：基于真实踩坑经验沉淀高通过率流程。
- 中文优先：聚焦中国开发者常见情境与限制条件。
- 合规提醒：显式标注政策波动与需线下核实的环节。
- 可拓展性：章节化结构，便于社区持续补充与修订。

## 🚀 快速开始
1. 阅读第一章：[选择开户路径](docs/01-hk-bank-account/README.md)（线上/线下/VTM/见证）。
2. 准备材料：身份证、港澳通行证、入境记录 PDF、可收件地址、稳定网络等。
3. 完成开户后，前往第二章：[配置 Stripe/Wise](docs/02-payments/README.md)。
4. 提交前参考：[CONTRIBUTING.md](CONTRIBUTING.md)。

## 🔗 一键直达（常用小节）
- 香港银行
  - HSBC：
    - [账户类型](docs/01-hk-bank-account/hsbc-guide.md#hsbc-types)
    - [线上开户（HSBC One）](docs/01-hk-bank-account/hsbc-guide.md#hsbc-online)
    - [地址填写（字符限制与示例）](docs/01-hk-bank-account/hsbc-guide.md#hsbc-address)
  - [工银亚洲（VTM）](docs/01-hk-bank-account/icbc-asia-guide.md)
  - [中银香港 BOCHK](docs/01-hk-bank-account/bochk-guide.md)
  - [渣打香港 SCB](docs/01-hk-bank-account/scb-guide.md)
  - [众安银行 ZA Bank](docs/01-hk-bank-account/za-bank-guide.md)
  - [众安银行资金转入与实体卡申请](docs/01-hk-bank-account/za-bank-funding-guide.md)
  - [蚂蚁银行 Ant Bank](docs/01-hk-bank-account/ant-bank-guide.md)
  - [天星银行 Airstar](docs/01-hk-bank-account/airstar-guide.md)
  - [香港银行卡维护与后续操作](docs/01-hk-bank-account/hk-bank-maintenance-guide.md)
- 支付与收款
  - Stripe：
    - [开户前准备](docs/02-payments/stripe.md#stripe-prep)
    - [注册流程](docs/02-payments/stripe.md#stripe-register)
    - [出金与资金路径](docs/02-payments/stripe.md#stripe-payouts)
    - [常见问题 FAQ](docs/02-payments/stripe.md#stripe-faq)
  - [Wise 收款](docs/02-payments/wise.md)

## 🗂️ 目录结构
- docs/
  - 01-hk-bank-account/
    - [README.md](docs/01-hk-bank-account/README.md)
    - [hsbc-guide.md](docs/01-hk-bank-account/hsbc-guide.md)
    - [bochk-guide.md](docs/01-hk-bank-account/bochk-guide.md)
    - [za-bank-guide.md](docs/01-hk-bank-account/za-bank-guide.md)
    - [za-bank-funding-guide.md](docs/01-hk-bank-account/za-bank-funding-guide.md)
    - [ant-bank-guide.md](docs/01-hk-bank-account/ant-bank-guide.md)
    - [airstar-guide.md](docs/01-hk-bank-account/airstar-guide.md)
    - [icbc-asia-guide.md](docs/01-hk-bank-account/icbc-asia-guide.md)
    - [scb-guide.md](docs/01-hk-bank-account/scb-guide.md)
    - [comparison.md](docs/01-hk-bank-account/comparison.md)
    - [hk-bank-maintenance-guide.md](docs/01-hk-bank-account/hk-bank-maintenance-guide.md)
  - 02-payments/
    - [README.md](docs/02-payments/README.md)
    - [stripe.md](docs/02-payments/stripe.md)
    - [wise.md](docs/02-payments/wise.md)
- 根目录：
  - [CONTRIBUTING.md](CONTRIBUTING.md)
  - [LICENSE](LICENSE)

## 🤝 参与贡献
- 阅读并遵循：[CONTRIBUTING.md](CONTRIBUTING.md)。
- PR 请说明「动机 / 变更点 / 截图（如有）」；一次 PR 聚焦一个主题。

## 📄 许可协议
本项目采用 MIT 许可证，详见 `LICENSE`。

## ⚠️ 免责声明
- 本仓库仅供学习与信息参考，不构成法律、财税或投资建议；请以银行/支付机构官方最新政策为准。
- 任何办理、开户、收款流程均需遵守所在地及目的地法律法规，请谨慎合规操作。
- 请勿提交、留存或截图包含个人隐私与敏感信息的材料。


## 💰 打赏 Buy Me A Coffee

如果该项目帮助了您，请作者喝杯咖啡吧 ☕️

### WeChat

<img src="docs/assets/wechat-reward-code.jpg" alt="微信打赏码" width="200" />

## 🧑‍💻 作者
- 作者：`geekjourneyx`
- X（Twitter）：https://x.com/seekjourney
- 公众号：极客杰尼

关注公众号，获取更多 AI 编程、AI 工具与 AI 出海建站的实战分享：

<p>
  <img src="./docs/assets/qrcode.jpg" alt="公众号：极客杰尼" width="180" />
</p>
- [Ideoy](https://ideoy.ai) - Remake this week's meme videos with one selfie (AI image-to-video, freemium, adults only).
