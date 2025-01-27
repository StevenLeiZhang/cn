# 镜像概述

镜像是实例运行环境的模板，包含操作系统和预装的软件以及相关配置。镜像和实例密不可分，创建实例必须指定镜像，而实例创建后，可以通过制作镜像将系统盘和数据盘进行备份并记录其关联关系，后续可以基于镜像快速启动任意数量实例。

## 镜像应用
* 批量部署软件环境：
对已经部署好环境的实例制作镜像，然后基于此镜像批量创建实例，主机创建之后，拥有和之前实例一致的软件环境，以此可以达到批量部署软件环境的目的。

* 作为服务器运行环境的备份：
对一台实例制作镜像，如果该实例在后续使用过程中软件环境被损坏无法正常运行，则可以通过实例重置系统功能使用该镜像恢复受损的实例。

* 跨地域跨平台一致性部署
对实例制作镜像后，通过镜像导入/导出、跨区域复制等功能，可以实现本地+云或多云间的一致性部署，实现主备或多活架构。

## 镜像费用

* 镜像使用<br>
目前官方镜像和镜像市场镜像均为免费使用，即使用镜像创建实例时无需支付镜像相关费用。
* 镜像存储<br>
由于私有镜像本质是对云硬盘备份数据（快照）的引用，而云硬盘快照目前已经商业化，因此保有私有镜像会产生一定的快照保存费用，具体收费标准请以[云硬盘快照收费](https://docs.jdcloud.com/cloud-disk-service/price-overview)为准。

## 镜像生命周期

通过对实例制作镜像或从外部环境导入均可获得私有镜像，用户对私有镜像拥有绝对的使用和管理权限，可以将其复制到其他地域、共享给其他用户、导出京东云或进行删除，京东云早期提供的本地系统盘镜像，可以通过镜像类型转换功能生成云盘系统盘镜像继续使用。

<div align="center"><img src="https://img1.jcloudcs.com/cn/image/vm/image-overview.png" width="700"></div>


## 相关参考

[制作私有镜像](https://docs.jdcloud.com/virtual-machines/create-private-image)

[镜像类型转换](Convert-Image.md)

[云硬盘快照收费](https://docs.jdcloud.com/cloud-disk-service/price-overview)
