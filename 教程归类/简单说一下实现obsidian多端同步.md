今天学习了如何实现Obsidian在多平台同布

**工具** `WebDAV`，`remotely save插件`

1，在obsidian自带的第三方插件仓库下载`remotely save`(**需要挂VPN**)，接着就需要开始配置`WebDav`

2，`Webdav`可以选择`OneDrive`或者`坚果云`，不过经过网友反馈，**坚果云可能存在备份失败，在安卓上不兼容等问题**，推荐使用`OneDrive`

3，获取`OneDrive`的`WebDav`，教程链接
[[OneNote获取WebDAV]]

5，打开`Obsidian`的第三方插件`remotely save`，输入服务器地址https://app.koofr.net/dav/你在koofr上给onedrive网盘起的名字 ，并填入注册`OneDrive`时填写的邮箱和刚刚生成的密钥，这样就大功告成了！

>你可以根据自己的习惯，设置remotely save的自动同步和启动时即可同步，*我设置的的是一分钟同步一次和启动后1秒自动同步*
