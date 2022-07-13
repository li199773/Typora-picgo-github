# Typora-picgo-github
Typora 是一款知名的 Markdown 编辑器，简单好用，体验良好。直接使用 typora 编写的 Markdown 文件，图片路径可能存在问题，导致页面上图片无法显示。改路径的话那就很麻烦了，好在 Typora 支持拖拽或复制来插入图片，并且可以复制到指定路径，或直接上传到图床。

1.GIthub配置
- github 新建一个仓库， 专门用于放置自己的图片
- settings—developer settings—new token—Note(请注意)填写token名称；将repo全部勾上√—完成(令牌只出现一次)

2.picgo配置

- 下载安装完后打开PicGo
- 点击左边图床设置进入GitHub图床
- 设定仓库名，填写：你的GitHub名/新建的GitHub库
- 分支，默认填main(不是master)
- 设定Token，写刚才保存的token令牌
- 指定存储路径，默认填img/
- 自定义域名：一般使用cdn来加速，使用方法是：https://cdn.jsdelivr.net/gh/你的github名/你新建的github仓库名
- 点击确定和设为默认图床
