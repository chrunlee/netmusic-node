# netmusic-node
``` bash
# 下载项目到本地
git clone git@github.com:sqaiyan/netmusic-node.git

cd netmusic-node 

# 安装依赖
npm install 

# 启动项目 服务器中可用pm2或foreve之类
node app.js | pm2 app.js

```



网易云音乐接口
很多接口都是github上别人发布的，但是都不全，我这个是根据官网pc站看源码和pc客户端扫描找出来的，因为目前的接口都是采用eapi地址的最新接口，参数都是加密后的很多参数值能靠猜，欢迎大家自己去看源码，找出更多的接口并发出来。

欢迎star

接口调用是有频率限制的,搜索类太频繁会返回空数据，登录类直接封IP，部署在vps要小心开放访问
