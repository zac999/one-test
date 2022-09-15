##### 表 1.1：laravel 文件夹结构简介

| 文件夹名称           |                               简介                                |
| -------------------- | :---------------------------------------------------------------: |
| app                  |                 应用程序的业务逻辑代码存放文件夹                  |
| app/Console          |                   存放自定义 Aritisan 命令文件                    |
| app/Exceptions       |                         存放应用异常文件                          |
| app/Http/Controllers |                         存放控制器的文件                          |
| app/Http/Middleware  |                        存放【中间件】文件                         |
| app/Models           |                           存放数据模型                            |
| app/Providers        |                      存放【服务提供者】文件                       |
| bootstrap            |                 框架启动与自动加载设置相关的文件                  |
| composer.json        |                        应用依赖的扩展包】                         |
| composer.lock        |                        应用程序的配置文件                         |
| config               |                        应用程序的配置文件                         |
| database             |             数据库操作相关文件（数据迁移和数据填充）              |
| node_modules         |                         存放 NPM 依赖模板                         |
| docker-composer.yml  |                Docker 环境 Laravel Sail 的配置文件                |
| package.json         |                     应用所需的 NPM 包配置文件                     |
| phpunit.xml          |                    测试工具 PHPUnit 的配置文件                    |
| public               |         前端控制器和资源相关文件（图片，javascript,css）          |
| README.md            |                         项目介绍说明文件                          |
| resources            |                             应用资源                              |
| resources/js         |                     未编译的 JavaScript 代码                      |
| resources/css        |                             CSS 代码                              |
| resources/lang       |                            多语言文件                             |
| resources/views      |                             视图文件                              |
| routes/api.php       |                      用于定义 API 类型的路由                      |
| routes/channels.php  |                         事件广播注册信息                          |
| routes/Console.php   |                       用于定义 Artisan 命令                       |
| routes/web.php       |      用于定义 Web 类型的路由（重点，大部分情况下本书会用到）      |
| server.php           | 使用 php 内置服务器时的 URL 重写（类似于 Apache 的"mod_rewrite"） |
| storage              |       编译后的视图，基于会话，文件缓存和其他框架生成的文件        |
| storage/app          |               目录可用于存储应用程序使用的任何文件                |
| storage/framework    |                目录被用于保存框架生成的文件及缓存                 |
| storage/logs         |                        应用程序的日志文件                         |
| tests                |                         应用测试相关文件                          |
| vendor               |                         Composer 依赖模块                         |
| webpack.mix.js       |                   Laravel 的前端工作流配置文件                    |
| .gitignore           |                        被 Git 所忽略的文件                        |
| .env                 |                         环境变量配置文件                          |

###### 流程图

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```
