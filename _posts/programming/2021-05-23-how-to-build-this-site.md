---
tags: jekyll gitpage markdown
---
# 开发运行环境

![](/assets/img/2021-05-23-how-to-build-this-site.png)

开发环境中：

- 使用`jekyll new username.github.io` 来创建工程

- 使用`bundle install` 来根据`Gemfile`安装gem库

- 使用`jekyll serve` 作为HTTP服务器来启动项目

  > 工程可以引用gem库的模版，也可以直接将模版拷贝到对应的工程文件中

运行环境中：

- 通过Github Action，在每次代码提交之后，自动调用`page_deploy.yaml` 将`_posts`中的markdown文件转化为`posts`中的HTML文件，来发布。
- 通过`http://username.github.io` 来发布站点

# 详细步骤

详细步骤请参考 [Jekyll 官网教程](https://jekyllrb.com/) , [jekyll-theme-chirpy模版](https://github.com/cotes2020/jekyll-theme-chirpy) 和[gitpage](https://pages.github.com/)相关说明。

# 使用图片

Powerpoint制作PNG格式图片的方法：

- 全选页面上所有图片
- 选择色彩为“中性灰”（powerpiont调色板，第一列倒数第三个灰色）
- 右键菜单选择“导出图片”，导出为PNG。
- 保存为`assists\img\*.png`

# 不支持的格式

github.io 支持markdown格式的文本和图片，但是不支持，下列格式：

- diagram
- HTML iframe
- reference







