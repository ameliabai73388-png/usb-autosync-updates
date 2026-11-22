# U盘自动同步

Windows 10/11 x64 托盘同步程序的公开更新源。

- USB 存储设备每分钟检查一次；按设备分别存放。
- 增量同步新增、修改和删除；被覆盖或删除的旧文件保留在本机历史目录。
- 通过 HTTPS 获取签名更新清单，验证 Ed25519 签名与 SHA-256 后升级。
- 程序只从这里下载更新；不会上传 USB 文件、备份内容或个人设置。

固定更新清单：`https://raw.githubusercontent.com/ameliabai73388-png/usb-autosync-updates/main/latest.json`

首次使用：下载 EXE，选择备份文件夹并保存。关闭设置窗口后继续在托盘运行。

更新程序前请从托盘退出旧版，再运行新的 EXE。1.2.1 起内置本仓库更新地址。
