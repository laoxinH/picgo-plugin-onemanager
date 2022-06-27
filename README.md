# picgo-plugin-onemanager-uploader

[githu仓库](https://github.com/laoxinH/picgo-plugin-onemanager/)
[我的博客](https://laoxin.top)

plugin for [PicGo](https://github.com/Molunerfinn/PicGo)

- 一个通过[onemanager](https://github.com/qkqpttgf/OneManager-php) 将图片上传到onedrive的[PicGo](https://github.com/Molunerfinn/PicGo)插件

### 为什么制作这个插件

我发现没有能比较好的将onedrive作为图床的方案

发现其中一个原有就是onedrive的外链有时效性,没过多久就会失效

然而结合onemanager的可以刷新外链保持链接有效性

然后发现了picgo这个软件,摸索文档开发了这么一个垃圾小插件

勉强实现了功能,实现方式不算优雅,后期我会慢慢优化

> 目前采用onemanager的公用图床方案，就是只要知道你的图床地址谁都能上传，但是只能上传不能看到其他图片，过去没少重要的图片也可以使用本教程中提供的示例图床地址

总的来说,穷是原罪,当然欢迎[投食](#赞赏码开发维护不易请赏杯茶水费)
### 简单的教程

> #### 插件安装

在picgo中搜索关键词onemanager即可

> #### onemanager设置

- 准备好一个**[onemanager](https://github.com/qkqpttgf/OneManager-php)** 
- **[onemanager](https://github.com/qkqpttgf/OneManager-php)** 搭建教程请自行搜索
- 进入你的**[onemanager](https://github.com/qkqpttgf/OneManager-php)**后台管理界面

![后台界面](https://pan.laoxin.top/od1/ykfile/3f60a3e0db1fb0016b52c065a9099bb0.png)

> 我这里设置的是`/ykfile`文件夹

- 打开你刚刚设置的图床文件夹
- 复制浏览器地址栏url

![图床文件夹](https://pan.laoxin.top/od1/ykfile/ce1dcc30ee6091e4668613f76b2a46c4.png)

> 我这里是`https://pan.laoxin.top/od1/ykfile`后面需要将这个url填入到插件url栏<br>
> 注意 ykfile 文件夹需要提前创建<br>
> 如果你只是挂载了一个网盘,那么`https://pan.laoxin.top/od1/ykfile`这行地址中不会存在`od1`

- 打开插件设置
- 将刚刚复制的url填入即可

![插件设置](https://pan.laoxin.top/od1/ykfile/ccf7a5bf68f2e8567d6afc7a0633c033.png)

**经过上面的设置你已经获得了一个比较完美的onedrive图床**

### 赞赏码(开发维护不易,请赏杯茶水费)
<div align=center><img width="250" height="250" src="https://github.com/laoxinH/MyScript/blob/main/alpay.jpg"/></div>

