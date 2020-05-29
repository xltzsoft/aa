首先，让[xtlsoft签到系统](http://signin.xapps.top/)隆重登场！
![](https://shop.io.mi-img.com/app/shop/img?id=shop_081d5cefac26379da5b230d3c0e37cd5.png)
额。。。

这个签到系统还有UA检测啊。不过没关系，我们用手机qq的UA来伪装一下。
![](https://shop.io.mi-img.com/app/shop/img?id=shop_31c6d53fdd61ebeed67506a710763c57.png)
那么接下来。。。
![](https://shop.io.mi-img.com/app/shop/img?id=shop_2db2c661121b99cd27c4340a23c3dba0.png)
知道我要干什么了吧。。。

但是，太不稳定了，而且我电脑配置太低，卡到爆炸。。。
![](https://shop.io.mi-img.com/app/shop/img?id=shop_e9c8a7c87937a100f274c07472058b36.png)
写个脚本，定时运行。。。

但是！！！
![](https://shop.io.mi-img.com/app/shop/img?id=shop_402de385d69492a46e3e01b32dfba107.png)
心惊胆战啊。。。这也太不稳定了。。。

那我们换一种思路，用php模拟。为了稳定，我一签就是10次。
![](https://shop.io.mi-img.com/app/shop/img?id=shop_b8eeaed212a44b84ba39002b17dfdbe0.png)
然后那个签到系统居然加上了cloudflare。。。本来以为加上cookie参数就可以了，结果没成功，不折腾了。

我们再换一种思路。
![](https://shop.io.mi-img.com/app/shop/img?id=shop_e413a06964b828e08221f1923ff1c3a3.png)
本来好好的，没想到，cfuid居然会变。。。

我也是真的没办法了，那我们退而求其次，定时提醒签到。
![](https://shop.io.mi-img.com/app/shop/img?id=shop_4d5661f2310734423182d9ff7afebd78.png)
还加上了serverchan微信推送，加上宝塔定时命令，完美！

我还写了一个telegram bot推送的版本，稳定运行到现在。