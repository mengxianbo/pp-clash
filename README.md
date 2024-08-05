  geoip: https://github.com/mengxianbo/pp-clash/blob/main/GeoIP.dat
  geosite: https://github.com/mengxianbo/pp-clash/blob/main/GeoSite.dat
  mmdb: https://github.com/mengxianbo/pp-clash/blob/main/Country.mmdb

rule-providers:
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
  gfw:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/gfw.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/gfw.yaml
  AD:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/ad.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/AD.yaml
  EasyList:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/EasyList.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/EasyList.yaml
  EasyListChina:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/EasyListChina.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/EasyListChina.yaml
  EasyPrivacy:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/EasyPrivacy.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/EasyPrivacy.yaml
  ProgramAD:
    type: http
    behavior: domain
    interval: 86400
    path: ./ruleset/ProgramAD.yaml
    url: https://raw.githubusercontent.com/mengxianbo/pp-clash/main/ProgramAD.yaml
