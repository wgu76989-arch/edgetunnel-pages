# edgetunnel-pages

这是 `wgu76989-arch/edgetunnel-independent` 使用的独立静态管理前端，部署地址为：

<https://wgu76989-arch.github.io/edgetunnel-pages/>

页面脚本、二维码、地图、字体和快照资源已放在本仓库或账号下的独立数据仓库中；
不会再自动使用原项目的 Raw 镜像或优选探测域名。

部分管理功能本质上需要运行时服务，仍按用户配置访问外部服务：Cloudflare API、
Telegram Bot API、DNS-over-HTTPS、公共 IP 查询、用户自行部署的 `SUBAPI`，以及
用户填写的 ProxyIP/订阅地址。这些不是静态文件依赖，不能通过 GitHub Pages 下载后
变成本地服务。
