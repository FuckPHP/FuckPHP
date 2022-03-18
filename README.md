# 《PHP安全-只有PHP安全才能拯救世界》

本项目是记录自己在学习研究PHP安全过程中遇到的优秀内容，包括PHP代码审计资源以及PHP开发的应用程序组件协议等的安全内容。一个不会PHP攻击的黑客不是一个好师傅，一个不懂PHP安全的师傅不是一个好黑客！深入理解PHP安全，手握众多重点PHP应用高危0day！作者：[0e0w](https://github.com/0e0w)

本项目创建于2021年7月8日，最近的一次更新时间为2022年3月18日。本项目会持续更新，直到海枯石烂。

- [01-PHP安全研究资源](https://github.com/FuckPHP/FuckPHP#01-php%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6%E8%B5%84%E6%BA%90)
- [02-PHP安全研究工具](https://github.com/FuckPHP/FuckPHP#02-php%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6%E5%B7%A5%E5%85%B7)
- [03-PHP安全漏洞环境](https://github.com/FuckPHP/FuckPHP#03-php%E5%AE%89%E5%85%A8%E6%BC%8F%E6%B4%9E%E7%8E%AF%E5%A2%83)
- [04-PHP安全漏洞分类](https://github.com/FuckPHP/FuckPHP#04-php%E5%AE%89%E5%85%A8%E6%BC%8F%E6%B4%9E%E5%88%86%E7%B1%BB)
- [05-PHP安全代码审计](https://github.com/FuckPHP/FuckPHP#05-php%E5%AE%89%E5%85%A8%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1)
- [06-PHP安全漏洞修复](https://github.com/FuckPHP/FuckPHP#06-php%E5%AE%89%E5%85%A8%E6%BC%8F%E6%B4%9E%E4%BF%AE%E5%A4%8D)
- [07-PHP安全高危应用](https://github.com/FuckPHP/FuckPHP#07-php%E5%AE%89%E5%85%A8%E9%AB%98%E5%8D%B1%E5%BA%94%E7%94%A8)
- [08-PHP安全参考资源](https://github.com/FuckPHP/FuckPHP#08-php%E5%AE%89%E5%85%A8%E5%8F%82%E8%80%83%E8%B5%84%E6%BA%90)

## 01-PHP安全研究资源

一、书籍资料
- [ ] [《代码审计：企业级Web代码安全架构》](https://item.jd.com/10037792221891.html)@尹毅
- [ ] [《Web安全漏洞及代码审计》](https://item.jd.com/10038852529768.html)@郭锡泉

二、基础教程
- [ ] https://github.com/hongriSec/PHP-Audit-Labs
- [ ] https://github.com/aleenzz/php_bug_wiki
- [ ] https://github.com/jiangsir404/Audit-Learning
- [ ] https://github.com/jiangsir404/PHP-code-audit
- [ ] https://github.com/SecWiki/CMS-Hunter
- [ ] https://github.com/yaofeifly/PHP_Code_Challenge
- [ ] https://github.com/ambionics/phpggc
- [ ] https://github.com/vimeo/psalm
- [ ] https://github.com/nikic/php-parser
- [ ] https://github.com/bowu678/php_bugs | PHP代码审计分段讲解
- [ ] https://github.com/Xyntax/1000php | 1000个PHP代码审计案例
- [ ] https://github.com/Jyny/pasc2at | 高级PHP应用程序漏洞审核技术
- [ ] https://github.com/SukaraLin/php_code_audit_project
- [ ] https://github.com/lightswitch05/php-version-audit
- [ ] https://github.com/marcocesarato/PHP-Antimalware-Scanner
- [ ] https://github.com/FriendsOfPHP/PHP-CS-Fixer
- [ ] https://github.com/kitezzzGrim/PHP-Audit-Learn
- [ ] [《PHP代码审计入门指南》](https://github.com/burpheart/PHPAuditGuideBook)@burpheart
- [ ] https://github.com/M0untainShley/PHP_CodeAudit
- [ ] https://www.freebuf.com/articles/web/252333.html

三、视频教程

四、培训演讲

五、专利文献

六、审计报告

七、其他资源

- https://github.com/topics/static-analysis?l=php

## 02-PHP安全研究工具

- [ ] https://github.com/xdebug/xdebug
- [ ] https://github.com/phpstan/phpstan
- [ ] https://github.com/ambionics/phpggc
- [ ] https://github.com/ripsscanner/rips
- [ ] https://github.com/robocoder/rips-scanner
- [ ] https://github.com/ecriminal/phpvuln
- [ ] https://github.com/meizjm3i/PHPVulFinder
- [ ] https://github.com/squizlabs/PHP_CodeSniffer

## 03-PHP安全漏洞环境

- [ ] https://github.com/digininja/DVWA
- [ ] https://github.com/710leo/ZVulDrill
- [ ] https://github.com/Acmesec/DoraBox
- [ ] https://github.com/c0ny1/upload-labs
- [ ] https://github.com/s4n7h0/xvwa
- [ ] https://github.com/wgpsec/VulnRange
- [ ] https://github.com/zhuifengshaonianhanlu/pikachu
- [ ] https://github.com/Audi-1/sqli-labs
- [ ] https://github.com/sqlsec/xssgame
- [ ] https://github.com/c0ny1/upload-labs
- [ ] https://github.com/s4n7h0/xvwa
- [ ] https://github.com/710leo/ZVulDrill
- [ ] https://github.com/redBu1l/ZVulDrill
- [ ] https://github.com/0xs1riu5/vulawdhub
- [ ] https://github.com/bmdyy/tudo
- [ ] https://github.com/78778443/permeate
- [ ] https://github.com/admin360bug/PHP
- [ ] https://github.com/Yavuzlar/VulnLab
- [ ] https://github.com/SpiderMate/B-XSSRF
- [ ] https://github.com/f4cknet/gohackphp
- [ ] https://github.com/lucideus-repo/UnSAFE_Bank

## 04-PHP安全漏洞分类

本部分详细列举常见的PHP安全漏洞内容。

- 程序安装问题
- 业务逻辑漏洞
- SQL注入漏洞
- 变量覆盖漏洞
- 任意文件上传漏洞
- 任意文件写入漏洞
- 任意文件删除漏洞
- 任意文件包含漏洞
- 任意命令执行漏洞
- PHP反序列化漏洞
- XSS跨站脚本攻击
- XML外部实体攻击
- CSRF跨站请求伪造
- SSRF服务端请求伪造

## 05-PHP安全代码审计

一、PHP安全Web漏洞

二、PHP代码审计实战

## 06-PHP安全漏洞修复

一、PHP安全编码规范

二、PHP安全漏洞修复

## 07-PHP安全高危应用

## 08-PHP安全参考资源

[![Stargazers over time](https://starchart.cc//0e0w/HackPHP.svg)](https://starchart.cc/0e0w/HackPHP)