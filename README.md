  geoip: https://github.com/mengxianbo/pp-clash/blob/main/GeoIP.dat
  
  geosite: https://github.com/mengxianbo/pp-clash/blob/main/GeoSite.dat
  
  mmdb: https://github.com/mengxianbo/pp-clash/blob/main/Country.mmdb

  rules:
  - DOMAIN,dl.google.com,🎯 全球直连
  - DOMAIN,origin-a.akamaihd.net,🎯 全球直连
  - DOMAIN,fairplay.l.qq.com,🎯 全球直连
  - DOMAIN,livew.l.qq.com,🎯 全球直连
  - DOMAIN,vd.l.qq.com,🎯 全球直连
  - DOMAIN,errlog.umeng.com,🎯 全球直连
  - DOMAIN,msg.umeng.com,🎯 全球直连
  - DOMAIN,msg.umengcloud.com,🎯 全球直连
  - DOMAIN,tracking.miui.com,🎯 全球直连
  - DOMAIN,app.adjust.com,🎯 全球直连
  - DOMAIN,bdtj.tagtic.cn,🎯 全球直连
  - DOMAIN,rewards.hypixel.net,🎯 全球直连
  - DOMAIN,instant.arubanetworks.com,🎯 全球直连
  - DOMAIN,setmeup.arubanetworks.com,🎯 全球直连
  - DOMAIN,router.asus.com,🎯 全球直连
  - DOMAIN,www.asusrouter.com,🎯 全球直连
  - DOMAIN-KEYWORD,360buy,🎯 全球直连
  - DOMAIN-KEYWORD,alicdn,🎯 全球直连
  - DOMAIN-KEYWORD,alimama,🎯 全球直连
  - DOMAIN-KEYWORD,alipay,🎯 全球直连
  - DOMAIN-KEYWORD,appzapp,🎯 全球直连
  - DOMAIN-KEYWORD,baidupcs,🎯 全球直连
  - DOMAIN-KEYWORD,bilibili,🎯 全球直连
  - DOMAIN-KEYWORD,ccgslb,🎯 全球直连
  - DOMAIN-KEYWORD,chinacache,🎯 全球直连
  - DOMAIN-KEYWORD,duobao,🎯 全球直连
  - DOMAIN-KEYWORD,jdpay,🎯 全球直连
  - DOMAIN-KEYWORD,moke,🎯 全球直连
  - DOMAIN-KEYWORD,qhimg,🎯 全球直连
  - DOMAIN-KEYWORD,vpimg,🎯 全球直连
  - DOMAIN-KEYWORD,xiami,🎯 全球直连
  - DOMAIN-KEYWORD,xiaomi,🎯 全球直连
  - DOMAIN,csgo.wmsj.cn,🎯 全球直连
  - DOMAIN,dota2.wmsj.cn,🎯 全球直连
  - DOMAIN,wmsjsteam.com,🎯 全球直连
  - DOMAIN,dl.steam.clngaa.com,🎯 全球直连
  - DOMAIN,dl.steam.ksyna.com,🎯 全球直连
  - DOMAIN,st.dl.bscstorage.net,🎯 全球直连
  - DOMAIN,st.dl.eccdnx.com,🎯 全球直连
  - DOMAIN,st.dl.pinyuncloud.com,🎯 全球直连
  - DOMAIN,xz.pphimalayanrt.com,🎯 全球直连
  - DOMAIN,steampipe.steamcontent.tnkjmec.com,🎯 全球直连
  - DOMAIN,steampowered.com.8686c.com,🎯 全球直连
  - DOMAIN,steamstatic.com.8686c.com,🎯 全球直连
  - DOMAIN,static.cloudflareinsights.com,🤗节点选择
  - DOMAIN,cdn.cloudflare.net,🤗节点选择
  - DOMAIN,challenges.cloudflare.com,🤗节点选择
  - DOMAIN,netflix.com,🤗节点选择
  - DOMAIN,tiktok.com,🤗节点选择
  - DOMAIN,youtube.com,🤗节点选择
  - DOMAIN,facebook.com,🤗节点选择
  - DOMAIN,telegram.com,🤗节点选择
  - DOMAIN,twitter.com,🤗节点选择
  - DOMAIN,xn--ngstr-lra8j.com,🤗节点选择
  - DOMAIN,services.googleapis.cn,🤗节点选择
  - DOMAIN,mtalk.google.com,🤗节点选择
  - DOMAIN-SUFFIX,voidsec.com,🤗节点选择
  - DOMAIN-SUFFIX,browserleaks.com,🤗节点选择
  - DOMAIN-SUFFIX,ipleak.net,🤗节点选择
  - RULE-SET,JianxianApp,🛑 广告拦截
  - RULE-SET,BlockDNS,🛑 广告拦截
  - RULE-SET,lancidr,DIRECT
  - RULE-SET,cncidr,DIRECT
  - RULE-SET,direct,DIRECT
  - RULE-SET,google,🤗节点选择
  - RULE-SET,proxy,🤗节点选择
  - RULE-SET,gfw,🤗节点选择
  - RULE-SET,cncidr,DIRECT
  - MATCH,🤗节点选择
rule-providers:
  gfw:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/gfw.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/gfw.yaml
  direct:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/direct.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/direct.yaml
  cncidr:
    type: http
    behavior: ipcidr
    interval: 86400
    path: ./ruleset/cncidr.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/cncidr.yaml
  lancidr:
    type: http
    behavior: ipcidr
    interval: 86400
    path: ./ruleset/lancidr.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/lancidr.yaml
  google:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/google.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/google.yaml
  proxy:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/proxy.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/proxy.yaml
  JianxianApp:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/JianxianApp.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/JianxianApp.yaml
  BlockDNS:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/BlockDNS.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/BlockDNS.yaml
