# ROADMAP · go-web-statistics

> 上游目前为空仓。本文件锁定 MVP。

## 定位

可私有化部署的 Golang Web 流量统计（采集 → 聚合 → 看板）。

## 里程碑

| 阶段 | 内容 | 验收 |
|---|---|---|
| M1 | 事件 schema + `.env.example` | 文档齐全 |
| M2 | beacon / JS SDK + 写入 API | curl 写入成功 |
| M3 | PV/UV/来源简易看板 | 本地可看数 |
| M4 | Compose + CSV 导出 | 一键部署样例 |

## 明确不做

- 刷 UV / 假点击
- 未授权采集第三方站点

## 定制入口

微信 **qingbao199101**（备注：Go流量统计）｜ wuxiumu@163.com
