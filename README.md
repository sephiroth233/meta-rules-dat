# meta-rules-dat

面向 mihomo/Clash Meta 与 sing-box 的自用 Geo 规则构建仓库。项目基于多个公开规则源生成 `geoip`、`geosite`、`rule-set` 与 `mmdb` 产物，并在本仓库的 `release`、`meta`、`sing` 分支和 `latest` Release 中发布。

## 下载地址

| 文件名 | GitHub Release | jsDelivr | jsDelivr-CF |
| --- | --- | --- | --- |
| `country.mmdb` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/country.mmdb) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/country.mmdb) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/country.mmdb) |
| `country-lite.mmdb` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/country-lite.mmdb) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/country-lite.mmdb) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/country-lite.mmdb) |
| `geoip.dat` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geoip.dat) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip.dat) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip.dat) |
| `geoip-lite.dat` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geoip-lite.dat) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip-lite.dat) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip-lite.dat) |
| `geoip.db` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geoip.db) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip.db) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip.db) |
| `geoip-lite.db` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geoip-lite.db) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip-lite.db) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip-lite.db) |
| `geoip.metadb` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geoip.metadb) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip.metadb) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip.metadb) |
| `geoip-lite.metadb` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geoip-lite.metadb) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip-lite.metadb) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geoip-lite.metadb) |
| `geosite.dat` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geosite.dat) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite.dat) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite.dat) |
| `geosite-lite.dat` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geosite-lite.dat) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite-lite.dat) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite-lite.dat) |
| `geosite.db` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geosite.db) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite.db) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite.db) |
| `geosite-lite.db` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/geosite-lite.db) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite-lite.db) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/geosite-lite.db) |
| `GeoLite2-ASN.mmdb` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/GeoLite2-ASN.mmdb) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/GeoLite2-ASN.mmdb) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/GeoLite2-ASN.mmdb) |
| `BundleMRS.7z` | [下载](https://github.com/sephiroth233/meta-rules-dat/releases/download/latest/BundleMRS.7z) | [下载](https://cdn.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/BundleMRS.7z) | [下载](https://testingcf.jsdelivr.net/gh/sephiroth233/meta-rules-dat@release/BundleMRS.7z) |

每个 Release 产物同时提供对应的 `.sha256sum` 校验文件。

## rule-set 分支

| 客户端 | 分支 | 说明 |
| --- | --- | --- |
| mihomo / Clash Meta | [`meta`](https://github.com/sephiroth233/meta-rules-dat/tree/meta) | `.mrs` rule-set，目录包含 `geo/geosite`、`geo/geoip`、`geo-lite/geosite`、`geo-lite/geoip` 与 `asn` |
| sing-box | [`sing`](https://github.com/sephiroth233/meta-rules-dat/tree/sing) | sing-box `.srs` rule-set，目录结构与 `meta` 分支一致 |
| 通用二进制产物 | [`release`](https://github.com/sephiroth233/meta-rules-dat/tree/release) | `dat`、`db`、`metadb`、`mmdb`、`BundleMRS.7z` 与校验文件 |

示例 rule-set 地址：

```yaml
rule-providers:
  cn:
    type: http
    behavior: domain
    format: mrs
    interval: 86400
    path: ./provider/rule-set/geosite-cn.mrs
    url: "https://raw.githubusercontent.com/sephiroth233/meta-rules-dat/meta/geo/geosite/cn.mrs"
```

## 产物说明

### GeoIP

`geoip.dat`、`geoip.db`、`geoip.metadb` 与 `country.mmdb` 主要沿用 [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip) 数据。

额外可用类别包括：

- `geoip:cloudflare`
- `geoip:cloudfront`
- `geoip:facebook`
- `geoip:fastly`
- `geoip:google`
- `geoip:netflix`
- `geoip:telegram`
- `geoip:twitter`

### GeoIP Lite

`geoip-lite.dat`、`geoip-lite.db`、`geoip-lite.metadb` 与 `country-lite.mmdb` 使用精简数据，国家维度主要保留 CN/JP，并补充常用服务商类别：

- `geoip:apple`
- `geoip:bilibili`
- `geoip:cloudflare`
- `geoip:cloudfront`
- `geoip:facebook`
- `geoip:google`
- `geoip:netflix`
- `geoip:telegram`
- `geoip:twitter`

### GeoSite

`geosite.dat` 与 `geosite.db` 基于 [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community) 和 [Loyalsoldier/domain-list-custom](https://github.com/Loyalsoldier/domain-list-custom) 构建，并按本项目需求做以下调整：

- `geosite:cn` 使用 [blackmatrix7/ios_rule_script ChinaMax](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ChinaMax) 作为主要来源。
- `geosite:geolocation-!cn` 合并 GFWList、Google/Apple 中国域名、`domain-list-custom` 等来源，并移除 `.cn` 结尾域名。
- 新增或覆盖 `google-cn`、`apple-cn`、`gfw`、`win-spy`、`win-update`、`win-extra`。
- `geosite:steam@cn` 合并 [SteamCN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/SteamCN) 数据。
- 新增 `geosite:biliintl`、`geosite:sharepoint`、`geosite:tracker`、`geosite:httpdns`。
- 合并 [sephiroth233/Tool](https://github.com/sephiroth233/Tool) 中的 `AI`、`Emby` 规则到对应 geosite 分类。
- `geosite:category-ads-all` 仍主要依赖域名规则；仅用域名做广告拦截效果有限，建议配合客户端自身能力使用。

### GeoSite Lite

`geosite-lite.dat` 与 `geosite-lite.db` 只保留常用集合，`cn` 集合更精简，覆盖范围不等同于完整版。

当前主要包含：

`abema`、`apple`、`applemusic`、`bilibili`、`biliintl`、`bahamut`、`cn`、`cloudflare`、`ehentai`、`google`、`github`、`microsoft`、`netflix`、`openai`、`onedrive`、`pixiv`、`private`、`proxy`、`spotify`、`telegram`、`twitter`、`tiktok`、`youtube`、`proxymedia`。

## 自动构建

GitHub Actions 会在以下场景触发构建：

- 每天 06:30（UTC+8）定时构建。
- 手动执行 `workflow_dispatch`。
- 推送到 `master` 且变更不只是 `README.md`。

构建流程概要：

1. 拉取 `domain-list-community`、`domain-list-custom`、`meta-rules-converter`、`gfwlist2dnsmasq`、`sephiroth233/Tool` 等数据源。
2. 生成并清理 `cn`、`geolocation-!cn`、`google-cn`、`apple-cn`、`gfw` 等 geosite 数据。
3. 构建完整版与 lite 版 `geosite.dat`。
4. 下载或转换 `geoip`、`country.mmdb`、`db`、`metadb`。
5. 转换为 mihomo `.mrs` 与 sing-box `.srs` rule-set。
6. 发布 `latest` Release，并强制更新 `release`、`meta`、`sing` 分支。
7. 清理 jsDelivr CDN 缓存。

## 自定义规则维护

自定义列表位于 `resouces/` 目录。目录名沿用仓库历史拼写。

| 文件 | 作用 |
| --- | --- |
| `resouces/direct.txt` | 追加到 `cn` / DIRECT 域名集合 |
| `resouces/proxy.txt` | 追加到 `geolocation-!cn` / PROXY 域名集合 |
| `resouces/direct-need-to-remove.txt` | 从生成后的 DIRECT 集合中移除指定域名 |
| `resouces/proxy-need-to-remove.txt` | 从生成后的 PROXY 集合中移除指定域名 |
| `resouces/reject.txt` | 预留的 REJECT 追加列表，当前自动构建流程未启用 |
| `resouces/reject-need-to-remove.txt` | 预留的 REJECT 移除列表，当前自动构建流程未启用 |

维护建议：

- 每行一个域名，推荐使用裸域名，例如 `example.com`。
- `direct.txt` 与 `proxy.txt` 会参与去重、移除和排序，再写入对应 geosite 数据。
- `full:`、`keyword:`、`regexp:` 等特殊前缀的保留逻辑主要来自上游 `domain-list-custom`，不建议直接写入这些自定义追加列表。
- 修改 `direct.txt`、`proxy.txt` 或 `*-need-to-remove.txt` 后，推送到 `master` 即可触发自动构建。

## 辅助脚本

| 脚本 | 说明 |
| --- | --- |
| `resouces/findRedundantDomain.py` | 查找冗余子域名，例如已有 `example.com` 时标记 `www.example.com` |
| `resouces/removeFrom.py` | 从一个列表中移除另一个列表包含的条目 |
| `resouces/convert.sh` | 本地将 `geoip.dat`、`geosite.dat` 转换为 sing-box `.srs`，需要 `mosdns` 与 `sing-box` 可执行文件 |
| `resouces/convert-clash.sh` | 本地将 `geoip.dat`、`geosite.dat` 解包为 Clash/Mihomo 可用的 `.yaml` payload |
| `resouces/bm7.sh` | 将 blackmatrix7 Clash 规则整理并转换为 sing-box rule-set；当前 GitHub Actions 中未启用 |

示例：

```bash
python ./resouces/removeFrom.py \
  -remove ./resouces/proxy-need-to-remove.txt \
  -from ./proxy-list-without-redundant \
  -out ./temp-geolocation-\!cn.txt
```

## mihomo 示例

```yaml
rule-providers:
  cn:
    type: http
    behavior: domain
    format: mrs
    interval: 86400
    path: ./provider/rule-set/geosite-cn.mrs
    url: "https://raw.githubusercontent.com/sephiroth233/meta-rules-dat/meta/geo/geosite/cn.mrs"

dns:
  nameserver-policy:
    "geosite:cn,private,apple":
      - https://doh.pub/dns-query
      - https://dns.alidns.com/dns-query
    "geosite:category-ads-all": rcode://success

rules:
  - RULE-SET,cn,DIRECT
  - GEOSITE,category-ads-all,REJECT
  - GEOSITE,private,DIRECT
  - GEOSITE,youtube,PROXY
  - GEOSITE,google,PROXY
  - GEOSITE,twitter,PROXY
  - GEOSITE,pixiv,PROXY
  - GEOSITE,category-scholar-!cn,PROXY
  - GEOSITE,biliintl,PROXY
  - GEOSITE,onedrive,DIRECT
  - GEOSITE,microsoft@cn,DIRECT
  - GEOSITE,apple-cn,DIRECT
  - GEOSITE,steam@cn,DIRECT
  - GEOSITE,category-games@cn,DIRECT
  - GEOSITE,geolocation-!cn,PROXY
  - GEOSITE,cn,DIRECT
  - GEOIP,private,DIRECT,no-resolve
  - GEOIP,telegram,PROXY
  - GEOIP,JP,PROXY
  - GEOIP,CN,DIRECT
  - DST-PORT,80/8080/443/8443,PROXY
  - MATCH,DIRECT
```

## 相关工具

- [MetaCubeX/geo](https://github.com/MetaCubeX/geo)：Geo 资源转换与管理工具。
- [MetaCubeX/meta-rules-converter](https://github.com/MetaCubeX/meta-rules-converter)：将 Geo 资源转换为 rule-set。

## 致谢

- [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)
- [Loyalsoldier/domain-list-custom](https://github.com/Loyalsoldier/domain-list-custom)
- [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- [felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
- [gfwlist/gfwlist](https://github.com/gfwlist/gfwlist)
- [cokebar/gfwlist2dnsmasq](https://github.com/cokebar/gfwlist2dnsmasq)
- [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)
- [xishang0128/geoip](https://github.com/xishang0128/geoip)
- [xishang0128/rules](https://github.com/xishang0128/rules)
- [crazy-max/WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker)
- [MetaCubeX/meta-rules-dat](https://github.com/MetaCubeX/meta-rules-dat)
