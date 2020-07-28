[&#171; SDKBOX Home](http://sdkbox.com)

<h1>在Cocos Creator上使用SDKBox For Creator</h1>

## 在 Cocos Creator 工程上使用 SDKBox For Creator 插件
---

### 介绍

`SDKBox For Creator`是一个运行在 Creator 上的 SDKBox GUI 插件, 它使用户可以图形化集成, 更新 SDKBox 插件.

### 当前环境

* `CocosCreator` Ver.2.4.1 [安装](http://www.cocos.com/creator)
* `SDKBox Installer` 1.4.0.0 [安装](http://docs.sdkbox.com/en/installer/)

__PS__: 第一次运行, 如果你本机没有 `SDKBox Installer`, SDKBox For Creator 会自动帮你安装.

<!-- 
### 安装 SDKBox For Creator

* 在 Creator 的菜单中 `插件` -> `插件商店` 打开商店
* 搜索 `sdkbox`

![](../imgs/for_creator_store_search.png)

* 安装, 这里选择全局安装

![](../imgs/for_creator_install_query.png)

* 笔者目前这个版本, Creator 并没有给出安装成功的提示, 只能从 console 中看 log

![](../imgs/for_creator_install_log.png)

* 安装成功后, 如果没有在菜单中看到 SDKBox 项, 重启 Creator 试试

![](../imgs/ccc_tutorial_sdkbox_menu.png)
-->

### 在 Creator 上手动安装 SDKBox

如果你使用的是 Creator 1.4.0- 或 Creator 2.4.1+ 版本, 那么你可能需要手动来集成 SDKBox.

* 通过这个[链接](http://sdkbox.anysdk.com/gui/creator/sdkbox-1.4.0.zip)下载 SDKBox For Creator 插件包
* 安装 SDKBox For Creator
    - 全局安装: 将上一步中的插件包解压到 `~/.CocosCreator/packages` (Windows 用户为 `C:\Users\${你的用户名}\.CocosCreator\packages`) 目录下
    - 项目安装: 将上一步中的插件包解压到 `${你的项目地址}/packages` 目录

* 如果扩展菜单中没有出现 `SDKBox` 项的话, 也许需要重启 Creator

* packages 目录结构应该类似以下:
```
packages
|--sdkbox
    |--app
    |--main.js
    |--package.json
```


### 使用 SDKBox For Creator

* 在菜单栏中 `SDKBox` -> `Launch`
* 如果你的工程还从来没有构建过，那么你会看到如下界面

![](../imgs/for_creator_need_build_project.png)

* `SDKBox For Creator` 中的 Build 按钮, 或 Creator 菜单中 `项目` -> `构建发布` 都可以打开 Creator 的构建窗口

* 当你构建完成后, SDKBox 会主动提示你是否要安装 SDKBox 的插件, 这里点击是

![](../imgs/for_creator_install_plugin_query.png)

* 然后在 `SDKBox For Creator` 中, 可以安装你所需要的插件了


# 插件 API

* 插件的 API 文档可以在[这里](http://docs.sdkbox.com/zh/)查看

这个[文档](http://docs.sdkbox.com/zh/qa/integration-admob-to-creator/)介绍了如何在 Creator 工程中代码上调用 AdMob 的样例.
