# Pithiness

The theme for [Hexo](http://zespia.tw/hexo/). 目前还处于完善当中。

## 一些修改    
由于网站配置中root为 / 导致css js文件路径误差  修改文件  
layout/_partial/head.ejs    
  <link rel="stylesheet" href="<%- config.root %>css/style.css" media="screen" type="text/css">
为    
  <link rel="stylesheet" href="css/style.css" media="screen" type="text/css">
layout/_partial/after_footer.ejs
<script src="<%- config.root %>js/jquery.imagesloaded.min.js"></script>
<script src="<%- config.root %>js/main.js"></script>
为
<script src="js/jquery.imagesloaded.min.js"></script>   
<script src="js/main.js"></script>   

<link rel="stylesheet" type="text/css" href="<%- config.root %>fancybox/jquery.fancybox.css">    
<script type="text/javascript" src="<%- config.root %>fancybox/jquery.fancybox.js"></script>      
为     
<link rel="stylesheet" type="text/css" href="fancybox/jquery.fancybox.css">   
<script type="text/javascript" src="fancybox/jquery.fancybox.js"></script>    
layout/_partial/header.ejs    

    <img class="circle" src="<%- config.root %>img/koala.jpg" alt="Anthem">
为
    <img class="circle" src="img/koala.jpg" alt="Anthem">
## 安装 Install

Execute the following command and modify `theme` in `_config.yml` to `pithiness`.

```
git clone git://github.com/okoala/hexo-theme-pithiness.git
```

## 更新 Update

Execute the following command to update pithiness.

```
cd themes/pithiness
git pull
```

## 效果图 Effect diagram

![](http://ww3.sinaimg.cn/large/a74ecc4cjw1e2ne9rb3nuj.jpg)

## 特性 Feature

Responsive 
fancybox
