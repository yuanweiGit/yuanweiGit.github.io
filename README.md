
Hexo博客
# yuanweiGit.github.io

Hexo博客搭建

我的博客地址:

http://yuanweiGit.github.io

1.首先通过Github官网：https://github.com，注册Github账户。

2.在Github账户中创建一个项目，项目名必须要遵守格式：账户名xxxx.github.io

3.安装Git，下载地址：https://git-scm.com/downloads (还要配置密钥)

4.安装NodeJS，下载地址：http://nodejs.cn/download/

5.在电脑上新建存放博客的目录，在目录位置打开cmd窗口，依次执行

  (1).npm install -g hexo-cli (安装hexo)

  (2).hexo init (初始化hexo环境)

  (3).hexo generate (生成静态界面)

  (4).hexo server (启动hexo服务器)

  浏览器输入 http://localhost:4000 看效果  ---默认4000

--------接下来发布到github

6.将hexo生成的项目部署到GitHub上，打开配置文件 _config.yml，翻到最后

   deploy:

```
type: git

repo: git@github.com:yuanweiGit/yuanweiGit.github.io.git

branch: master
```

 7.安装deploy-git ，也就是部署的命令,这样你才能用命令部署到GitHub
    

```
npm install hexo-deployer-git --save
```

8.执行 hexo deploy 部署

------

Hexo 常用命令 

1. hexo clean (清楚之前生产的东西)
2. hexo generate (生成静态界面)
3. hexo deploy (部署)
4. hexo server (启动hexo服务器)

Hexo 主题 https://hexo.io/themes

hexo 插件 https://hexo.io/plugins

