

2018-07-07 1、修改一键下载复制多图的功能，解决循环，漏下丢失图片（顺序执行下载待优化）
           2、 优化点击收藏功能，用户进入商品详情，自动校验是否收藏该商品以及浏览量增加等
           3、增加短视频播放和下载功能（针对代理用户）提供下载功能

           首页：
           1、增加下拉刷新和自动版本校验，当版本更新的时候，自动提示用户下载安装。
           个人中心：
           1、优化自动登录，微信更新用户登录授权功能，让用户主动授权的方式。



中玉玉器微商平台：（后台）
            1、新增redis缓存，优化响应速度。（因主导图片太多，图片已经过处理，所以也就想到缓存了。）
            2、动静分离（静态资源使用独立域名），把图片分离到七牛云存储，使用CDN缓存加速。
            3、重新打架服务器环境（有原来Apache2.4.9+MySQL5.6+PHP5.5----> nginx1.10+mysql5.6+PHP7.0）
            4、域名https协议配置，PHP nginx fastcgi通信配置


