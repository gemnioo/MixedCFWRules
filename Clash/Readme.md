March 31. 2023 Friday 

避免带来不必要的麻烦 把最近几天折腾& Surge； Quantumult X； Clash for Window 记录一下

#原因是大部分“大佬”维护的规则 策略组 IP池都太繁复了 小白遇到问题很难修改规则#
#另外 Surge 最先发明了策略组 现在一般看到复杂的策略组套策略组 因为Rule set 或者 filter remote  等等存在 更加难以一次性直观的修改rules#
#另外 特别吐槽一下 Quantumult 的规则顺序 默认先加载本地而后是remote  "DOMAIN-KEYWORD 规则优先级带来的问题"  https://blog.hly0928.com/post/talk-about-some-proxy-apps-on-ios/   并不是像另外两个软件 直观的按照 rules 内的顺序 (本地和Github仓库可穿插 #


## !! 自用不需要 模块以及开启MitM Rewriter 有这两种需求的请参阅其他教程 通过大量规则屏蔽广告证明不如用浏览器插件 或者Adguard？ 没有解锁TikTok的需求 也不捋羊毛 知乎微博基本不上

# 机场节点订阅的问题
Clash for Windows 遇到 proxy provider health-check error: key 'type' missing  
https://github.com/vernesong/OpenClash/issues/978


# proxy group[1]: `use` or `proxies` missing 
https://github.com/vernesong/OpenClash/issues/874
原因格式？问题  查看右键 proxies 后发现节点无法拖入到部分策略组 
客户端 左侧 proxies --- 选择你编辑导入的 yaml 配置文件---右键proxies 删除所有你无法加入策略&节点的策略组  然后重新创建 保存
