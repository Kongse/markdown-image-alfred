# 描述
复制本地图片或截图，快速上传图片到七牛云空间，并获取Markdown格式的图片地址。

# 功能

- 支持复制本地图片获取图片链接
- 支持截图获取图片图片链接
- 支持gif格式
- 操作结果会在通知栏显示

# 快捷键

`option + command + v`

# 依赖

- 已注册好的七牛图床
- 付费版Alfred

# 使用

- 下载[alfredworkflow](https://github.com/kaito-kidd/markdown-image-alfred/releases/download/1.1.1/markdown-image.alfredworkflow)文件，双击安装
- 复制本地一张图片(格式为：jpg、png、gif)，或截一张图
- 打开任意编辑器，按下`option + command + v`快捷键
- 自动插入上传后的图片链接

# 说明

第一次操作：需设置七牛的相关参数，会自动打开配置文件，填入配置即可<br/>
请注意：有可能填写配置时，配置中的英文引号会变成中文引号，请使用其他编辑器自行修改。<br/><br/>

插入的图片链接不是标准的Markdown格式，而是`img`标签<br/>
由于在retina屏幕下截图后，在非retina屏幕下图片会非常大，很难看<br/>
所以使用`img`标签的属性保证图片的大小和质量
