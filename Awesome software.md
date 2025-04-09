# Awesome software



统计区块为 `name,download，support，code，explain`，分别为软件名，下载地址，支持的操作系统 ，是否开源 (是否商业) 以及对其的作用解析，需要注意 download 区块并不标注于 Linux 的下载方式，而是 windows，Linux 通常可直接 apt or pacman 操作软件包快速下载，windows 也存在 scoop winget choco 亦然可操作三者用于下载

> others：需要注意标记为 browser 图标的为 Web 端工具



## icon

Here is a record of commonly used icons

Linux![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)

Windows ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)

open source ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png)

no open source ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png)

browser ![浏览器](https://security-note.oss-cn-hangzhou.aliyuncs.com/浏览器.png)



## 浏览器插件

> life browser plugins

| name                                                         | explain                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 沉浸式翻译                                                   | 翻译软件：携带快捷键指定翻译、携带 pdf 翻译                  |
| Auto Refresh Plus                                            | 自动刷新监控：可自定义规则匹配关键字                         |
| 扩展管理器（Extension Manager）                              | 扩展管理：分类开启 or 关闭 and 卸载扩展 [以前分为 life 和 pentest 模式，但 pentest 插件以分去 firefox 操作，因此不再使用 ] |
| SuperCopy                                                    | broken copy 例如百度文库等禁止复制的站点                     |
| Video DownloadHelper                                         | 视频下载：多个国外站点视频下载                               |
| 猫抓                                                         | 视频下载：解析网页视频链接                                   |
| 集装箱                                                       | 辅助软件：购物历史价格、图片快捷右键搜索                     |
| [bypass-paywalls-chrome](https://github.com/iamadamdev/bypass-paywalls-chrome) | 付费突破：绕过某些付费站点如 medium 等                       |
| [Pornhub-Video-Downloader-Plugin](https://github.com/zgao264/Pornhub-Video-Downloader-Plugin) | 付费突破：下载 Pornhub 视频                                  |
| SingleFile                                                   | 页面保存：保存文章工具，直接下载为单个 HTML 保存 (简阅因此被我废弃) |
|                                                              |                                                              |
| Tampermonkey                                                 | 基于插件再生插件用于自动化 or broken                         |
| [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved) | tempermonkey：bilibili 增强脚本站点访问的一个脚本，下载视频、个性化等 |
| 血莲小助手                                                   | tempermonkey：自动化购物优惠卷                               |
| [CSDNGreener](https://greasyfork.org/zh-CN/scripts/378351)   | tempermonkey： 去除 CSDN 的恶心登陆才可复制突破与广告        |
| HackBar                                                      | Hackbar                                                      |
| OWASP PTK                                                    | 多功能：渗透测试辅助                                         |
| ==supperSearchIP==                                           | 信息收集：集成化插件                                         |
| ==FindSomething==                                            | Spider：站点端点信息                                         |
| ==Hack-Tools==                                               | 渗透测试常用 Payload                                         |
| [Heimdallr](https://github.com/graynjo/Heimdallr)            | 一款完全被动监听的谷歌插件，用于高危指纹识别、蜜罐特征告警和拦截、机器特征对抗(目前仅支持 chrome，因此等待重构 firefox 版本插件) |
|                                                              |                                                              |
| Hackers toolkit                                              | 常用 hash&encoder&decoder 并提供 Payload                     |
|                                                              |                                                              |
| Hunter                                                       | 邮箱收集                                                     |
| Shodan                                                       | shodan                                                       |
| IP Address and Domain Information                            | IP、IP 地理信息、域名 and IP Whois、ASN                      |
| Wappalyzer                                                   | 框架技术监测                                                 |
| Keyfinder                                                    | 查找页面内敏感信息                                           |
| Gotanda                                                      | 信息收集插件(被动式鼠标右键)                                 |
| Proxy SwitchySharp                                           | 代理切换                                                     |
| FireProxy                                                    | 代理切换                                                     |
| Set Character Encoding                                       | 切换页面编码                                                 |
| User-Agent Switcher and Manager                              | User-Agent                                                   |
| X-Forwarded-For Header                                       | X-Forwarded-For                                              |
| d3coder                                                      | 解码                                                         |
| EditThisCookie                                               | Cookie edit，并显示 cookie 过期时间                          |
| retire.js                                                    | 扫描器检测具有已知漏洞的 JavaScript 库的使用                 |
| XSS辅助工具                                                  | XSS payload 编码工具(F4盲打Payload生成)                      |
| HTTP-TRACKER                                                 | 记录传输的 HTTP/s 数据                                       |
| ScanAnnotation                                               | 扫描注释内容                                                 |
| Check My Links                                               | 一个谷歌浏览器扩展程序，允许您检查网页是否有损坏的链接（响应代码 404 等），作为 bughunter 来使用可检测任意外链以及超链接 |
| quick                                                        | 一键开启 or 关闭 JS                                          |
| Admin tools                                                  | 信息收集辅助                                                 |
| bulkopen                                                     | 该插件记录打开的网址                                         |
| Canvas Blocker                                               | anti WebRTC 防止获取真实 IP                                  |



## 远程连接

> 这里所谓的远程连接即：超级终端包含 SHELL 管理与远程会话以及 Serial 协议，等等其他远程协议，其中 XShell 较为特别，它仅管理 SHELL 与远程会话

| name                                             | Download                                                     | support                                                      | open                                                         | explain                                                      |
| ------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [electerm](https://github.com/electerm/electerm) |                                                              |                                                              |                                                              | Terminal/ssh/telnet/serialport/*sftp* client(linux, mac, win) |
| termius                                          |                                                              |                                                              |                                                              | 个人版免费 ssh/sftp 远程                                     |
| windterm                                         | [link](https://github.com/kingToolbox/WindTerm)              | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | A professional cross-platform SSH/Sftp/Shell/Telnet/Serial terminal. [ Linux 下传输文件遇到问题] |
| mRemoteNG                                        | [link](https://github.com/mRemoteNG/mRemoteNG)               | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | mRemoteNG is the next generation of mRemote, open source, tabbed, multi-protocol, remote connections manager. |
| tabby                                            | [link](https://github.com/Eugeny/tabby)                      | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | A terminal for a more modern age                             |
| mobaxterm                                        | [link](https://mobaxterm.mobatek.net/)                       | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 一个集所有协议为一身的超级终端                               |
| xshell                                           | [link](https://www.xshell.com/zh/)                           | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | Xshell ~                                                     |
| realvnc-vnc-viewer                               | [link](https://aur.archlinux.org/pkgbase/realvnc-vnc-viewer) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | VNC 远程桌面软件，我用的比较舒服(被 mRemoteNG 替代)          |
| Remmina                                          |                                                              |                                                              | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | RDP,SSH,X2GO,我在 linux 下比较喜欢的远程桌面工具             |
| freerdp                                          |                                                              |                                                              |                                                              | 跨平台 rdp 远程连接，安装后使用 xfreerdp                     |
| 1Remote                                          | [link](https://1remote.org/zh-cn/)                           | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 1Remote是一款现代化的个人远程会话管理员和启动器，使用它你可以管理从一个入口管理多种远程会话。 |
| dbever                                           |                                                              |                                                              | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 数据库远程连接                                               |
| chat2db                                          | [link](https://github.com/chat2db/Chat2DB)                   |                                                              | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 阿里云开发 - 远程数据库连接                                  |
| Microsoft Remote Desktop Beta                    | [link][https://install.appcenter.ms/orgs/rdmacios-k2vy/apps/microsoft-remote-desktop-for-mac/distribution_groups/all-users-of-microsoft-remote-desktop-for-mac] |                                                              | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | Mac m2 系列使用 rdp 远程桌面，支持键盘监控，远程复制传输，自动调整分辨率 |
|                                                  |                                                              |                                                              |                                                              |                                                              |



## 效率增强与辅助

| name                                          | Download                                        | support                                                      | open                                                         | explain                                                      |
| --------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Quicker                                       | [link](https://getquicker.net/)                 | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | windows 效率神器，浑身都是效率功能 (内置 OCR 截图识别)       |
| Mouse+                                        | [link](https://wwr.lanzoui.com/b02c3ahje)       | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 扩展生成鼠标右键轮盘，用于增强效率                           |
| [espanso](https://github.com/espanso/espanso) |                                                 |                                                              |                                                              | 文本扩展器是一种程序，可以检测您何时键入特定关键字并将其替换为其他关键字，社区插件支持：https://hub.espanso.org/ |
| autocomplete                                  | [link](https://github.com/withfig/autocomplete) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | terminal AI 提示补全 (跟代码补齐的插件类似)                  |
| thefuck                                       | [link](https://github.com/nvbn/thefuck)         | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 命令输入错误后可用于 fuck 一下提示正确的命令                 |
| Maya                                          | [link](https://github.com/25H/Maya)             | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | Maye 一个简洁小巧的快速启动工具                              |
| ==cheat==                                     |                                                 |                                                              |                                                              | 命令行备忘单                                                 |
| pot-desktop                                   |                                                 | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 跨平台 GUI 翻译软件(内置 OCR 识别)                           |



## 输入法

| name    | Download | support | open | explain           |
| ------- | -------- | ------- | ---- | ----------------- |
| Fcitx 5 |          |         |      | Google 中文输入法 |



## 包管理

| name       | Download                                        | support                                                      | open                                                         | explain                                  |
| ---------- | ----------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------- |
| Scoop      | [link](https://github.com/ScoopInstaller/Scoop) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | A command-line installer for Windows.    |
| winget-cli | [link](https://github.com/microsoft/winget-cli) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | Windows Package Manager CLI (aka winget) |



## 终端

| name          | Download | support | open | explain               |
| ------------- | -------- | ------- | ---- | --------------------- |
| ==alacritty== |          |         |      | 我喜欢的终端 terminal |



## 压缩&解压

| name    | Download                                       | support                                                      | open                                                         | explain                    |
| ------- | ---------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------- |
| bandzip | [link](https://www.bandisoft.com/bandizip/dl/) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 快捷快速的一个压缩解压软件 |
| 7-zip   | [link](https://www.7-zip.org/)                 | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 7z 曾经出现过提权漏洞      |
| winrar  | [link](http://www.winrar.com.cn/)              | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | windows 老牌压缩解压软件   |
| Nanazip | [link](https://github.com/M2Team/NanaZip)      | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 一款超级好用的压缩软件     |
| PeaZip  | [link](https://github.com/peazip/PeaZip)       | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 开源，简介，无广告好用     |



## 全局搜索

| name              | Download                                           | support                                                      | open                                                         | explain                                              |
| ----------------- | -------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------------- |
| everything        | [link](https://www.voidtools.com/zh-cn/)           | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ?                                                            | GUI 全局搜索                                         |
| fzf               | [link](https://github.com/junegunn/fzf)            | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 命令行全局搜索，命令行的 Everythig (windows)         |
| EverythingToolbar | [link](https://github.com/stnkl/EverythingToolbar) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | GUI bar 全局搜索 (测试后仅在windows 10 上可完美运行) |



## 浏览器

| name    | Download                                                     | support                                                      | open                                                         | explain                        |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------ |
| Brave   | [link](https://github.com/brave/brave-browser/)              | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 快速，加密，内置 Tor，数字货币 |
| Chrome  | [link](https://www.google.com/intl/zh-CN/chrome/)            | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | Google 浏览器                  |
| Firefox | [link](https://www.mozilla.org/en-US/firefox/browsers/)      | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | Firefox 浏览器                 |
| Edge    | [link](https://www.microsoft.com/en-us/edge?form=MA13FJ#evergreen) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 微软 Windows 内置浏览器        |



## 截图

| name              | Download                                                     | support                                                      | open                                                         | explain                                                      |
| ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ==Snipaste==      | [link](https://www.snipaste.com/)                            | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 截图的同时可在图上用于教学的其他字符                         |
| ksnip             | [link](https://github.com/ksnip/ksnip)                       | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 在 Linux 下我比较常用的截图软件(以前用，由于不可进行进一步图形编辑，换用列 flameshot) |
| shutter           | [link](https://github.com/shutter-project/shutter)           | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 这个截图软件我用在我的 i3wm-Manjaro 上                       |
| ==flameshot==     | [link](https://github.com/flameshot-org/flameshot)           | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 在 Linux 我比较喜欢用的一个截图软件                          |
| FastStone Capture | [link](https://www.faststone.org/FSCaptureDownload.htm)      | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 用来截长图 (不开源可破解)                                    |
| ScreenToGif       | [link](https://github.com/NickeManarin/ScreenToGif)          | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 动态截取 Gif                                                 |
| terminalizer      | [link](https://github.com/faressoft/terminalizer#installation) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 仅记录你的终端操作，可生成任意格式文件 (一般在 Linux 下可以用用，不推荐) |
| peek              | [link](https://github.com/phw/peek#official-distribution-packages) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 动态截取 Gif (推荐，简单，好用)                              |



## 录屏

| name       | Download                                         | support                                                      | open                                                         | explain                |
| ---------- | ------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- |
| obs-studio | [link](https://github.com/obsproject/obs-studio) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 推流，录屏的开源好工具 |
|            |                                                  |                                                              |                                                              |                        |

## 思维导图

| name  | Download | support                                                      | open | explain      |
| ----- | -------- | ------------------------------------------------------------ | ---- | ------------ |
| xmind |          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | no   | 思维导图软件 |
|       |          |                                                              |      |              |

## 文本编辑器

| name      | Download | support                                                      | open                                                         | explain                                          |
| --------- | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------ |
| gedit     |          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ？                                                           | txt 等其他非编程 markdown 的编辑器，好用且轻量级 |
| Notepads  |          | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | Windows 的 gedit，notepad 的增强版               |
| Noteapd++ |          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | notepad 的增强版                                 |



## 网盘&下载

> 操作 bilibili-evolved 中的 aria 2 input 模式，可批量下载 bilibili 视频

| name                      | Download                                                | support                                                      | open                                                         | explain                                                      |
| ------------------------- | ------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| qBittorrent               | [link](https://www.fosshub.com/qBittorrent.html)        | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 种子下载                                                     |
| 百度网盘/baidunetdisk-bin | [link](https://pan.baidu.com/download#win)              | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 网盘下载                                                     |
| 蓝奏云                    | [link](https://www.lanzou.com/)                         | ![浏览器](https://security-note.oss-cn-hangzhou.aliyuncs.com/浏览器.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 网盘下载                                                     |
| 阿里云盘                  | [link](https://drchan.top/)                             | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 网盘下载                                                     |
| 迅雷/xunlei-bin           | [link](https://dl.xunlei.com/)                          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 种子下载                                                     |
| N_m3u8DL-CLI              | [link](https://github.com/nilaoda/N_m3u8DL-CLI)         | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | m3u8 视频下载                                                |
| hitomi                    | [link](https://github.com/KurtBestor/Hitomi-Downloader) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 视频下载 (直接简单，复制视频 URL 可直接尝试下载)             |
| Bilibili-Evolved          | [link](https://github.com/the1812/Bilibili-Evolved)     | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 这是一个专门增强 bilibili 站点访问的一个 tempermonkey 插件，其中携带了bilibili 视频下载功能，所以这里顺便一提 |
| aria2                     | [link](https://github.com/aria2/aria2)                  | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | aria2 是一个轻量级的多协议、多源、跨平台下载工具，在命令行中操作。它支持 HTTP/HTTPS、FTP、SFTP、BitTorrent和Metalink。 |





## 视频播放器

| name | Download                                                     | support                                                      | open                                                         | explain                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------- |
| mpv  | [link](https://sourceforge.net/projects/mpv-player-windows/files/64bit/) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 跨平台的视频播放器 GUI and Bash |



## 音乐&音乐播放器



| name         | Download                                            | support                                                      | open                                                         | explain                      |
| ------------ | --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------- |
| qqmusic      | [link](https://y.qq.com/download/index.html)        | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | tencent                      |
| lx-music     | [link](https://github.com/lyswhut/lx-music-desktop) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 一个基于 electron 的音乐软件 |
| YesPlayMusic | [link](https://github.com/qier222/YesPlayMusic)     | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 高颜值的第三方网易云播放器   |



## 协作办公

| name               | Download                                                     | support                                                      | open                                                         | explain                                    |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ |
| 钉钉/dingtalk-bin  | [link](https://www.dingtalk.com/)                            | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 钉钉(机器人自动推送)                       |
| 浙政钉             | [link](https://www.ding.zj.gov.cn/pc/index.html#/)           | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 浙政钉                                     |
| 腾讯文档/wedoc-bin |                                                              | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 腾讯文档                                   |
| 飞书               | [link](https://www.feishu.cn/download?from=navigation_bar_app_download) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 飞书(用它的原因是因为其支持机器人自动推送) |



## 视频会议

| name            | Download                             | support                                                      | open                                                         | explain  |
| --------------- | ------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| 钉钉/dingtalk   | [link](https://www.dingtalk.com/)    | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 钉钉     |
| 腾讯会议/wemeet | [link](https://meeting.tencent.com/) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 腾讯会议 |



## 社交

| name                      | Download                                            | support                                                      | open                                                         | explain                                                      |
| ------------------------- | --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| QQ/deepin-wine-qq         | [link](https://weixin.qq.com/)                      | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | QQ(由于腾讯官方已经开始维护 Linux qq 分支流，所以摒弃 wine 版 QQ) |
| wechat/deepin-wine-wechat | [link](https://im.qq.com/index)                     | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 微信(摒弃)                                                   |
| telegram/telegram-desktop | [link](https://github.com/telegramdesktop/tdesktop) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 加密，匿名                                                   |
| discord                   | [link](https://discord.com/download)                | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 交友                                                         |
| BetterDiscord             | [link](BetterDiscord)                               | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 他并不是一个社交软件，而是作为一个增强 discord 的插件 or 软件 |







## 思维导图

| name  | Download                  | support                                                      | open                                                         | explain  |
| ----- | ------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| xmind | [link](https://xmind.cn/) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 思维导图 |



## 格式转换 Format

| name          | Download                                        | support                                                      | open                                                         | explain                                                      |
| ------------- | ----------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| FileConverter | [link](https://github.com/Tichau/FileConverter) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 可直接操作文件于鼠标右键菜单进行格式转换                     |
| marp-cli      | [link](https://github.com/marp-team/marp-cli)   | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | markdown 转 PPT，可生成 HTML 以 PPT 形式演示呈现，也可直接转换为 PPT |
| slidev        | [link](https://github.com/slidevjs/slidev)      | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | markdown 以 PPT 形式呈现                                     |



## 图片提取

| name       | Download                                                     | support                                                      | open                                                         | explain                                  |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------- |
| IconViewer | [link](https://www.botproductions.com/iconview/download.html) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 提取应用程序的 icon ==右键->属性->icon== |





## PPT 相关软件

| name         | Download | support                                                      | open | explain                 |
| ------------ | -------- | ------------------------------------------------------------ | ---- | ----------------------- |
| PPT 模板大全 | 微软商城 | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ？   | 获取免费的 PPT 模板使用 |



## 终端 banner 生成

| name   | Download | support                                                      | open | explain              |
| ------ | -------- | ------------------------------------------------------------ | ---- | -------------------- |
| toilet | ?        | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) ? | ?    | 终端字符 banner 生成 |



## 密码管理

| name      | Download                                 | support                                                      | open                                                         | explain                                                      |
| --------- | ---------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| keeweb    | [link](https://github.com/keeweb/keeweb) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | keeweb 密码存储于一个加密的数据库中，只有知道进入数据库密码的人才可获取到全部明文 |
| keepassxc |                                          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 由于在 Linux 下 keeweb 无法编译成功，所以这里使用 keepassxc 代替，若仅想使用 keeweb 可自行下载 app 后缀的文件 |



## Github 相关

| name         | Download | support | open | explain                                     |
| ------------ | -------- | ------- | ---- | ------------------------------------------- |
| export-stars |          |         |      | Github 任意用户 start 项目一键导出 URL 保存 |





## Markdown 编辑器

| name     | Download                                     | support                                                      | open                                                         | explain                                |
| -------- | -------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| Typora   | [link](https://typora.io/)                   | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 我个人常用的 markdown 编辑器           |
| marktext | [link](https://github.com/marktext/marktext) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 一个很漂亮简洁且快速的 markdown 编辑器 |
| notable  | [link](https://github.com/notable/notable)   | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 一个很漂亮简洁且快速的 markdown 编辑器 |



## 图床软件

| name          | Download | support | open | explain                                                      |
| ------------- | -------- | ------- | ---- | ------------------------------------------------------------ |
| Picgo         |          |         |      | 快捷上传图床图片                                             |
| Picgo-command |          |         |      | 该工具用 typora 下载，继承在 typora 上使用上传图片到图床，一般 linux 下我使用，windows 下则直接用 picgo 即可 |
| qiniuClient   |          |         |      | 客户端图床管理工具                                           |





## 代码与开发

### 代码编辑器

这里仅列出本人所学习的编程的代码编辑器

| name                                               | Download                                    | support                                                      | open                                                         | explain                          |
| -------------------------------------------------- | ------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------- |
| vscode                                             | [link](https://code.visualstudio.com/)      | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 微软开源，通过插件可操作任意编程 |
| golangd                                            | [link](https://www.jetbrains.com/go/)       | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | Golang IDE                       |
| pycharm                                            | [link](https://www.jetbrains.com/pycharm/)  | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | Python IDE                       |
| phpstorm                                           | [link](https://www.jetbrains.com/phpstorm/) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | PHP IDE                          |
| [massCode](https://github.com/massCodeIO/massCode) | [link](https://www.jetbrains.com/phpstorm/) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png)![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 代码片段编辑器                   |





### 代码环境



## 微信多开

* https://github.com/huiyadanli/RevokeMsgPatcher



## 防撤回

* WeChat/QQ/TIM：https://github.com/huiyadanli/RevokeMsgPatcher



## VPN Softwares 

| Softwares                                                    | System  | mode | explain                                                      |
| ------------------------------------------------------------ | ------- | ---- | ------------------------------------------------------------ |
| [clash](https://github.com/Dreamacro/clash)                  | ALL     | Cli  | Clash 是一个跨平台的基于规则的代理实用程序，运行在网络和应用层上，开箱即用地支持各种代理和反审查协议 |
| [clash-verge](https://github.com/zzzgydi/clash-verge)        | ALL     | GUI  | GUI，支持 clash.Permium 内核，clash.meta 内核                |
| [clashN](https://github.com/2dust/clashN)                    | Windows | GUI  | GUI，支持 clash.Permium 内核，clash.meta 内核                |
| [ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid) | Android | GUI  | GUI，支持 clash.Permium 内核，clash.meta 内核                |
| [ClashX.Meta](https://github.com/MetaCubeX/ClashX.Meta)      | Mac     | GUI  | GUI，支持 clash.Permium 内核，clash.meta 内核                |
| [clashX](https://github.com/yichengchen/clashX)              | MAC     | GUI  | GUI，支持 clash.Permium 内核                                 |
| [clash_for_windows_pkg](https://github.com/Fndroid/clash_for_windows_pkg) | Windows | GUI  | GUI，支持 claash.Permium 内核                                |
| [Clash-for-Windows_Chinese](https://github.com/Z-Siqi/Clash-for-Windows_Chinese) | Windows | GUI  | clash for windows 汉化版. 提供 clash for window s的汉化版, 汉化补丁及汉化版安装程序 |
| [ClashForAndroid](https://github.com/Kr328/ClashForAndroid)  | Android | GUI  | GUI，支持 claash.Permium 内核                                |
|                                                              |         |      |                                                              |
| [v2rayN](https://github.com/2dust/v2rayN)                    | Windows | GUI  | GUI，Cilent，支持 v2ray，xray 内核                           |
| [NekoBoxForAndroid](https://github.com/MatsuriDayo/NekoBoxForAndroid) | Android | GUI  | SOCKS (4/4a/5) HTTP(S) SSH Shadowsocks VMess VLESS WireGuard Trojan Trojan-Go ( trojan-go-plugin ) NaïveProxy ( naive-plugin ) Hysteria ( hysteria-plugin ) TUIC |
| [openvpn](https://openvpn.net/community-downloads/)          |         |      |                                                              |



## 版权水印



## U盘&系统创建

| name       | Download                                 | support                                                      | open | explain                                                      |
| ---------- | ---------------------------------------- | ------------------------------------------------------------ | ---- | ------------------------------------------------------------ |
| rufus      | [link](https://github.com/pbatard/rufus) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | yes  | 在 Windows 上最常用的 U 盘系统制作软件                       |
| etcher-bin | [link](https://www.balena.io/etcher/)    | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ?    | 型一代一键制作系统安装镜像，在 Linux 上我最为常用            |
| Etcher     |                                          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)? | ?    | U 盘启动盘制作 (Linux) 在 Linux 操作系统上制作 U 盘启动盘==不要自动挂载必须取消挂载再制作== |
| WoeUSB     |                                          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)? | ?    | U 盘制作工具 (比较支持 windows 的 U 盘启动制作)              |
| GParted    |                                          | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)? | ?    | U 盘格式化与分区助手                                         |
|            |                                          |                                                              |      |                                                              |





## 文本比较-compare

| name                                             | Download | support | open | explain     |
| ------------------------------------------------ | -------- | ------- | ---- | ----------- |
| heaptrack                                        |          |         |      | KDE 开源    |
| [winmerge](https://github.com/WinMerge/winmerge) |          | windows |      | Github 开源 |







## 系统&安全防护与优化

* 全能优化工具：[optimizer](https://github.com/hellzerg/optimizer)

### 系统优化与管理

| name               | Download                                                     | support                                                      | open                                                         | explain                                                 |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------- |
| SophiApp           | [link](https://github.com/Sophia-Community/SophiApp)         | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | windows 内置功能调整开关工具                            |
| W11ClassicMenu     | [link](https://www.softpedia.com/get/Tweak/System-Tweak/Windows-11-Classic-Context-menu.shtml) | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ？                                                           | windows 11 右键菜单回调                                 |
| Defender Control   | [link](https://www.sordum.org/9480/defender-control-v2-1/)   | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ？                                                           | windows defender 一键持久开关                           |
| Windows10Debloater | [link](https://github.com/Sycnex/Windows10Debloater)         | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 用于删除 windows 11，10 的过时垃圾软件 (无用且消耗 CPU) |
| neofetch           |                                                              |                                                              |                                                              | 装逼与查看系统信息并存                                  |

### 扫垃圾

| name                                    | Download                                                     | support                                                      | open                                                         | explain                                             |
| --------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------------- |
| dism++                                  | [link](https://github.com/Chuyu-Team/Dism-Multi-language)    | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | dism 扫垃圾能力也很出众，它可以说是一个系统全能工具 |
| Geek                                    |                                                              | ![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![no](https://security-note.oss-cn-hangzhou.aliyuncs.com/no.png) | 彻底清理某软件痕迹，注册表也携带                    |
| [BleachBit](https://www.bleachbit.org/) | [link](https://www.bleachbit.org/download/file/t?file=BleachBit-4.4.2-setup.exe) | ![linuxOS](https://security-note.oss-cn-hangzhou.aliyuncs.com/linuxQ.png)![windows](https://security-note.oss-cn-hangzhou.aliyuncs.com/windows.png) | ![yes](https://security-note.oss-cn-hangzhou.aliyuncs.com/yes.png) | 作为一种半清理的扫地软件，具体功能如下截图          |

![image-20221114124022927](https://security-note.oss-cn-hangzhou.aliyuncs.com/image-20221114124022927.png)

### 软件卸载

### 自动化备份

| name      | Download | support | open | explain                                       |
| --------- | -------- | ------- | ---- | --------------------------------------------- |
| Timeshift |          |         |      | arch 怕滚挂就装，快照，系统本地备份，数据恢复 |





## mac 软件记录

| softwares                                                    | explain                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [BetterRename](https://www.publicspace.net/BetterRename/)    | 批量重命名                                                   |
| [Beyond Compare](http://www.scootersoftware.com/download.php) | 比较文件内容差异                                             |
| [Dash](https://kapeli.com/dash)                              | api 离线文档软件                                             |
| [Hex Fiend](https://ridiculousfish.com/hexfiend/)            | 16 进制编辑器                                                |
| ihosts                                                       | host 内容管理 - app store 安装                               |
| [Karabiner-Elements](https://github.com/pqrs-org/Karabiner-Elements) | 键位映射自定义                                               |
| https://github.com/iina/iina                                 | 媒体播放器                                                   |
| utm                                                          | mac 下的开源虚拟机，不支持快照，但可以 clone                 |
| [parallels_desktop_crack_18.0.1-53056](https://github.com/andrewssobral/parallels_desktop_crack_18.0.1-53056) | parallels mac 下的虚拟机软件，相比 utm 不开源并收费，但专门为 mac 而创造的软件，比 utm 好用很多 |
| stats                                                        | menu bar ， 显示系统硬件状态                                 |
| xbmc                                                         | 影视资源并播放                                               |
| [BetterDisplay](https://github.com/waydabber/BetterDisplay)  | mac 虚拟屏幕、hidpi 屏幕，等其他屏幕设置                     |
| https://pilotmoon.com/scrollreverser/                        | 解决触控板鼠标反向问题                                       |
| [keycastr](https://github.com/keycastr/keycastr)             | KeyCastr，一个开源的击键可视化工具。                         |
| giphy                                                        | gif 截图软件                                                 |
| ibar                                                         | 解决刘海屏幕遮挡 menubar 的小图标                            |
| [hammerspoon](https://github.com/Hammerspoon/hammerspoon)    | 借助 Lua 实现功能惊人的强大 macOS 桌面自动化                 |
|                                                              |                                                              |
