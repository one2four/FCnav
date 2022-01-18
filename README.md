# 蘑菇导航
FCnav导航，是一款使用PHP语音编写的导航工具
FCnav导航是根据[蘑菇导航](https://github.com/qu5/nav)修改而来的一个php网址导航。
支持php8，支持左侧锚点，支持自定义fontawesome图标。
js、css、字体文件使用本地调用
增加Links.txt备注信息
## 演示
pc样式
无

手机样式

无

## 使用方法
### 安装
下载后上传到php空间。
### 修改标题、简介
编辑`index.php`

### 链接编辑 `links.txt`

格式：
```
box
分类名称
fontawesome名称
链接名
链接地址
备注
链接名
链接地址
备注
.....
.....
endbox
```
### 左侧导航栏编辑`nav.txt` 
```
链接名称
链接地址
```

支持添加`#`锚点链接
```
学习探索
#学习探索
```

### 卡片分类图标

分类图片采用[fontawesome](https://fontawesome.com)，复制`<i class="fas fa-music"></i>`中的`fas fa-music`到links.txt。


## 捐赠
如果您觉得脚本对您有用，可以请我喝杯咖啡。

