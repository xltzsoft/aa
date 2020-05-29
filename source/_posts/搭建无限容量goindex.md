首先，我们来申请一个无限容量的Google Drive
打开这个网站：[https://gd.zxd.workers.dev/](https://gd.zxd.workers.dev/)
![](https://shop.io.mi-img.com/app/shop/img?id=shop_4dead0afce20cd7e576af6c8f0e0e5c0.png)
填写信息，然后你就拥有无限容量Google Drive团队盘了。
登录你的Google账号，在云端硬盘里找到共享云端硬盘，打开，然后找到地址里的folders后面的一串字符，复制下来。
打开[https://install.gd.workers.dev/](https://install.gd.workers.dev/)
![](https://shop.io.mi-img.com/app/shop/img?id=shop_2e3decb469fd329c9828155bf757e891.png)
获取认证码，把你在上面获得的一串字符填到目录id那一栏，生成代码。
去[cloudflare](https://dash.cloudflare.com/)新建一个cf worker，把代码粘贴到里面，部署
![](https://shop.io.mi-img.com/app/shop/img?id=shop_93a89ce87e807687d351baaa56039329.png)
然后打开xxx(你的worker名字).workers.dev就可以看到你的Google Drive团队盘了。
展示一下成品：
![](https://shop.io.mi-img.com/app/shop/img?id=shop_c78e2e601a9428dc7252f5f869cde423.png)