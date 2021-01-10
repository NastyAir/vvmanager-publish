# VVManager
VVManager 是一套跨平台家庭媒体管理系统，帮助用户更好的管理访问家庭的流媒体数据。
包含移动端（HVPlayer）、服务端（VVManager）及后台管理Web端。

## 服务端（VVManager）
### 服务端配置使用说明
1. 解压缩后将VVManager.exe和config.json放在同一目录下
2. 保持配置后启动 VVManager.exe	，启动成功会输出监听的地址，使用过程中请勿关闭窗口。
3. 访问控制台输出的服务器地址进入web配置界面
   - 首页为概览，可以查看服务器整体情况
   - 频道页面可以对频道进行基础增删改查。喜欢、默认频道为初始化频道，点赞后的视频会加入喜欢频道，默认频道为全部视频
   - 媒体库页面配制视频地址，配置完成后需要点击扫描媒体库录入视频，当前不支持自动检测媒体库更新，添加文件后需要重新扫描（后续会加入定时扫描相关功能）
   - 视频页面可以查看视频
4. 安装app，推荐使用默认版本，如果默认版本无法正常工作则安装兼容版本。
5. 在初次使用会要求输入服务器信息，输入手机所在的网段的IP，如果你不知道手机所在网段就只能挨个测试上一步中服务器输出的地址信息。如果地址正确此时就可以正常观看了。

## 移动端(HVPlayer)
### 客户端使用说明
- 播放/暂停，点击屏幕
- 倍速切换，双击屏幕
- 快进/快退，按住屏幕向右滑动/向左滑动，屏幕下方会依次显示 此次快进时间、目标时间、视频总长度
- 跳转到，拖动屏幕下方进度条看跳转到任意位置
- 菜单，点击屏幕左上角的菜单键或者从左侧边缘往右滑动（部分全面屏手机可能会退出，需要在左上方侧滑才行）
- 视频排序切换，在呼出的菜单上方点击切换即可，默认模式（按修改时间排序）和随机模式（随机排序）两种
- 服务器切换，点击可重新进入服务器配置菜单。
