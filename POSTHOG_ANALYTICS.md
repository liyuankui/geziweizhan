# PostHog Analytics · geziweizhan（各自为战）

Project property: `geziweizhan` · EU ingest（与家族共用项目采集键）· 注册表：`~/Notebooks/context/prompt/POSTHOG_USAGE_GUIDE.md`

| 事件 | 属性 | 触发 |
|------|------|------|
| `page_view` | `ref` · `sport`（pp/bd） | 页面加载 |
| `page_leave` | `dwell_ms`（累计可见毫秒）· `scroll_pct`（最大滚动 0-100） | 页面隐藏/关闭时上报——时长与首屏留存 |
| `sport_switch` | `from` · `to` | 顶栏切换运动 tab |
| `nav_click` | `to`（bd-* 同构） · `sport` | 导航锚点 |
| `share_copy` | — | 复制分享文案 |

分析口径：`nav_click` 分布 = 哪个板块最被需要；`ref` 看家族互链与外部引流。
