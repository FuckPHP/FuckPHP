# 《深入理解PHP代码审计》

本项目是记录自己在学习PHP代码审计过程中遇到的优秀内容，包括PHP代码审计技巧以及优秀的PHP代码审计案例。一个不会PHP代码审计的师傅不是一个好黑客！一个不会PHP代码审计的黑客不是一个好师傅！深入理解PHP代码审计，手握众多重点PHP应用高危0day！作者：[0e0w](https://github.com/0e0w/HackPHP)

本项目创建于2021年7月8日，最近的一次更新时间为2021年11月30日。本项目会持续更新，直到海枯石烂。

- [01-PHP代码审计资源](https://github.com/0e0w/HackPHP#01-php%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E8%B5%84%E6%BA%90)
- [02-PHP代码审计工具](https://github.com/0e0w/HackPHP#02-php%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E5%B7%A5%E5%85%B7)
- [03-PHP漏洞靶场平台](https://github.com/0e0w/HackPHP#03-php%E6%BC%8F%E6%B4%9E%E9%9D%B6%E5%9C%BA%E5%B9%B3%E5%8F%B0)
- [04-PHP安全Web漏洞](https://github.com/0e0w/HackPHP#04-php%E5%AE%89%E5%85%A8web%E6%BC%8F%E6%B4%9E)
- [05-PHP代码审计实战](https://github.com/0e0w/HackPHP#05-php%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E5%AE%9E%E6%88%98)
- [06-PHP安全编码规范](https://github.com/0e0w/HackPHP#06-php%E5%AE%89%E5%85%A8%E7%BC%96%E7%A0%81%E8%A7%84%E8%8C%83)
- [07-PHP代码审计老师](https://github.com/0e0w/HackPHP#07-php%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E8%80%81%E5%B8%88)

## 01-PHP代码审计资源

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

## 02-PHP代码审计工具

- [ ] https://github.com/xdebug/xdebug
- [ ] https://github.com/phpstan/phpstan
- [ ] https://github.com/ambionics/phpggc
- [ ] https://github.com/ripsscanner/rips
- [ ] https://github.com/robocoder/rips-scanner
- [ ] https://github.com/ecriminal/phpvuln
- [ ] https://github.com/meizjm3i/PHPVulFinder

## 03-PHP漏洞靶场平台

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

## 04-PHP安全Web漏洞

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

## 05-PHP代码审计实战

## 06-PHP安全编码规范

## 07-PHP代码审计老师

[![Stargazers over time](https://starchart.cc//0e0w/HackPHP.svg)](https://starchart.cc/0e0w/HackPHP)