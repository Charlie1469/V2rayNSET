# V2rayN
收藏一个由面具人哈乐共享科技分享的长期永久免费节点制作方法
https://www.kejixiaolu.com/djvps/dj02.html
操作步骤点击进入YouTube查看
https://www.youtube.com/watch?v=PXZbvd5nZaA

需要使用到的软件：

1.v2rayN 最新版下载地址>>

https://github.com/2dust/v2rayN/releases

2.workers win专用ip优选：下载地址>>

https://jdssl.top/wp-content/uploads/2023/07/works%E4%B8%93%E7%94%A8ip%E4%BC%98%E9%80%89.zip

cloudflare网站链接>>https://dash.cloudflare.com/

临时邮箱：https://www.linshiyouxiang.net/

部署代码：https://github.com/zizifn/edgetunnel/blob/main/src/worker-vless.js

uuid生成：https://1024tools.com/uuid

ip查看：https://whatismyipaddress.com/

cf ip优选；https://stock.hostmonit.com/CloudFlareYes

网络测速：https://www.speedtest.net/result/14952074175

openclash转换订阅网址：https://sub-web.netlify.app/

cdn加速
cdn-all.xn--b6gac.eu.org

cdn.xn--b6gac.eu.org 

cdn-b100.xn--b6gac.eu.org 

edgetunnel.anycast.eu.org

cdn.anycast.eu.org （亚洲地区）

因为原项目里面的代码“ proxy IP ”为空，关于 proxy IP ，是用于转发CF的一些流量，所以，若是存在套了CF的一些网站无法打开，请更换其中的其他网址，也就是第九行中的部分网址！
ProxyIP 可以替换成域名或优选IP
proxyip.us.fxxk.dedyn.io

更多 proxyIP 列表：
CM 维护
proxyip.us.fxxk.dedyn.io
IP落地区域: 美国 维护频率: 12小时/次
proxyip.sg.fxxk.dedyn.io
IP落地区域: 新加坡 维护频率: 12小时/次
proxyip.jp.fxxk.dedyn.io
IP落地区域: 日本 维护频率: 12小时/次
proxyip.hk.fxxk.dedyn.io
IP落地区域: 香港 维护频率: 12小时/次
proxyip.aliyun.fxxk.dedyn.io
IP落地区域: 阿里云 维护频率: 4小时/次
proxyip.oracle.fxxk.dedyn.io
IP落地区域: 甲骨文 维护频率: 4小时/次
proxyip.digitalocean.fxxk.dedyn.io
IP落地区域: 数码海 维护频率: 4小时/次

白嫖哥维护
workers.cloudflare.cyou

Mingyu 维护
my-telegram-is-herocore.onecf.eu.org
sg.ipdb.rr.nu
nl.ipdb.rr.nu
hk.ipdb.rr.nu
jp.ipdb.rr.nu
us.ipdb.rr.nu

小一维护
hk.cf.zhetengsha.eu.org
sg.cf.zhetengsha.eu.org
us.cf.zhetengsha.eu.org
jp.cf.zhetengsha.eu.org

代码修改完毕以后，点击右边的部署 – 保存并部署，然后点击左边的箭头，返回！

进去worker.dev，加上/uuid就能看到VLESS节点URL和Clash-meta配置。v2ray,shadowrocket等客户端要去掉tls加密，端口改为80或者2052，地址修为优选 ip

域名在v2ray 填优选ip处填写，把端口改为：80 并把下面的tls关闭。

![01](https://github.com/Charlie1469/V2rayN/assets/125989687/47ea6f76-8f54-42ba-b5d9-db59891c3f45)

