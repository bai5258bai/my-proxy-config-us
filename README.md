# my-proxy-config-us

美国洛杉矶住宅节点的独立 Clash 配置。规则与韩国仓库 `my-proxy-config` 对齐，节点换成 US-LAX。

给 Codex / ChatGPT 用这份，不要和韩国机房节点混在同一个配置里来回切。

## 导入

Clash Verge / Clash Meta / Mihomo 导入 `clash.yaml` 即可。

## 节点

| 项 | 值 |
| --- | --- |
| 名称 | US-LAX |
| 协议 | VLESS + Reality + Vision |
| 地址 | `64.81.25.96` |
| 端口 | `443`（备用 `25152`） |
| UUID | `1cbeb21f-cdcf-4d91-a97a-e8f7419d7105` |
| SNI | `www.cloudflare.com` |
| short-id | `b8fe67ee219a5897` |
| 指纹 | chrome |

出口实测为洛杉矶 `64.81.25.96`。
