今天学习了如何实现Obsidian在多平台同布

**工具** ==WebDAV，remotely save插件==

1，在obsidian自带的第三方插件仓库下载remotely save(**需要挂VPN**)，接着就需要开始配置WebDav

2，Webdav可以选择OneDrive或者坚果云，不过经过反馈，**坚果云可能存在备份失败，在安卓上不兼容等问题**，推荐使用OneDrive

3，获取OneDrive的WebDav，教程链接
[[OneNote获取WebDAV]]

4，然后在**koofr**的**preference**中选择**password**，下滑找到**APP password**生成Webdav即可

>**请复制生成的密钥，配置remotely save要用到！**

5，打开**Obsidian**的第三方插件**remotely save**，输入服务器地址https://app.koofr.net/dav/onedrive  (==地址最后的onedrive并不是固定的，你可以填写自己给网盘的命名==)并填入注册**OneDrive**时填写的邮箱和刚刚生成的密钥，这样就大功告成了！

>你也可以根据自己的习惯，设置remotely save的自动同步和启动时即可同步，*我设置的的是一分钟同步一次和启动后1秒自动同步*