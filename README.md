部署，把源码粘贴到worker项目保存运行
1.有域名（有tls加密，443端口)，推荐！
Custom Domains查看——添加自定义域——填1个二级域名
点击自定义域，在二级域名后加/UUID，就能看到VLESS节点URL和Clash-meta配置
在v2rayN导入URL，地址栏改为优选ip

2.无域名（没tls加密，80或者2052端口）
进去worker.dev，加上/uuid就能看到VLESS节点URL和Clash-meta配置。v2ray,shadowrocket等客户端要去掉tls加密，端口改为80或者2052，地址修为优选 ip
uuid生成：https://1024tools.com/uuid
