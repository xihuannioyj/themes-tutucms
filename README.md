#### 主题介绍
本主题主要参考了晨星博客免费发布的CX-UDY wordpress主题，修改为tutucms支持的模版。

#### 模版说明
1. 本主题采用的是H5自适应代码，PC和移动都能够友好呈现。
2. 本主题仅包含首页、分类、文章、话题和标签模版，其他像系统文章模版等没有。


#### 安装说明 
1. 从这里 https://github.com/yalay/themes-tutucms/releases 下载最新release版本。
2. 在你tutucms系统的template文件夹创建一个目录，比如yalay
3. 将release版本压缩包解压到yalay目录里。
4. tutucms后台启用yalay模板。

#### 注意事项
1. 分类页背景图片是固定规则地址，比如img/cate_1.png，1为你的分类id，对应替换即可。
2. 栏目的显示模式需要是文章模式，图集模式不支持。
3. 系统默认的分页比较难看，这个修改了tutucms系统的分页代码，需要将这里的的Page.php替换tutucms系统里的这个文件core/class/Ext/Page.php。
