# my-proxy-config-us

美国洛杉矶节点的独立 Clash 配置。规则与韩国仓库 `my-proxy-config` 对齐。

给 Codex / ChatGPT 用这份，不要和韩国机房节点混在同一个配置里来回切。

## 导入

Clash Verge / Clash Meta / Mihomo 导入下面的订阅链接即可：

https://raw.githubusercontent.com/bai5258bai/my-proxy-config-us/main/clash.yaml

## 节点

### US-LAX-ISP（默认）

YinNet 美国双 ISP 新机器，出口为洛杉矶。

| 项 | 值 |
| --- | --- |
| 名称 | US-LAX-ISP |
| 协议 | VLESS + Reality + Vision |
| 地址 | `216.167.74.215` |
| 端口 | `443`（备用 `25152`） |
| UUID | `f4e65f0a-47b4-4033-8f90-bfb692b83ce6` |
| SNI | `www.cloudflare.com` |
| short-id | `57e267ef74b481da` |
| 指纹 | chrome |

### US-LAX（保留）

原洛杉矶住宅节点，443 端口仍可连通，配置里先保留。若已不再使用，可以说一声，我再从仓库里去掉。

| 项 | 值 |
| --- | --- |
| 名称 | US-LAX |
| 协议 | VLESS + Reality + Vision |
| 地址 | `64.81.25.96` |
| 端口 | `443` |
| UUID | `1cbeb21f-cdcf-4d91-a97a-e8f7419d7105` |
| SNI | `www.cloudflare.com` |
| short-id | `b8fe67ee219a5897` |
| 指纹 | chrome |
