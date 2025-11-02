# Github

- 个人Github：[clash_rule_personal](https://github.com/ccwctv/clash_rule_personal)  
- 故障转移：[clash-fallback-all.yaml](https://github.com/liandu2024/little/blob/main/yaml/clash-fallback-all.yaml)  
- 分流规则
  - [ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash)
  - [little](https://github.com/liandu2024/little)



# 策略组位置对应

- 顺序无需一一对应
- 把修改、自定义的策略组前置，好后期修改


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




# OpenClash 更新 Yaml配置

## 修改当前配置文件
- 运行状态-配置文件-编辑按钮-保存
- 更新配置
- 切换配置（切换使生效）

## 手动上传yaml配置文件
- 易有云文件管理器，打开 `/root/etc/openclash`
- 删除以下文件，以防分流策略不更新或更新不及时
	- XX.yaml：`/root/etc/openclash/config`，`/root/etc/openclash/config`，`/root/etc/openclash/backup`
	- XX.db：`/root/etc/openclash/history`
		- 若只是微调yaml（如调整分流组顺序），可保留history下的 XX.db 数据文件（设置数据）
	- 删除完成后，再次应用该yaml配置文件

## 覆写设置
覆写设置，优先于手动上传yaml配置
- 若是覆写规则不生效，试着清理DNS缓存
- 若清理DNS依然无效，执行上述删除操作











