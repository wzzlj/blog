---
title: sublime text 3 配置 python 开发环境  
layout: post
tags: python sublime-text  
---

## 在命令行中添加 subl 命令

就像 Textmate 的 mate 命令一样， Sublime Text 也有一个叫 subl 的命令行工具，可以通过终端来打开一个文件或者一整个文件夹。

- 当然需要先进行软链接才可以生效：
  
  `ln -s /Applications/Sublime Text.app/Contents/SharedSupport/bin/subl /usr/bin/`


- 这样就可以使用 `subl filename` 打开sublime了


- 如果需要查询所有可用的命令，打开帮助文件：`subs —help`



## 安装 Package Control

这是 sublime text 必装的插件管理器——这个东西必须要手动安装。

一旦你安装好了以后，你就可以使用 Package Control 来安装、移除或者升级所有的 ST3 插件了。

1. 依次点击 **View > Show Console** 打开 ST3 的控制台。
   
2. 在控制台中粘贴[官方网址](https://packagecontrol.io/installation#st3)内提供的代码，然后回车，最后重启 ST3。
   
3. 现在可以通过快捷键 **cmd+shift+P** 打开 Package Control 来安装其他的插件了。Package Control 支持自动补全，所以输入 **IP** 就可以看到 **Package Control：Install Package**，点击回车就可以搜索想要安装的插件了。
   
4. 其他的一些相关命令如下：   
    - ​List Packages 显示所有已安装的插件
    - Remove Packages 移除一个指定的插件
    - Upgrade Packages 更新一个指定的插件
    - Upgrade/Overwrite All Packages 更新所有已安装的插件

## 推荐的几个插件


## 快捷键

1. 跳转任意内容 **cmd+p** 用来快速查找和打开文件。你仅仅只需要工程文件的一部分路径或者文件名就可以很容易的打开这个文件。
2. 跳转到指定行 **ctrl+g**
3. 跳转到标志 **cmd+r**
4. 跳转到行首 **cmd+left-arrow-key** 与跳转行尾 **cmd+right-arrow-key**
5. 删除当前行 **crtl+shift+k**
6. 多重编辑（墙裂推荐！）  
    - 选定一个单词，按 **cmd+d** 来选择同样的单词
    - 再次用 **cmd+d** 继续选择下一个单词
    - 或者用 **cmd+单机** 来指定多个你想要同时修改的地方

   
   ​
