# Serverless Devs Registry Application Awesome

- [Web Framework应用案例](#WebFramework应用案例)
- [静态网站应用案例](#静态网站应用案例)
- [场景合集](#场景合集)
    - [AI场景](#AI场景)
    - [音视频处理案例](#音视频处理案例)
    - [Serverless架构下数据库使用](#Serverless架构下数据库使用)
    - [其他](#其他)

## Web Framework应用案例

将一个传统框架部署到阿里云Serverless平台的方法有很多，可以选择Custom、Custom Container以及原生编程语言的运行时。这其中Custom和原生语言运行时方案，除了启动命令/入口函数不同之外，区别并不是很大，可以根据自己需求进行实现，Custom Container方案相对来说更简单，但是镜像的冷启动速度相对Custom和原生语言运行时比较慢。

目前函数计算仓库收录以下常见框架的部署案例：

<table>
<tr>
<th>No.</th>
<th>:fire:Nodejs</th>
<th>Python</th>
<th>PHP</th>
<th>Go</th>
<th>Java</th>
<th>Others</th>
</tr>
<tr>
<td align="center">1</td>
<td align="center">:fire:<a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/express/src">Express [custom]</a></td>
<td align="center">:fire::fire:<a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/flask/src">Flask [python3]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/thinkphp/src">Think PHP</a></td>
<td align="center">BeeGo</td>
<td align="center">Tomcat/Jetty</td>
<td align="center">Gatsby</td>
</tr>
<tr>
<td align="center">2</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/egg/src">Egg [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/tornado/src">Tornado [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/laravel/src">laravel</a></td>
<td align="center">Gin</td>
    <td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/java/springboot">Spring Boot</a></td><td>Hugo</td>
</tr>
<tr>
<td align="center">3</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/next/src">Nextjs [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/bottle/src">Bottle [python3]</a></td>
    <td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/discuz/src">Discuz</a></td><td></td><td align="center">Quarkus</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">4</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nuxt/src">Nuxtjs [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/webpy/src">Web.py [python3]</a></td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/wordpress/src" >WordPress</a></td><td></td><td></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">5</td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/hapi/src" >Hapi [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/django/src" >Django [python3]</a></td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/zblog/src" >Zblog</a></td><td></td><td></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">6</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/koa/src">Koa [custom]</a></td>
    <td align="center">FastAPI</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/ecshop/src" >Ecshop</a></td><td></td><td></td><td></td>
</tr>
<tr>
<td align="center">7</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nest/src">Nest [nodejs12]</a></td>
<td align="center">Web2py</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/metinfo/src" >Metinfo</a></td>
    <td></td><td></td><td></td>
</tr>
<tr>
<td align="center">8</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/connect/src">Connect [nodejs12]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/pyramid/src" >Pyramid [python3]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/whatsns/src" >Whatsns</a></td><td></td><td></td><td></td>
</tr>
<tr>
<td align="center">9</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/thinkjs/src">Think.js [nodejs12]</a></td>
<td align="center"></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/typecho/src" >Typecho</a></td><td></td><td></td><td></td>
</tr>
</table>

> 除了上面的案例之外，还提供了两个简单的实践应用：
> - [基于Express框架的todoList应用](./example/todolist-app/src)：`s init todolist-app`
> - [基于Django框架的博客应用](./example/django-blog/src)：`s init django-blog`    
> 考虑到部分用户在使用 Nuxt 等框架时，有 SSR 或者 SPA 的目的，所以本仓库也提供了类似的案例：
> - [next-ssr](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/next-ssr/src): `s init start-next-ssr`
> - [nuxt-ssr](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nuxt-ssr/src): `s init start-nuxt-ssr`
> - [nuxt-spi](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nuxt-spa/src): `s init start-nuxt-spa`     
> 为了对比Custom运行时和编程语言原生运行时的框架迁移区别，可以参考以下案例进行自行对比：
>
> | 框架名 | Custom运行时 | Node.js 12运行时 |
> | ----- | ----------- | ----------------|
> | Egg.js | [https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/egg](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/egg/src) | [https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/egg-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/egg-app/src) |
> | Express.js | [https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/express](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/express/src) | [https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/express-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/express-app/src) |
> | Koa.js | [https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/koa](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/koa/src) | [https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/koa-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/koa-app/src) |
>


## 静态网站应用案例

- 静态网站案例：
    - [普通静态资源应用](https://github.com/devsapp/start-website/tree/master/website-base/src): `s init website-base`
    - [react应用](https://github.com/devsapp/start-website/tree/master/website-react/src) `s init website-react`
    - [vue应用](https://github.com/devsapp/start-website/tree/master/website-vue/src) `s init website-vue`
    - [hexo应用](https://github.com/devsapp/start-website/tree/master/website-hexo/src) `s init website-hexo`
    - [docusaurus应用](https://github.com/devsapp/start-website/tree/master/website-docusaurus/src) `s init website-docusaurus`
    - [vuepress应用](https://github.com/devsapp/start-website/tree/master/website-vuepress/src) `s init website-vuepress`

> 当然，上面所列举的静态网站案例都是build之后部署到对象存储等，您也可以直接部署到函数计算（尽管这并不是一个值得推荐的做法），您可以参考[start-static-site文档](https://github.com/devsapp/start-static-site) , 也可以尝试执行命令`s init start-static-site`进行初始化

## 场景合集

### AI场景

- [PyTorch案例](https://github.com/devsapp/start-ai/tree/master/start-pytorch/src) `s init start-pytorch`
- [Tensorflow案例](https://github.com/devsapp/start-ai/tree/master/start-tensorflow/src) `s init start-tensorflow`
- [OCR案例](https://github.com/devsapp/start-ai/tree/master/start-ocr/src) `s init start-ocr`
- [目标检测案例](https://github.com/devsapp/start-ai/tree/master/image-prediction-app/src) `s init image-prediction-app`

### 音视频处理案例

- [弹性高可用的高度自定义音视频处理](https://github.com/devsapp/start-ffmpeg/tree/master/ffmpeg-app/src): `s init ffmpeg-app`
- [对直播视频流截图的应用](https://github.com/devsapp/start-ffmpeg/tree/master/rtmp-snapshot/src): `s init rtmp-snapshot`
- [一个对浏览器全景录制](https://github.com/devsapp/start-ffmpeg/tree/master/headless-ffmpeg/src): `s init headless-ffmpeg`

### Serverless架构下数据库使用

- python案例
    - [mysql案例](https://github.com/devsapp/start-fc-db/tree/main/python/mysql/src): `s init start-fc-mysql-python`
    - [redis案例](https://github.com/devsapp/start-fc-db/tree/main/python/redis/src): `s init start-fc-redis-python`
    - [mongodb案例](https://github.com/devsapp/start-fc-db/tree/main/python/mongodb/src): `s init start-fc-mongodb-python`
    - [sql-server案例](https://github.com/devsapp/start-fc-db/tree/main/python/sql_server/src): `s init start-fc-sql-server-python`
    - [postgresql案例](https://github.com/devsapp/start-fc-db/tree/main/python/postgresql/src): `s init start-fc-postgresql-python`
    - [Lindorm案例](https://github.com/devsapp/start-fc-db/tree/main/python/lindorm/src): `s init start-fc-lindorm-python`

### 其他
- 基于 puppeteer 的截图 Web 应用: 
    - [基于Node.js的案例](https://github.com/devsapp/start-puppeteer/tree/master/puppeteer-nodejs/src): `s init puppeteer-nodejs`
    - [基于Container的案例](https://github.com/devsapp/start-puppeteer/tree/master/puppeteer-container/src): `s init puppeteer-container`
- [word转pdf的应用](https://github.com/devsapp/start-word2pdf): `s init start-word2pdf`
- [pdf转图片的应用](https://github.com/devsapp/start-pdf2img): `s init start-pdf2img`
- [电商后端管理系统](https://github.com/devsapp/start-fc-mall-admin): `s init start-fc-mall-admin`
- [现代应用解决方案](https://github.com/devsapp/modern-web-application): `s init modern-web-application`