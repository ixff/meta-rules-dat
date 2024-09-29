## 说明

1. 适用于 Pter 的代理规则列表。~~妈妈再也不用担心我的tracker走代理而被标盒啦。~~
2. 相比原仓库的变化：完善了 [category-pt](https://github.com/ixff/domain-list-community/blob/master/data/category-pt) 类别。
3. 使用方法：
   
   PT 涉及到的类别 `category-pt`、`category-pt@!cn` ，使用方法见[⬇原仓库README](#原仓库README)。
   
   mihomo内核还可以搭配 [`applications`](https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/applications.txt) 类别使用，方法见 [Loyalsoldier/clash-rules](https://github.com/Loyalsoldier/clash-rules?tab=readme-ov-file#%E4%BD%BF%E7%94%A8%E6%96%B9%E5%BC%8F)。
   
4. 如果你发现缺少某些站点域名或其tracker域名，请[到 ixff/domain-list-community 仓库提issue](https://github.com/ixff/domain-list-community/issues/new?assignees=&labels=&projects=&template=%E5%9F%9F%E5%90%8D%E6%9B%B4%E6%96%B0.md&title=%E3%80%90%E5%9F%9F%E5%90%8D%E6%9B%B4%E6%96%B0%E3%80%91XXX)，维护该列表需要大家的共同努力。


<details>
<summary><H1>原仓库README</H1></summary>

## **下载地址**：

| 文件名              | Github release                                                                                                            | JSdelivr                                                                                                                           | JSdelivr-CF                                                                                                                              |
|---------------------|---------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| country.mmdb        | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/country.mmdb)                                 | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/country.mmdb)                                                  | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/country.mmdb)                                                  |
| geoip.dat           | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip.dat)                                    | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip.dat)                                                       | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip.dat)                                                       |
| geoip.db            | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip.db)                                     | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip.db)                                                        | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip.db)                                                        |
| geoip.metadb        | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip.metadb)                                 | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip.metadb)                                                    | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip.metadb)                                                    |
| country-lite.mmdb   | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/country-lite.mmdb)                            | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/country-lite.mmdb)                                               | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/country-lite.mmdb)                                               |
| geoip-lite.dat      | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip-lite.dat)                               | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip-lite.dat)                                                  | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip-lite.dat)                                                  |
| geoip-lite.db       | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip-lite.db)                                | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip-lite.db)                                                   | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geoip-lite.db)                                                   |
| geosite.dat         | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geosite.dat)                                  | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite.dat)                                                     | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite.dat)                                                     |
| geosite.db          | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geosite.db)                                   | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite.db)                                                      | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite.db)                                                      |
| geosite-lite.dat    | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geosite-lite.dat)                             | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite-lite.dat)                                                 | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite-lite.dat)                                                 |
| geosite-lite.db     | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geosite-lite.db)                              | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite-lite.db)                                                 | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/geosite-lite.db)                                                 |
| GeoLite2-ASN.mmdb   | [下载](https://github.com/MetaCubeX/meta-rules-dat/releases/download/latest/GeoLite2-ASN.mmdb)                              | [下载](https://cdn.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/GeoLite2-ASN.mmdb)                                                 | [下载](https://testingcf.jsdelivr.net/gh/MetaCubeX/meta-rules-dat@release/GeoLite2-ASN.mmdb)                                                 |

### **rule-set**

mihomo：[meta branch](https://github.com/MetaCubeX/meta-rules-dat/tree/meta)

sing-box: [sing branch](https://github.com/MetaCubeX/meta-rules-dat/tree/sing)

## **country.mmdb,geoip.dat,geoip.db 内容**

同 [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)

- 新增类别（方便有特殊需求的用户使用）：
  - `geoip:cloudflare`
  - `geoip:cloudfront`
  - `geoip:facebook`
  - `geoip:fastly`
  - `geoip:google`
  - `geoip:netflix`
  - `geoip:telegram`
  - `geoip:twitter`

## **country-lite.mmdb,geoip-lite.dat,geoip-lite.db 内容**

国家仅包含 CN/JP,精简体积,替换一些类别

- 新增类别（方便有特殊需求的用户使用）：
  - `geoip:cloudflare`
  - `geoip:cloudfront`
  - `geoip:facebook`
  - `geoip:bilibili`
  - `geoip:google`
  - `geoip:netflix`
  - `geoip:telegram`
  - `geoip:twitter`
  - `geoip:apple`

## **geosite.dat,geosite.db 内容**

用法同 [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)

- `geosite:category-ads-all` 仅使用域名作为广告拦截用途作用有限，因此不作额外域名添加
- `geosite:cn` 源替换为 [ios_rule_script/ChinaMax_Domain](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ChinaMax)
- `geosite:onedrive` 合并 [ios_rule_script/OneDrive](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/OneDrive)
- `geosite:steam@cn` 合并 [ios_rule_script/SteamCN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/SteamCN) 的内数据
- 新增类别 - `geosite:biliintl` 来源 [biliintl](https://raw.githubusercontent.com/xishang0128/rules/main/biliintl.list) - `geosite:tracker` 来源 [TrackersList](https://trackerslist.com/#/zh)以及[blackmatrix7
  /
  ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/PrivateTracker)

## **geosite-lite.dat,geosite-lite.db 内容**

仅包含常用集合，cn 为精简集合，可能不全
集合内容均来自 https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash

集合包含 `abema / apple / applemusic / bilibili / biliintl / bahamut / cn / ehentai / google / github / microsoft / netflix / openai / onedrive / pixiv / proxy / spotify / telegram / twitter / tiktok / youtube / proxymedia`

## **示例**

```yaml
rule-providers:
  cn:
    behavior: domain
    interval: 86400
    path: ./provider/rule-set/cn_domain.yaml
    type: http
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/cn.yaml"

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

  #GEOIP 规则
  - GEOIP,private,DIRECT,no-resolve
  - GEOIP,telegram,PROXY
  - GEOIP,JP,PROXY
  - GEOIP,CN,DIRECT
  - DST-PORT,80/8080/443/8443,PROXY
  - MATCH,DIRECT
```

## 辅助工具

https://github.com/MetaCubeX/geo

🗺 An easy way to manage all your Geo resources.

## 致谢

- [@Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)
- [@v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- [@Loyalsoldier/domain-list-custom](https://github.com/Loyalsoldier/domain-list-custom)
- [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
- [@gfwlist/gfwlist](https://github.com/gfwlist/gfwlist)
- [@cokebar/gfwlist2dnsmasq](https://github.com/cokebar/gfwlist2dnsmasq)
- [@Loyalsoldier/cn-blocked-domain](https://github.com/Loyalsoldier/cn-blocked-domain)
- [@AdblockPlus/EasylistChina+Easylist.txt](https://easylist-downloads.adblockplus.org/easylistchina+easylist.txt)
- [@AdGuard/DNS-filter](https://kb.adguard.com/en/general/adguard-ad-filters#dns-filter)
- [@PeterLowe/adservers](https://pgl.yoyo.org/adservers)
- [@DanPollock/hosts](https://someonewhocares.org/hosts)
- [@crazy-max/WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker)
- [@blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)

</details>
