# proj313-Secure-Storage
# 基于飞腾派的安全存储应用，利用eMMC的RPMB分区的硬件特性实现安全存储

## 项目描述

飞腾派开发板是飞腾公司针对教育行业推出的一款国产开源硬件平台，兼容 ARMv8-A 处理器架构。此项目涉及安全操作系统，Trustzone硬件架构，都是目前最流行的安全框架。

本项目以安全存储作为一个理解安全架构的切入点，给同学们带来目前主流的安全存储的方式，涉及RPMB、optee、密钥保存，密钥派生，HUK等安全关键方向。

## 预期目标

1. 实现目标文件在固定存储介质中的安全存储。
2. 进一步实现多文件、大文件的安全存储，并优化存储过程
3. 分析安全可靠性，以及和普通存储的优势，分析方案能破解的条件。

## 特征

- optee安全操作系统
- eMMC的RPMB分区
- ARM Trustzone硬件架构
- 密钥派生和密钥存储
- 硬件支持
	- 带eMMC的飞腾派开发板

## 已有参考资料

-  飞腾派开发资料
	-  [操作系统大赛飞腾赛道交流社区](https://edu.phytium.com.cn/group/10)
	- [飞腾派开发板电子发烧友社区](https://bbs.elecfans.com/group_1708)
- [飞腾OPTEE开源项目](https://gitee.com/phytium_embedded/phytium-embedded-docs/blob/master/optee)
- [赛题资料汇总](https://edu.phytium.com.cn/group/10/thread/21579)
## 赛题分类
安全操作系统/可信执行环境

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

高等

## License

- Apache2.0
- BSD-2

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

**赛事支持导师**

- 姓名：郭丁丁
- 单位：飞腾信息技术有限公司
- email：[guodingding1657@phytium.com.cn](mailto:guodingding1657@phytium.com.cn)

**飞腾技术支持导师**
  
- 姓名：邓强
- 单位：飞腾信息技术有限公司
- email：[dengqiang@phytium.com.cn](mailto:dengqiang@phytium.com.cn)

**飞腾派技术支持导师**
  
- 姓名：连宇飞
- 单位：飞腾信息技术有限公司
- email：[lianyufei@phytium.com.cn](mailto:lianyufei@phytium.com.cn)
