# 微信应用号/小程序开发&环境配置&工具破解&准备开发阶段

<img src="https://cloud.githubusercontent.com/assets/876707/18773863/cca59fae-8185-11e6-9d7b-050ba646b456.png" width = "172" height = "150" alt="LOGO" align=center />

官方简易教程：http://wxopen.notedown.cn
简易教程：框架、组件、API、工具、Q&A、介绍、设计、运营、文档、Github打包下载
官方已推出正式版本IDE，请前往下载：http://wxopen.notedown.cn/devtools/download.html


## 破解步骤

***Mac测试可用，Windows测试可用***

1. 下载开发工具，并安装（***注意：一定要安装0.9版本***）
2. 打开『微信Web开发者工具』的程序目录
  * Windows：使用资源管理器查看
  * Mac：右键点击图标，选择『显示包内容』
3. 进入程序目录后，替换以下文件（只需要替换0.9版本里的，0.7版本用来登陆）：
  * Windows：
    * \package.nw\app\dist\components\create\createstep.js
    * \package.nw\app\dist\stroes\projectStores.js 或 \package.nw\app\dist\stores\projectStores.js （0.9.092300之后版本）
    * \package.nw\app\dist\weapp\appservice\asdebug.js
  * Mac：
    * /Resources/app.nw/app/dist/components/create/createstep.js
    * /Resources/app.nw/app/dist/stroes/projectStores.js 或 /Resources/app.nw/app/dist/stroes/projectStores.js （0.9.092300之后版本）
    * /Resources/app.nw/app/dist/weapp/appservice/asdebug.js  

  **[替换的文件点击这里下载](https://github.com/gavinkwoe/weapp-ide-crack/archive/master.zip)**

4. Good luck

## 项目创建

1. 运行『微信Web开发者工具』
2. 通过微信扫描二维码
3. 创建项目
  * AppID：选【无AppId】
  * 项目名称：随便填
  * 本地开发目录：选择一个目录
4. 点击「添加项目」
5. 打开项目
6. 开始写代码
7. Good luck

## Demo运行

* 创建项目
* 打开项目所在目录
* 下载「Demo源代码」并解压覆盖
* 打开项目
* Good luck

## 常见问题（仅真对破解版）
1. 找不到所要替换的文件
  * 问题原因：开发工具版本不正确，老版本不支持
  * 解决方案：确保下载的程序版本在0.9.092100以上
2. Failed to load resource: net::ERR_NAME_NOT_RESOLVED http://1709827360.appservice.open.weixin.qq.com/appservice
  * 问题原因：通常是由于系统设置了代理如Shadowsocks等。
  * 解决方案：关闭代理，或者依次点击工具栏“动作”-"设置"，选择“不使用任何代理，勾选后直连网络”。
3. 修复asdebug.js报错
  * 问题原因：TypeError: Cannot read property 'MaxRequestConcurrent' of undefined
  * 解决方案：替换 /Resources/app.nw/app/dist/weapp/appservice/asdebug.js  
4. 扫码登录失败
  * 问题原因：please bind your wechat account to the appid first
  * 解决方案：先使用0.7版本的进行扫码登陆，登陆成功后，再用0.9的版本打开就直接进入了。
    * 0.7版本地址：http://dldir1.qq.com/WechatWebDev/release/0.7.0/wechat_web_devtools_0.7.0.dmg
5. mac版本升级到0.9.092300后，asdebug.js报错
  * 问题原因：TypeError: Cannot read property 'MaxRequestConcurrent' of undefined
  * 解决方案：替换 /Resources/app.nw/app/dist/weapp/appservice/asdebug.js  

## 工具截图

![IDE](https://cloud.githubusercontent.com/assets/876707/18745196/f4f0488e-80f3-11e6-844b-f45d7e52a23c.png)

![IDE](https://cloud.githubusercontent.com/assets/876707/18745200/f7a74870-80f3-11e6-83cf-df00f7f87f56.png)

