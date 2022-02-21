<p align="center">
        <img  src="img/logo.png">
</p>

# 海天数据库安全审计防护平台

![LICENSE](https://img.shields.io/badge/license-AGPL%20-blue.svg)
![](https://img.shields.io/badge/build-release-brightgreen.svg)  
![](https://img.shields.io/badge/version-v3.0-brightgreen.svg)

#### 简介
HTASP（HThorizon Audit Security Protection ）是一款实时具备实时主动防护能力的数据库安全审计类产品。

公司信息： [北京海天起点技术服务股份有限公司](http://www.hthorizon.com/)

#### 部署方式
######  1. 基于反向代理的串联式部署模式

<p align="left">
        <img  width="450" height="300" src="img/deploy-proxy.jpg">
</p>

######  2. 基于端口镜像的旁路监听部署模式

<p align="left">
        <img width="450" height="300" src="img/deploy-bypass.jpg">
</p>

#### 支持的数据库
1. oracle
2. mysql/mariadb
3. postgresql
4. 达梦
5. 神州通用
6. todo...

#### Feature 功能
- 实时入侵阻断
<p align="left">
        <img src="img/reject1.png">
</p>
<p align="left">
        <img src="img/reject2.png">
</p>

- 分级防护：SQL级阻断、会话级阻断
<p align="left">
        <img width="500" height="200" src="img/level-protect.png">
</p>

- 基于SQL摘要的安全策略模型
<p align="left">
        <img width="500" height="370" src="img/policy.png">
</p>

- 等保合规级的溯源分析
<p align="left">
        <img width="460" height="370" src="img/audit.png">
</p>

- SQL质量审核
<p align="left">
        <img width="500" height="370" src="img/dengbao.png">
</p>

- SQL执行性能监测
- 风险评估
- 权限分离
- 集群支持

