### 第一部分：基础软件安装

* 打开学之思开源仓库地址：<https://gitee.com/mindskip/xzs-mysql>
* 加群QQ交流群，找管理员拿到数据库脚本
* 工具介绍

```软件简介
    VC_redist.x64 :  Redis数据库依赖、mysql依赖，先安装这个
    ideaIU-2020.3.3 ： java开发工具
    mysql-installer-community-8.0.19.0 ： Mysql数据库安装包
    navicat150_mysql_cs_x64 ： Mysql数据库连接工具
    rdm-2021.3.0.0 ：Redis连接工具
    Redis-x64-3.0.504 ： Redis内存数据库
    WebStorm-2020.3.3:  前端开发工具
    jdk-8u241-windows-x64：java运行环境
    node-v12.16.1-x64：前端vue运行环境
```

* 工具安装
* 所有准备工具安装已结束，下一步是调试开发环境
* 视频地址：<https://www.bilibili.com/video/BV1rp4y1b7Se>

### 第二部分：本地代码调试运行

* 打开仓库地址 <https://gitee.com/mindskip/xzs-mysql> ，下载源代码
* 打开教学文档 <https://www.mindskip.net:999>
* 修改java的镜像，改为阿里云镜像，默认是国外的，速度比较慢。默认是没有.m2文件夹的，可以自己新建一个。
* 打开数据库连接工具，导入mysql脚本
* 打开java代码，等待组件自动下载完成即可启动
* 添加sdk，建议使用1.8
* 启动后端程序
* 修改下配置文件，我们是本地连接，需要改下数据库连接地址
* 再打开教程，开始启动前端开发工具
* 前端依赖组件默认也是国外的，可按教程修为成国内的
* 组件下载完成，执行运行命令
* 学生前端也同样操作，启动
* 建议先将package-lock.json文件删掉，再执行npm install命令
* 前后端都已启动完成
* 视频地址：<https://www.bilibili.com/video/BV1Qh411S7RY>

### 第三部分：微信小程序开发

* 去官网下载小程序开发工具，并安装
* 去微信小程序官网 （微信公众平台），创建小程序
* 登录成功后，点击左边菜单开发下面的开发管理，在点击开发设置
* 拿到appId、AppSecret后配置到代码中
* 修改代码配置后，重新启动后台程序
* 打开微信开发工具，导入微信小程序代码
* 微信接口默认是<http://localhost:8000>，默认就可以了，和后端端口保持一致
* 启动后需要修改appid,和代码中的保持一致
* 微信小程序就启动成功了
* 视频地址：<https://www.bilibili.com/video/BV1mK4y127C5>
