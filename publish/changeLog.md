### 新增

- 新增对播放详情页歌词大小、是否缩放、对齐方式的设置，可以去设置-播放详情页设置查看
- 新增播放详情页通过歌词调整播放进度，默认关闭，需要到设置-播放详情页设置开启，开启后在播放详情页拖动歌词时将会出现跳转当前行歌词播放的按钮
- 新增全屏状态，按F11可以进入、退出全屏状态，由于全屏时会隐藏控制栏按钮，所以需要使用鼠标右键双击（详情页的任意地方都可以）来关闭播放详情页
- 新增动态主题“道法自然”，你可以预先设置一个亮色主题及暗色主题，此后将根据系统的亮、暗主题色自动切换为你预先设置的相应主题。注：鼠标 右击 此主题项即可打开亮、暗色主题设置窗口。
- 新增对kw源卡拉OK歌词的支持

### 优化

- 优化Windows任务栏缩略图工具栏控制按钮在浅色任务栏下的显示效果
- 添加音频可视化与音频输出设备冲突的提示
- 优化歌词的播放偏移
- 优化托盘菜单操作（#686）
- 优化播放下载列表时的切歌性能

### 修复

- 修复“当前的声音输出设备被改变时暂停播放歌曲”设置无效的问题
- 修复桌面歌词没有处理停止播放状态的问题
- 修复AppImage包无法运行的问题
- 修复Windows任务栏缩略图工具栏控制按钮的歌曲收藏按钮状态更新问题
- 修复使用链接导入的歌单无法在我的列表打开原歌单详情页的问题
- 修复播放下载列表的歌曲时增删下载任务导致正在的歌曲序号改变时，不会更新到新增序号的问题

### 文档

添加LX中定义的快捷操作汇总说明到常见问题中，这是目前可用的鼠标、键盘快捷操作，它们都可以在更新日志中找到

- 鼠标右击播放栏的歌曲图片封面可以定位当前播放的歌曲
- 鼠标右击播放栏进度条上的LRC按钮可以锁定/解锁桌面歌词
- 歌曲搜索框、歌单链接输入框内鼠标右击可以将当前剪贴板上的文字粘贴到输入框内
- 鼠标右击搜索界面中的单条搜索历史可以将其移除
- 歌曲列表内的文字在选中后，鼠标右击可以复制已选中的文字，此功能只对搜索、歌单、排行榜、我的列表中的列表有效
- 鼠标在播放详情页内右键双击可以关闭播放详情页
- 鼠标左击播放栏上的歌曲名字可以将它复制
- 鼠标右击“道法自然（英文Auto）”主题可以打开亮、暗主题设置窗口
- 歌曲搜索框的候选内容可以用键盘上下方向键选择，按回车键搜索已选内容
- 在歌单详情页按退格键可以返回歌单列表
- 歌曲列表中可以使用Ctrl、Shift键进行多选，这类似Windows下的文件选择，详情看常见问题列表多选部分
- 在我的列表内可以使用Ctrl+f键打开搜索框进行列表内歌曲搜索，搜索框按Esc键可以关闭搜索框，搜索框内按上下方向键可以选择歌曲，按回车键跳转到已选歌曲，按Ctrl+回车可以跳转并播放已选歌曲
- 在我的列表按住Ctrl键可以进入列表拖动模式，此时可以用鼠标拖动列表调整列表的位置
- 编辑列表名时按Esc键可以取消编辑
- 按F11可以进入、退出全屏状态
