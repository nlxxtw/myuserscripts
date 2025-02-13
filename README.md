## 网易云音乐脚本
[点击此处安装](https://update.greasyfork.org/scripts/459633/%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%3A%E4%BA%91%E7%9B%98%E5%BF%AB%E4%BC%A0%28%E5%90%AB%E5%91%A8%E6%9D%B0%E4%BC%A6%29%7C%E6%AD%8C%E6%9B%B2%E4%B8%8B%E8%BD%BD%E8%BD%AC%E5%AD%98%E4%BA%91%E7%9B%98%7C%E4%BA%91%E7%9B%98%E5%8C%B9%E9%85%8D%E7%BA%A0%E6%AD%A3%7C%E9%AB%98%E9%9F%B3%E8%B4%A8%E8%AF%95%E5%90%AC.user.js) (请确保浏览器已经安装了[TamperMonkey](https://www.tampermonkey.net/))

 [![Greasy Fork](https://img.shields.io/greasyfork/dt/459633?label=greasyfork%20installs)](https://greasyfork.org/zh-CN/scripts/459633)

 ### 功能
- 云盘快传
  - 无需文件快速上传云盘歌曲,三分钟解锁周杰伦。
- 歌曲下载
  - 不消耗vip下载次数,不是ncm加密文件。
  - 请将 `TamperMonkey` 插件设置中的 `下载模式` 设置为 `浏览器 API` 并将 `/.(mp3|flac|lrc)$/` 添加进`文件扩展名白名单` 以保证能正常下载。
- 歌曲转存云盘
  - 用网易云自身音源将歌曲快速上传到云盘，不需要完整的文件下载和上传过程。
- 高音质试听：
  - 解除网页端只能听标准音质的限制。
  - 在鼠标右键菜单中可进行优先试听音质的设置。
- 歌单页加载全部歌曲
- 评论区显示IP属地、使用指定的IP地址发送评论
- 歌单歌曲排序
  - 将歌单内歌曲按发行时间、红心数、评论数进行排序。
- 限免vip歌曲下载与上传
  - 对客户端内普通用户可免费试听的vip歌曲进行下载与上传。
- 云盘匹配纠错
  - 云盘歌曲匹配歌词、封面和评论。
- 云盘音质提升
  - 寻找网易云的音质比云盘文件更好的歌曲，以进行替换。只有上传成功时才删除原来低音质文件。
  -  需要是黑胶会员以获取高音质音源。
- 本地文件上传云盘
  - 可先编辑需要在云盘显示的歌手,专辑信息再上传。
- 云盘导入导出
  - 云盘歌曲导入另一账号。和云盘快传相同原理。 
### 使用说明
脚本安装完成后，登陆网易云音乐网页端。在右上角用户头像的 `我的主页` 中，使用云盘相关功能。在单曲、专辑、歌单（并非`我的音乐`的歌单，而是 `我的主页` 的歌单）页面使用下载、转存云盘功能。
 ### 问题说明
- 云盘快传:不保证内容的准确性、完整性。部分音质为算法升频。
- 上传失败时，浏览器控制台(F12)有输出具体错误内容。大多数时候重试一次就好了。
- 脚本不支持ViolentMonkey插件安装，使用ViolentMonkey会导致上传报错、获取不到`超清母带`、用不了SVIP的6T空间等问题。
### 截图
<img src="https://raw.githubusercontent.com/Cinvin/myuserscripts/main/screenshot/ncmHomePage.png" width="60%">

<img src="https://raw.githubusercontent.com/Cinvin/myuserscripts/main/screenshot/ncmPlaylist.png" width="60%">

<img src="https://raw.githubusercontent.com/Cinvin/myuserscripts/main/screenshot/ncmCommentIP.png" width="60%">

### 参考
网易云音乐API来自[Binaryify/NeteaseCloudMusicApi](https://gitlab.com/Binaryify/NeteaseCloudMusicApi)  