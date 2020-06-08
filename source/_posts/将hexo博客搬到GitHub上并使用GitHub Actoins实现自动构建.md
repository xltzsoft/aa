### 搭建hexo环境并上传至github
首先，你需要在本地搭建好一个hexo环境，配置好,然后上传到github，最好用git push（文件太多）
看看我的：[https://github.com/xltzsoft/aa](https://github.com/xltzsoft/aa)
### 编写GitHub Action
[https://github.com/xltzsoft/aa/blob/master/.github/workflows/main.yml](https://github.com/xltzsoft/aa/blob/master/.github/workflows/main.yml)
参照我的配置文件，改一下最后的user_name和user_email
### 生成ssh key并添加秘密环境变量
用ssh工具生成一个ssh key，将私钥上传到这里：[https://github.com/settings/keys](https://github.com/settings/keys)
再来到这里：
![](https://shop.io.mi-img.com/app/shop/img?id=shop_4c055d9f406d28539168bfec5703686f.png)
添加一个秘密环境变量DEPLOY_KEY，内容是你的私钥
### 愉快使用
现在，可以去source/_posts里面写一篇文章，触发GitHub Action的自动构建，随时随地优雅地写博客了！
