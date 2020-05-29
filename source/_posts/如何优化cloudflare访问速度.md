[本站](https://stzo.cn)就是用cloudflare实现访问的，具体可以看我上一篇文章。如果你使用ipv4来访问本站，会发现速度很快，ping值也在50ms左右（我这里）。这速度延时，不像是cloudflare减速器啊！（笑）下面我就来说说怎么实现加速。

首先，我们要在cloudflare官网注册一个账号：
![](https://shop.io.mi-img.com/app/shop/img?id=shop_91669121d5256049b710d3d3f7772eb1.png)
然后，我们去[笨牛网](https://cdn.bnxb.com)，用刚刚注册的cloudflare账号注册笨牛账号，然后添加域名解析，选择cname解析，把它提供的cname地址填到你的域名服务商那里。像这样：
![](https://shop.io.mi-img.com/app/shop/img?id=shop_f2993d4a4716e5111e8824319d60f65e.png)
最后就是选节点了，我们ping一下[cloudflare的ip段](https://www.cloudflare.com/zh-cn/ips/)，找到延时最低，丢包最少的ip，填入域名服务商，增加解析，改一下线路，完美！
![](https://shop.io.mi-img.com/app/shop/img?id=shop_bc4f09b3c0053fce9efca207cad4d8c4.png)
好心的我给大家推荐几个不错的ip段：

162.159.208.4-162.159.208.103

162.159.209.4-162.159.209.103

162.159.210.4-162.159.210.103

162.159.211.4-162.159.211.103

上面是百度云合作ip段，对电信友好，可以试试。

172.64.32.*

141.101.115.*

上面是cloudflare香港节点，对移动友好，本站就是用的移动ip段。

设置完ip，你会发现网站还是访问不了。。。那是因为，我忘记了一件关键的事情：去笨牛网添加解析。
![](https://shop.io.mi-img.com/app/shop/img?id=shop_49795ca12686cc81e3ae6365b1ba12bb.png)
其中，类型和回源地址根据你的服务器自行修改。

最后，还可以在笨牛网的自动优化中优化一下，让全站都被cdn缓存。

接下来，享受飞一般的网站访问速度吧！