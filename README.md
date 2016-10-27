# Mooder团队贡献系统

Mooder是一款开源、安全、简洁、强大的（安全）团队贡献平台，基于Django、全封闭保证私密性、支持Markdown、支持Postgres/Mysql/Sqlite等多种数据库、支持Docker-compose一键化安装与更新，易于二次开发。

## 为什么会有Mooder

做Mooder的初衷是为了团队内部的交流。由于众所周知的原因，国内大量社区关闭，安全技术知识的学习变得愈加困难，更多的团队将交流方式变为QQ群、微信群。
而QQ、微信等及时通信工具并不是一个交流技术的好地方，团队仍然需要一个内部社区。于是，Mooder应运而生。

Mooder从设计之初想法就是“封闭”，也就是说该社区严格控制内部隐私，仅拥有邀请码的用户可以登录社区，管理员在后台也能够踢出、删除一个用户，保证了社区的私密性。

另外，Mooder的核心理念的“贡献”。团队成员可以将自己挖掘的通用漏洞、编写的EXP、提交到其他SRC的漏洞详情、众测中挖到的漏洞等等作为一个“贡献”提交到Mooder中，然后由管理员进行审核并给予rank与积分。通过该“积分”，团队成员也可以购买其他成员提交的贡献，或者去礼品中心换取礼品等。

通过这样的“知识交换”，让团队能够更快地成长。

## 文档

详细文档移步 [https://phith0n.github.io/mooder/][1]

## 演示站点

演示站点： [http://mooder.daoapp.io/][2]

演示站点不对外开放。

## 开源协议

使用Mooder请遵守LGPL协议。

[1]: https://phith0n.github.io/mooder/
[2]: http://mooder.daoapp.io/