## 基于node unblocker的通用web代理
本工程是 [node-unblocker](https://github.com/nfriedly/node-unblocker) 的一个副本，只是修改了工程结构，以便于直接在Heroku上部署;  原作者的版本里, 所有的代理请求被到 http, 在这种场景下, URL中含有敏感域名会导致连接被GFW重置。因此，在该副本里，修改了代码让所有代理请求全使用https。

## 注意：heroku的login服务器已被GFW屏b，请翻墙进行部署

node-unblocker相对于PHP的web代理性能要好，且易于在Heroku上部署。 Heroku提供免费账号，且不需要绑定信用卡，部署简单。若您担心使用别人提供的服务器可能会泄漏个人隐私，可以通过一键部署搭建自己的Web代理。部署自己的代理，去中心化，小范围使用更不容易被GFW封锁。

# 本版本变化
1、已将轮轮添加的链接删除，界面更纯净

2、净化google，github链接

3、添加了一些个人常用链接，如 pixiv，niconico

# 一键部署，请点击下方的"Deploy to Heroku"按钮

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

注：此代理适用于大多数网站，但无法播放YouTube视频。观看YouTube视频，请使用 [you2php-heroku](https://github.com/zhangke200377/you2php-heroku)。

# 社会主义核心价值观
 富强 民主 文明 和谐
 自由 平等 公正 法制
 爱国 敬业 诚信 友善
