## 说明

Laravel 另一个令人喜欢的地方，是拥有活跃的开发者社区，而活跃的开发者社区带来的，是繁华的扩展包生态。

本文对 [Packagist 上打了 Laravel 标签](https://packagist.org/search/?tags=laravel) 的扩展包进行整理，截止到现在 2016 年 8 月 9号，有超过 7176 个扩展包，以下是下载量最大的 100 个。

相信下面这 100 个扩展包会让你的编码更加高效 :beers:

> 讨论请前往：https://phphub.org/topics/2530，放 GitHub 上方便跟踪修改和接受 PR。

## 排名

| 排名 | 下载次数 | Star 数 | 扩展包 | 一句话描述 |
|---|---|---|---|---|
| 1 | 2883968 | 3968 | [intervention/image](https://github.com/Intervention/image) | 图片处理扩展包，支持裁剪、水印等处理，使用教程请见  https://phphub.org/topics/1903 |
| 2 | 2215372 | 3694 | [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) | 页面调试工具栏 (对 phpdebugbar 的封装)，教程请见：https://phphub.org/topics/2531 |
| 3 | 2173424 | 3570 | [barryvdh/laravel-ide-helper](https://github.com/barryvdh/laravel-ide-helper) | 使用 IDE 开发 Laravel 项目的好帮手，支持 Facade 方法跳转，相关讨论请见：https://phphub.org/topics/2532 |
| 4 | 1269005 | 2396 | [maatwebsite/excel](https://github.com/Maatwebsite/Laravel-Excel) | Excel 处理工具，中文处理时会出现乱码，推荐使用 [laravel-snappy](https://github.com/barryvdh/laravel-snappy)，历史讨论请见 https://phphub.org/topics/2477 |
| 5 | 1131952 | 702 | [aws/aws-sdk-php-laravel](https://github.com/aws/aws-sdk-php-laravel) | 亚马逊 AWS 服务的开发者工具包，亚马逊云已经在 2016 年 8 月 [正式落地中国](http://36kr.com/p/5050460.html)，这个包以后会常用到，教程请见：https://phphub.org/topics/2533 |
| 6 | 750405 | 1016 | [jenssegers/agent](https://github.com/jenssegers/agent) | 客户端 User Agent 解析工具（基于 Mobiledetect），教程请见：https://phphub.org/topics/782 |
| 7 | 711842 | 216 | [bugsnag/bugsnag-laravel](https://github.com/bugsnag/bugsnag-laravel) | Bugsnag 服务集成包（异常捕获服务，可惜国内访问效果不好），教程请见：https://phphub.org/topics/2534 |
| 8 | 683268 | 3268 | [zizaco/entrust](https://github.com/Zizaco/entrust) | 基于用户组的用户权限系统（必备） |
| 9 | 644651 | 821 | [barryvdh/laravel-cors](https://github.com/barryvdh/laravel-cors) | 跨域资源共享的支持  |
| 10 | 571221 | 963 | [barryvdh/laravel-dompdf](https://github.com/barryvdh/laravel-dompdf) | PDF 操作工具（基于 dompdf ） |
| 11 | 548367 | 1172 | [laravelbook/ardent](https://github.com/laravel-ardent/ardent) | 自动 [数据模型](http://laravel-china.org/docs/5.1/eloquent) 验证工具 |
| 12 | 534650 | 2364 | [tymon/jwt-auth](https://github.com/tymondesigns/jwt-auth) | JWT (JSON Web Token) 用户认证机制 |
| 13 | 496656 | 1977 | [lucadegasperi/oauth2-server-laravel](https://github.com/lucadegasperi/oauth2-server-laravel) | OAuth 2.0 支持 |
| 14 | 468263 | 595 | [maknz/slack](https://github.com/maknz/slack) | Slack 服务的集成 |
| 15 | 423728 | 1920 | [jenssegers/mongodb](https://github.com/jenssegers/laravel-mongodb) | MongoDB 数据库的支持  |
| 16 | 390006 | 4061 | [dingo/api](https://github.com/dingo/api) | 构建 API 服务器的完整解决方案 |
| 17 | 370341 | 912 | [itsgoingd/clockwork](https://github.com/itsgoingd/clockwork) | 配合 Chrome 浏览器下同名插件的调试工具 |
| 18 | 357552 | 600 | [anahkiasen/underscore-php](https://github.com/Anahkiasen/underscore-php) | Underscore.js 类似的 PHP 语法支持 |
| 19 | 355742 | 1191 | [laracasts/generators](https://github.com/laracasts/Laravel-5-Generators-Extended) | Laracasts 出品的代码快速生成工具（推荐） ，使用教程：https://phphub.org/topics/2535 |
| 20 | 344522 | 1200 | [cviebrock/eloquent-sluggable](https://github.com/cviebrock/eloquent-sluggable) | 文章标题 URL 别名处理工具 |
| 21 | 344237 | 382 | [laracasts/testdummy](https://github.com/laracasts/TestDummy) | Laracasts 出品的假数据创建工具 |
| 22 | 321543 | 709 | [davejamesmiller/laravel-breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) | 页面面包屑工具 |
| 23 | 309529 | 962 | [laracasts/utilities](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) | 将 PHP 变量转换为 JavaScript 变量 |
| 24 | 304501 | 621 | [roumen/sitemap](https://github.com/RoumenDamianoff/laravel-sitemap) | Sitemap 生成工具  |
| 25 | 303660 | 827 | [yajra/laravel-datatables-oracle](https://github.com/yajra/laravel-datatables) | jQuery DataTables 的后端支持  |
| 26 | 302076 | 336 | [webpatser/laravel-uuid](https://github.com/webpatser/laravel-uuid) | RFC 4122 标准生成的 UUID ，使用教程 https://phphub.org/topics/2538 |
| 27 | 301605 | 535 | [rcrowe/twigbridge](https://github.com/rcrowe/TwigBridge) | Twig 模板引擎支持 |
| 28 | 294356 | 218 | [intervention/imagecache](https://github.com/Intervention/imagecache) | 图片缓存增强工具  |
| 29 | 289380 | 958 | [indatus/dispatcher](https://github.com/Indatus/dispatcher) | 计划任务分发器（直接可替换掉 Cron），L5 内置了类似的功能  |
| 30 | 234578 | 589 | [jenssegers/date](https://github.com/jenssegers/date) | 日期处理工具（让 Carbon 支持多语言，中文用户的福音） |
| 31 | 234151 | 715 | [rap2hpoutre/laravel-log-viewer](https://github.com/rap2hpoutre/laravel-log-viewer) | 非常方便的页面 Log 查看工具，必备，不过使用时请注意访问权限控制  |
| 32 | 204976 | 1109 | [baum/baum](https://github.com/etrepat/baum) | 嵌套集合 (Nested Set) 模型的支持 |
| 33 | 204619 | 2146 | [anahkiasen/rocketeer](https://github.com/rocketeers/rocketeer) | 现代化的服务器代码部署工具 |
| 34 | 194675 | 1026 | [anahkiasen/former](https://github.com/formers/former) | 强大的表单构造器，教程请见 https://phphub.org/topics/2539 |
| 35 | 190032 | 375 | [barryvdh/laravel-snappy](https://github.com/barryvdh/laravel-snappy) | HTML 生成 PDF/Image 工具（利用 wkhtmltopdf） |
| 36 | 184879 | 361 | [thujohn/twitter](https://github.com/thujohn/twitter) | Twitter API 的支持 |
| 37 | 184078 | 228 | [orchestra/testbench](https://github.com/orchestral/testbench) | Laravel 扩展包的单元测试工具 |
| 38 | 181799 | 258 | [graham-campbell/flysystem](https://github.com/GrahamCampbell/Laravel-Flysystem) | 文件系统操作，多平台支持（AWS，Dropbox 等） |
| 39 | 180921 | 342 | [mews/purifier](https://github.com/mewebstudio/Purifier) | 用户提交的 Html 白名单过滤 |
| 40 | 175355 | 349 | [laracasts/presenter](https://github.com/laracasts/Presenter) | Laracasts 出品的 Presenter 方案 |
| 41 | 172640 | 852 | [venturecraft/revisionable](https://github.com/VentureCraft/revisionable) | 数据模型的操作记录（如管理员操作日记） |
| 42 | 168707 | 995 | [mcamara/laravel-localization](https://github.com/mcamara/laravel-localization) | Laravel 本地化功能增强 |
| 43 | 166917 | 366 | [league/factory-muffin](https://github.com/thephpleague/factory-muffin) | 允许更加方便的创建对象，一般在测试中常用（基本上是 ROR 的 factory_girl 的复制版） |
| 44 | 165140 | 271 | [robclancy/presenter](https://github.com/robclancy/presenter) | Elequent 的 Presenter 方案 |
| 45 | 163835 | 150 | [intouch/laravel-newrelic](https://github.com/In-Touch/laravel-newrelic) | 应用状态监控服务 NewRelic 开发者工具包 |
| 46 | 157930 | 855 | [xethron/migrations-generator](https://github.com/Xethron/migrations-generator) | 从现存的数据中以 migration 的形式导出数据库表，包括索引和外键，相当于 [数据库迁移](http://laravel-china.org/docs/5.1/migrations) |
| 47 | 149079 | 410 | [greggilbert/recaptcha](https://github.com/greggilbert/recaptcha) | reCAPTCHA 验证码的支持 |
| 48 | 144971 | 594 | [watson/validating](https://github.com/dwightwatson/validating) | 以 Trait 的方式来实现 Eloquent 数据模型保存的时候自动验证 |
| 49 | 142284 | 814 | [dimsav/laravel-translatable](https://github.com/dimsav/laravel-translatable) | 数据库的多语言翻译方案 |
| 50 | 138661 | 120 | [laracasts/behat-laravel-extension](https://github.com/laracasts/Behat-Laravel-Extension) | Behat 测试框架的 Laravel 支持 |
| 51 | 137782 | 200 | [jenssegers/rollbar](https://github.com/jenssegers/laravel-rollbar) | Rollbar 错误监控服务的自动集成 |
| 52 | 134723 | 330 | [torann/geoip](https://github.com/Torann/laravel-geoip) | 通过 IP 获取到对应的地理位置信息（GeoIP 数据库），请参考：https://phphub.org/topics/2537 |
| 53 | 133803 | 658 | [davibennun/laravel-push-notification](https://github.com/davibennun/laravel-push-notification) | App 的 Push Notification 发送工具，支持苹果的 APNS 和 安卓的 GCM |
| 54 | 128523 | 168 | [chumper/zipper](https://github.com/Chumper/Zipper) | ZIp 打包工具（基于 ZipArchive） |
| 55 | 127700 | 244 | [simplesoftwareio/simple-qrcode](https://github.com/SimpleSoftwareIO/simple-qrcode) | 二维码生成工具 |
| 56 | 125421 | 374 | [graham-campbell/markdown](https://github.com/GrahamCampbell/Laravel-Markdown) | Markdown 解析器 |
| 57 | 125315 | 164 | [aloha/twilio](https://github.com/aloha/laravel-twilio) | Twillio API 支持 |
| 58 | 123623 | 295 | [propaganistas/laravel-phone](https://github.com/Propaganistas/Laravel-Phone) | 手机号码，电话号码验证支持 |
| 59 | 121845 | 421 | [orangehill/iseed](https://github.com/orangehill/iseed) | 将数据从数据库以 seed 的方式导出，[数据填充](http://laravel-china.org/docs/5.1/seeding) 的逆向操作。（推荐） |
| 60 | 121350 | 380 | [sammyk/laravel-facebook-sdk](https://github.com/SammyK/LaravelFacebookSdk) | （非官方）Laravel 的 Facebook 开发者工具包 |
| 61 | 120891 | 497 | [vinkla/hashids](https://github.com/vinkla/laravel-hashids) | Hash ID 生成器，方便把数字的 ID 隐藏（基于Hashids），教程：https://phphub.org/topics/2536 |
| 62 | 116939 | 993 | [spatie/laravel-backup](https://github.com/spatie/laravel-backup) | 数据备份工具，支持压缩，支持各种文件系统（推荐） |
| 63 | 116718 | 459 | [mccool/laravel-auto-presenter](https://github.com/laravel-auto-presenter/laravel-auto-presenter) | 自动注入 Presenter |
| 64 | 111879 | 270 | [graham-campbell/throttle](https://github.com/GrahamCampbell/Laravel-Throttle) | 阀门控制工具 |
| 65 | 106306 | 1766 | [frozennode/administrator](https://github.com/FrozenNode/Laravel-Administrator) | 快速创建基于数据模型的 CRUD 管理员后台 |
| 66 | 105181 | 430 | [codesleeve/laravel-stapler](https://github.com/CodeSleeve/laravel-stapler) | 专为 ORM 定制的文件上传支持 |
| 67 | 100442 | 307 | [webpatser/laravel-countries](https://github.com/webpatser/laravel-countries) | 世界所有国家数据，包括首都汇率等 |
| 68 | 97451 | 848 | [prettus/l5-repository](https://github.com/andersao/l5-repository) | Repository 开发模式的支持 |
| 69 | 96491 | 371 | [pragmarx/google2fa](https://github.com/antonioribeiro/google2fa) | 用户认证方案，支持谷歌提倡的双向认证和 HOTP 认证算法 |
| 70 | 94117 | 195 | [hisorange/browser-detect](https://github.com/hisorange/browser-detect) | 浏览器检测工具，包括客户端对 JavaScript 和 CSS 支持情况的检测 |
| 71 | 93442 | 277 | [graham-campbell/htmlmin](https://github.com/GrahamCampbell/Laravel-HTMLMin) | 基于 minify 的 HTML 压缩工具 |
| 72 | 90609 | 156 | [toin0u/geocoder-laravel](https://github.com/geocoder-php/GeocoderLaravel) | 地理位置操作工具集（基于Geocoder） |
| 73 | 89845 | 491 | [edvinaskrucas/notification](https://github.com/edvinaskrucas/notification) | 页面消息提醒的组件 |
| 74 | 89333 | 403 | [laracasts/integrated](https://github.com/laracasts/Integrated) | PHPUnit 的集成测试支持 |
| 75 | 88682 | 779 | [laravel/envoy](https://github.com/laravel/envoy) | Laravel 官方出品的简单的部署工具 |
| 76 | 86793 | 137 | [felixkiss/uniquewith-validator](https://github.com/felixkiss/uniquewith-validator) | 表单验证规则增加字段之间的唯一性验证 |
| 77 | 81211 | 200 | [graham-campbell/exceptions](https://github.com/GrahamCampbell/Laravel-Exceptions) | 错误异常处理工具，支持开发和生产环境，使用 Whoops 进行错误显示 |
| 78 | 81076 | 163 | [thomaswelton/laravel-gravatar](https://github.com/thomaswelton/laravel-gravatar) | Gravatar 服务的支持 |
| 79 | 79494 | 477 | [mews/captcha](https://github.com/mewebstudio/captcha) | 图片验证码方案 |
| 80 | 79387 | 222 | [roumen/feed](https://github.com/RoumenDamianoff/laravel-feed) | Feed 生成器 |
| 81 | 79241 | 164 | [cviebrock/image-validator](https://github.com/cviebrock/image-validator) | 表单验证增加图片专属，如长宽，比例等 |
| 82 | 77849 | 125 | [laravelcollective/annotations](https://github.com/LaravelCollective/annotations) | 基于注解方式生成路由、事件、模型绑定的映射 |
| 83 | 77061 | 870 | [gloudemans/shoppingcart](https://github.com/Crinsane/LaravelShoppingcart) | 一个简单的购物车模块实现 |
| 84 | 75852 | 149 | [artisaninweb/laravel-soap](https://github.com/artisaninweb/laravel-soap) | Soap 协议客户端 |
| 85 | 75476 | 260 | [jlapp/swaggervel](https://github.com/slampenny/Swaggervel) | Swagger API 规范支持 |
| 86 | 73124 | 480 | [barryvdh/laravel-translation-manager](https://github.com/barryvdh/laravel-translation-manager) | 翻译辅助工具，包含 Web 界面 |
| 87 | 72532 | 515 | [patricktalmadge/bootstrapper](https://github.com/patricktalmadge/bootstrapper) | Twitter Bootstrap 支持 |
| 88 | 68952 | 133 | [soapbox/laravel-formatter](https://github.com/SoapBox/laravel-formatter) | 对不同输出格式进行转换，支持Array，CSV，JSON，XML，YAML |
| 89 | 66968 | 155 | [fedeisas/laravel-mail-css-inliner](https://github.com/fedeisas/laravel-mail-css-inliner) | 将 CSS 样式写入 HTML 里，用于邮件发送内容的样式定制 |
| 90 | 66881 | 747 | [nicolaslopezj/searchable](https://github.com/nicolaslopezj/searchable) | 以 Trait 的形式为 Eloquent 模型增加搜索功能 |
| 91 | 65754 | 109 | [benconstable/phpspec-laravel](https://github.com/BenConstable/phpspec-laravel) | PHPSpec BDD 测试框架的 Laravel 扩展 |
| 92 | 65489 | 193 | [watson/rememberable](https://github.com/dwightwatson/rememberable) | 让 Laravel 5 数据模型支持 remember() 方法 |
| 93 | 63895 | 373 | [rtconner/laravel-tagging](https://github.com/rtconner/laravel-tagging) | 为 Eloquent 模型增加打标签功能 |
| 94 | 62932 | 68 | [laravelcollective/remote](https://github.com/LaravelCollective/remote) | LaravelCollective 维护的 SSH 连接管理工具 |
| 95 | 60917 | 226 | [khill/lavacharts](https://github.com/kevinkhill/lavacharts) | Google 图表 JavaScript API 的封装 |
| 96 | 60203 | 115 | [anchu/ftp](https://github.com/harishanchu/Laravel-FTP) | 让 Laravel 支持 FTP 操作 |
| 97 | 58556 | 355 | [liebig/cron](https://github.com/liebig/cron) | 计划任务分发器（直接可替换掉 Cron），L5 内置了类似的功能  |
| 98 | 57174 | 348 | [lord/laroute](https://github.com/aaronlord/laroute) | JavaScript 读取路由信息的解决方案 |
| 99 | 57053 | 643 | [spatie/laravel-analytics](https://github.com/spatie/laravel-analytics) | Google 统计数据获取工具 |
| 100 | 56639 | 118 | [hieu-le/active](https://github.com/letrunghieu/active) | 非常方便的方案来判断导航元素的 `active` 状态 |
