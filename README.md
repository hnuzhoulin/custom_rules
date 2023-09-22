```
rule-providers:
  normal_proxy:
    type: http
    behavior: classical
    url: "https://ghproxy.com/https://github.com/hnuzhoulin/custom_rules/raw/main/normal_proxy.yaml"
    path: "./normal_proxy.yaml"
    interval: 86400  # 更新间隔，单位是秒
  normal_direct:
    type: http
    behavior: classical
    url: "https://ghproxy.com/https://github.com/hnuzhoulin/custom_rules/raw/main/normal_direct"
    path: "./normal_direct.yaml"
    interval: 86400  # 更新间隔，单位是秒
  us_proxy:
    type: http
    behavior: classical
    url: "https://ghproxy.com/https://github.com/hnuzhoulin/custom_rules/raw/main/us_proxy.yaml"
    path: "./us_proxy.yaml"
    interval: 86400  # 更新间隔，单位是秒
```
