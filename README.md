  geoip: https://github.com/mengxianbo/pp-clash/blob/main/GeoIP.dat
  
  geosite: https://github.com/mengxianbo/pp-clash/blob/main/GeoSite.dat
  
  mmdb: https://github.com/mengxianbo/pp-clash/blob/main/Country.mmdb

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
