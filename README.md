;Custom_OpenClash_Rules
;全分组防DNS泄漏订阅转换模板
;作者：https://github.com/Aethersailor
;基于 ACL4SSR 模板魔改而来
;项目地址：https://github.com/Aethersailor/Custom_OpenClash_Rules
;强烈建议搭配本项目配套教程，实现最佳化的 OpenClash 使用效果！
;教程：https://github.com/Aethersailor/Custom_OpenClash_Rules/wiki/OpenClash-%E8%AE%BE%E7%BD%AE%E6%96%B9%E6%A1%88
;有问题可提 issue，或者加入本项目 Telegram 群组进行讨论
;Telegram 群组：https://t.me/custom_openclash_rules_group
;Telegram 通知频道：https://t.me/custom_openclash_rules

[custom]
;设置规则标志位
;以下规则，按照从上往下的顺序遍历，优先命中上位规则
;修改顺序会影响分流效果

ruleset=🎯 全球直连,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Lan/Lan.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Direct/Direct.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/Aethersailor/Custom_OpenClash_Rules/main/rule/Custom_Direct.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/Aethersailor/Custom_OpenClash_Rules/main/rule/Custom_Proxy.list
ruleset=📢 谷歌FCM,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GoogleFCM/GoogleFCM.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/GoogleCN.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/GoogleCNProxyIP.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/SteamCN/SteamCN.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/Aethersailor/Custom_OpenClash_Rules/main/rule/Steam_CDN.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/PrivateTracker/PrivateTracker.list
ruleset=📲 Telegram,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Telegram/Telegram.list
ruleset=🕊️ Twitter(X),https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Twitter/Twitter.list
ruleset=💬 ChatGPT,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/OpenAI/OpenAI.list
ruleset=💬 Copilot,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Copilot/Copilot.list
ruleset=🚀 GitHub,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GitHub/GitHub.list
ruleset=🚀 测速工具,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Speedtest/Speedtest.list
ruleset=🍎 苹果服务,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Apple/Apple.list
ruleset=Ⓜ️ 微软服务,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Microsoft/Microsoft.list
ruleset=📹 YouTube,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/YouTube/YouTube.list
ruleset=🇬 谷歌服务,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Google/Google.list
ruleset=🍘️ 小米服务,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/XiaoMi/XiaoMi.list
ruleset=🎶 TikTok,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/TikTok/TikTok.list
ruleset=🎥 Netflix,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Netflix/Netflix.list
ruleset=🎥 DisneyPlus,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Disney/Disney.list
ruleset=🎥 HBO,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/HBO/HBO.list
ruleset=🎥 Emby,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Emby/Emby.list
ruleset=🎻 Spotify,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Spotify/Spotify.list
ruleset=📺 Bahamut,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Bahamut/Bahamut.list
ruleset=🎶 网易音乐,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/NetEaseMusic/NetEaseMusic.list
ruleset=📺 国内媒体,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/ChinaMedia/ChinaMedia.list
ruleset=🌎 国外媒体,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GlobalMedia/GlobalMedia.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Epic/Epic.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/EA/EA.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Blizzard/Blizzard.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/UBI/UBI.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Sony/Sony.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Nintendo/Nintendo.list
ruleset=🎮 Steam,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Steam/Steam.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaDomain.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaCompanyIp.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaIp.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Download/Download.list
ruleset=🎯 全球直连,[]GEOSITE,category-public-tracker
ruleset=🎯 全球直连,[]GEOIP,LAN,no-resolve
ruleset=🎯 全球直连,[]GEOIP,CN,no-resolve
ruleset=🐟 漏网之鱼,[]FINAL
;设置规则标志位结束

;设置节点分组标志位
custom_proxy_group=🚀 节点选择`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]♻️ 自动选择`[]🚀 手动切换
custom_proxy_group=🚀 手动切换`select`.*
custom_proxy_group=♻️ 自动选择`url-test`.*`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🚀 GitHub`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连
custom_proxy_group=📲 Telegram`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换
custom_proxy_group=🕊️ Twitter(X)`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=💬 ChatGPT`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=💬 Copilot`select`[]🇺🇸 美国节点`[]🇭🇰 香港节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连`.*
custom_proxy_group=🎶 TikTok`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连`.*
custom_proxy_group=📹 YouTube`select`[]🇸🇬 新加坡节点`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=🎥 Netflix`select`[]🇸🇬 新加坡节点`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=🎥 DisneyPlus`select`[]🇸🇬 新加坡节点`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=🎥 HBO`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连`.*
custom_proxy_group=🎥 Emby`select`[]🎯 全球直连`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=🎻 Spotify`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连`.*
custom_proxy_group=📺 Bahamut`select`[]🇹🇼 台湾节点`[]🚀 节点选择`[]🚀 手动切换`[]🎯 全球直连
custom_proxy_group=🎶 网易音乐`select`[]🎯 全球直连`[]🚀 节点选择`[]♻️ 自动选择`(网易|音乐|解锁|Music|NetEase)
custom_proxy_group=📺 国内媒体`select`[]🎯 全球直连`[]🇹🇼 台湾节点`[]🇭🇰 香港节点
custom_proxy_group=🌎 国外媒体`select`[]🇸🇬 新加坡节点`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连`.*
custom_proxy_group=📢 谷歌FCM`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连
custom_proxy_group=🇬 谷歌服务`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连
custom_proxy_group=🍎 苹果服务`select`[]🎯 全球直连`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换
custom_proxy_group=Ⓜ️ 微软服务`select`[]🎯 全球直连`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换
custom_proxy_group=🍘️ 小米服务`select`[]🎯 全球直连`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换
custom_proxy_group=🎮 游戏平台`select`[]🎯 全球直连`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换
custom_proxy_group=🎮 Steam`select`[]🎯 全球直连`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=🚀 测速工具`select`[]🎯 全球直连`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`.*
custom_proxy_group=🐟 漏网之鱼`select`[]🇭🇰 香港节点`[]🇺🇸 美国节点`[]🇯🇵 日本节点`[]🇸🇬 新加坡节点`[]🇹🇼 台湾节点`[]🇰🇷 韩国节点`[]🇨🇦 加拿大节点`[]🇬🇧 英国节点`[]🇫🇷 法国节点`[]🇩🇪 德国节点`[]🇳🇱 荷兰节点`[]🇹🇷 土耳其节点`[]🇻🇳 越南节点`[]🚀 节点选择`[]♻️ 自动选择`[]🚀 手动切换`[]🎯 全球直连`.*
custom_proxy_group=🎯 全球直连`select`[]DIRECT
custom_proxy_group=🇭🇰 香港节点`url-test`(港|HK|hk|Hong Kong|HongKong|hongkong|深港)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇺🇸 美国节点`url-test`(美|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|US|United States|UnitedStates)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇯🇵 日本节点`url-test`(日本|川日|东京|大阪|泉日|埼玉|沪日|深日|[^-]日|JP|Japan)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇸🇬 新加坡节点`url-test`(新加坡|坡|狮城|SG|Singapore)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇹🇼 台湾节点`url-test`(台|新北|彰化|TW|Taiwan)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇰🇷 韩国节点`url-test`(KR|Korea|KOR|首尔|韩|韓)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇨🇦 加拿大节点`url-test`(加拿大|Canada|渥太华|温哥华|卡尔加里)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇬🇧 英国节点`url-test`(英国|Great Britain)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇫🇷 法国节点`url-test`(法国|France|巴黎)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇩🇪 德国节点`url-test`(德国|Germany|柏林|法兰克福)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇳🇱 荷兰节点`url-test`(荷兰|Netherlands|阿姆斯特丹)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇹🇷 土耳其节点`url-test`(土耳其|Turkey|Türkiye)`http://cp.cloudflare.com/generate_204`300,,50
;custom_proxy_group=🇮🇳 印度节点`url-test`(印度|India|新德里|孟买)`http://cp.cloudflare.com/generate_204`300,,50
custom_proxy_group=🇻🇳 越南节点`url-test`(越南|Vietnam)`http://cp.cloudflare.com/generate_204`300,,50
;设置分组标志位

;下方参数请勿修改
enable_rule_generator=true
overwrite_original_rules=true
