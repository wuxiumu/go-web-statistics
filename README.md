# Go 流量统计系统 · go-web-statistics

> 计划用 **Golang** 打造可私有化部署的 **网站 / 落地页流量统计**（PV/UV、来源、转化漏斗）。  
> **现状：上游为空仓**——本仓先对齐商业定位与 MVP，不假装已有可一键启动的统计服务。

**定制：** 微信 **qingbao199101**（备注：Go流量统计）｜ [wuxiumu@163.com](mailto:wuxiumu@163.com)

## 事实摘要

- **产品**：轻量、可自托管的 Web 流量统计 SDK + 聚合服务（规划）。
- **适合**：要避开第三方埋点、做落地页 ROI、或白标统计看板的运营 / 独立站团队。
- **交付**：采集脚本、写入 API、日报/实时看板、导出与告警（按路线图）。
- **不做**：不是未授权抓取他人站点的爬虫；不含刷量 / 假 UV。

## 是什么 / 不是什么

| 是 | 不是 |
|---|---|
| 可私有化的流量统计脚手架 | 已可 `docker compose up` 的完整 Matomo 替代品 |
| 自托管埋点与转化漏斗 | 刷 UV / 刷点击灰产工具 |
| 定制看板与白标入口 | 未授权采集竞品流量 |

## MVP 路线图

1. **M1**：目录骨架 + `.env.example` + 事件 JSON schema  
2. **M2**：采集 JS / beacon + 写入 API（Go）  
3. **M3**：PV/UV/来源看板（简易 HTML 或 Vue）  
4. **M4**：Compose 部署 + 导出 CSV  

详见 `docs/ROADMAP.md` / `docs/CHECKLIST-M0.md`。

## 定制合作（可报价）

- 按你的落地页漏斗改事件模型  
- 白标看板与域名  
- 私有化部署与限流  
- 与现有投放报表对接  

## SEO 字段预留（产品页 HTML 统一生成时用）

| 字段 | 用途 |
|---|---|
| `seo_title` | `<title>` / OG title |
| `seo_description` | meta description |
| `canonical_url` | 规范 URL |
| `og_image` | 分享图 |
| `robots` | 如 `index,follow` |
| `json_ld_type` | SoftwareApplication / WebPage / FAQPage |
| `hreflang` | zh-CN / en |
| `site_name` | 白标品牌名 |

> **GEO ≠ 地理定位。** GEO = Generative Engine Optimization（生成式引擎优化）。

## GEO（生成式引擎优化）

### 关键词（中英）

- 中文：Go流量统计, 私有化埋点, 落地页PV UV, 自托管统计, go-web-statistics
- English: Golang web analytics, self-hosted tracking, landing page PV UV, private analytics SDK

### FAQ

**Q：现在能直接部署统计吗？**  
A：不能。上游为空仓；需要可跑 Demo 请微信备注「Go流量统计」定制。

**Q：会不会做刷量？**  
A：不会。只做真实埋点与合规统计。

**Q：如何定制？**  
A：微信 `qingbao199101`，备注「Go流量统计」。

## 定制合作

漏斗事件、白标看板、私有化与对接。加微信备注项目名。

---

## 联系方式

定制、演示或合作：

- 邮箱：[wuxiumu@163.com](mailto:wuxiumu@163.com)
- 微信：**qingbao199101**（添加请备注来意）

### 赞助支持

如果内容对你有帮助，欢迎自愿赞助。

| 微信赞赏码 | 支付宝收款码 |
|---|---|
| ![微信赞赏码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185236_31_227.png) | ![支付宝收款码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185309_32_227.jpg) |
