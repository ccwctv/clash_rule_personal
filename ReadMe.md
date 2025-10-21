# Github

- 个人Github：[clash_rule_personal](https://github.com/ccwctv/clash_rule_personal)  
- 故障转移：[clash-fallback-all.yaml](https://github.com/liandu2024/little/blob/main/yaml/clash-fallback-all.yaml)  
- 分流规则
  - [ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash)  



# 策略组位置对应

- 一一对应
- 顺序也要对应



# 注意规则顺序

- 规则越靠前，优先级越高
- 越特殊的规则，越要放前面
- 例如：OneDrive 策略组，要排在Microsoft 策略组之前

# 策略组选择

- Block：拒绝 Reject（不走 OpenClash 内核）
- SteamCN：直连 Direct（下载直连）
- NVIDIA：直连 Direct



# 规则集

- 注意规则集类型
  - text 文件：classical
  - yaml 文件：classical
  - mrs 文件：domain
- Github 上文件，点击右上角 Raw 打开，才是文件地址
- Github 地址前，添加加速地址，以防拉取配置失败



![1](https://github.com/ccwctv/clash_rule_personal/blob/1214319c26e8253c87d8b1453bf4aee88713d8f2/Picture/1.png?raw=true)

![](https://github.com/ccwctv/clash_rule_personal/blob/1214319c26e8253c87d8b1453bf4aee88713d8f2/Picture/2.png?raw=true)

![](https://github.com/ccwctv/clash_rule_personal/blob/1214319c26e8253c87d8b1453bf4aee88713d8f2/Picture/3.png?raw=true)  






