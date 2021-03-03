1. 获取Github相关网站的ip
https://www.ipaddress.com 中查询以下两个域名的ip地址

github.com
github.global.ssl.fastly.net

2. 修改本地hosts文件
windows系统的hosts文件的位置如下：C:\Windows\System32\drivers\etc\hosts
mac/linux系统的hosts文件的位置如下：/etc/hosts

写入hosts中

(我的配置)
140.82.114.4	github.com
199.232.5.194	github.global.ssl.fastly.net

3. ping github.com
cmd+r
输出 cmd 打开控制台
输出 ping github.com
输出 ipconfig/flushdns