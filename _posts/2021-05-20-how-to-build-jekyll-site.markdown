---
layout: post
title:  "使用Gem更新Theme"
date:   2021-05-20 14:16:30 +0800
categories: jekyll
---
# 使用gem更新theme

- 访问[Gem仓库](https://rubygems.org/search?query=jekyll-theme) 选择一个你喜欢的theme

- 修改Gemfile，修改将minama 修改为新的

  ```
  #gem "minima", "~> 2.5"
  gem "jekyll-bootstrap-theme"
  ```

- 安装新的Gem

  ```
  bundle install
  ```

- 修改站点的theme

  打开`_config.yml`然后修改theme

  ```
  theme: jekyll-bootstrap-theme
  ```

- 重启站点

  ```
  bundle exec jekyll serve
  ```

  

