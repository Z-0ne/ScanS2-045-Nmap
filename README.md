# ScanS2-045-Nmap
ScanS2-045-Nmap

Struts2 S2-045 Nmap Scan Script
# Struts2 S2-045 Vulnerabilities info
[CNNVD-2017-03-07](http://cnnvd.org.cn/notice/show/id/8230)

[CNTA-2017-0016](http://www.cnvd.org.cn/webinfo/show/4080)

[US-CERT](https://www.us-cert.gov/ncas/current-activity/2017/03/08/Apache-Software-Foundation-Releases-Security-Updates)

# Usage script
1、copy struts2-scan.nse to nmap script folder

2、run `nmap -script struts2-scan -sS -p 80,8080,81,82,83,84,85,86,87,88,8888,8088 -n -d ip -oX outscan.xml`
