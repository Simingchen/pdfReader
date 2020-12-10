# 项目一：word、excel、pdf查看器

该项目是一个PDF或excel格式的文件上传到后台，前端在需要将这份协议弄成可预览的形式。

### 功能
1. 在线预览word、excel、pdf等文件
2. 以3D形式浏览pdf文件

### 浏览 word,excel文件
1. 在线预览word、excel,可以直接引用微软的服务即可 

```
https://view.officeapps.live.com/op/view.aspx?src= + yourFile
```
2. 换上在线word文件即可，可[预览](https://view.officeapps.live.com/op/view.aspx?src=http://storage.xuetangx.com/public_assets/xuetangx/PDF/1.xls)demo

### 浏览pdf文件
1. 预览pdf文件需要用到pdf.js, 可以自己部署一个静态页面解析pdf文件
2. 相关文件在pdf文件夹下，包含语言包,viewer静态页面,js等文件。可以直接拷贝整个文件夹使用
3. 部署完后

```
https://simingchen.github.io/pdfReader/pdf/viewer.html?file= + yourFile
```
4. 换上在线pdf文件即可，可[预览](https://simingchen.github.io/pdfReader/pdf/viewer.html?file=https://simingchen.github.io/pdfReader/pdf/test.pdf)demo

# 项目二：3D阅读器

该项目是一个在线预览图片以3D，杂志的方式的项目。

### 功能
1. 预览图片以3D在线杂志的方式
2. 整个项目文件包含css, 动画声音voice, 图片images, 相关js等
3. 查看[地址](https://simingchen.github.io/pdfReader/index.html)
4. 使用配置 bookImgData.js 的变量作为图片服务器的资源对应，本地测试路径 'files/thumb'，暂时文件对应为数字 1.jpg 命名。