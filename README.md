概述
========
定制主题方法
这个目录商店开放实例的默认主题。

我们组织树模拟的目录结构
代码库,这样很容易告诉文件最终将在的地方
部署。我们将使用一个特殊的设置文件设置模板和
static  files路径正确指向这些文件。
 

![Alt text](/default_theme_screenshot.jpg?raw=true "Open edX Default Theme Screenshot")

主题创作
===============
定制你的主题:
- 叉这个存储库。
- 克隆到的主题目录在你edx-platform目录,重命名主题目录到您的新主题的名称。
- 上传自己的图片资产。
- 编辑。scss文件静态/ sass /和重命名文件和你的主题的名称。
-编辑lms.envs。在edx-platform json文件,设置“USE_CUSTOM_THEME”真,和“THEME_NAME”主题的名字。


 
=======

The code in this repo is licensed under the Apache 2.0 License.
See [LICENSE.txt](LICENSE.txt) for more info.
