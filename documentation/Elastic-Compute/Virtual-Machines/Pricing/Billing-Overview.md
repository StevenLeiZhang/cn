# 计费概述

您可以直接使用京东云提供的[云主机价格计算器](https://www.jdcloud.com/calculator/calHost)查看您所需的产品组合对应价格，也可以查阅[价格总览](Price-Overview.md)用以估算投入成本。

请注意：价格总览中价格为统一官方标价，不包用户括折扣优惠，为了保证价格准确性，建议您登录后使用云主机价格计算器或登录控制台云主机创建页面查看配置价格。

## 计费方式
云主机及关联资源涉及三类计费方式：[包年包月计费](http://docs.jdcloud.com/cn/billing/subscription)、[按配置计费](http://docs.jdcloud.com/cn/billing/pay-as-you-go)及[按用量计费](http://docs.jdcloud.com/cn/billing/pay-as-you-go)。

## 计费资源
### 实例

实例按照您选购实例规格对应vCPU核数、内存容量、本地存储（若有）及GPU（若有）计费，计费方式有包年包月计费及按配置计费。

### 云硬盘

云硬盘按照您选购容量计费，计费方式有包年包月计费及按配置计费。随云主机创建的云盘，计费方式与实例相同，为保证生命周期一致，建议您将实例与其挂载的云硬盘一同续费。详细信息请参见 [云硬盘计费文档](http://docs.jdcloud.com/cn/cloud-disk-service/billing-rules)。

### 弹性公网IP

弹性公网IP（Elastic IP，简称EIP）按您选择的固定带宽或实际使用流量计费，其中对于选择按固定带宽计费的EIP支持包年包月计费及按配置计费方式；对于选择按使用流量计费的EIP仅支持按用量计费方式。详细信息请参见 [弹性公网IP计费文档](../../../Networking/Elastic-IP/Pricing/Billing-Overview.md)。

* 若实例绑定了按固定带宽计费且计费类型为包年包月的EIP，为保证生命周期一致，建议您将实例与其绑定的按固定带宽计费EIP一同续费；
* 若实例绑定的按使用流量计费或按固定带宽计费且计费类型为按配置的EIP，您需要关注您余额及代金券剩余情况，以防由于欠费导致EIP提前释放影响您业务正常运行。

### 私有镜像
目前所有镜像均为免费使用，即使用镜像创建实例时无需支付镜像相关费用。但由于私有镜像本质是对云硬盘备份数据（快照）的引用，而云硬盘快照目前已经商业化，因此制作并保有私有镜像会产生一定的快照保存费用，具体收费标准详见 [云硬盘快照计费规则](https://docs.jdcloud.com/cn/cloud-disk-service/snapshot-billing-rules)。

## 相关参考

[云主机价格计算器](https://www.jdcloud.com/calculator/calHost)

[价格总览](Price-Overview.md)

[包年包月计费](http://docs.jdcloud.com/cn/billing/subscription)

[按配置计费](http://docs.jdcloud.com/cn/billing/pay-as-you-go)

[按用量计费](http://docs.jdcloud.com/cn/billing/pay-as-you-go)

[云硬盘计费文档](http://docs.jdcloud.com/cn/cloud-disk-service/billing-rules)

[弹性公网IP计费文档](../../../Networking/Elastic-IP/Pricing/Billing-Overview.md)




 
