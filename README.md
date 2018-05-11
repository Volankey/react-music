# BaiMusic
[查看演示](http://140.143.62.133/my-app-music/)
### 技术栈
- react
- react-router4
- react-redux+thunk
- react-transition-group
- Immutable

可以看到react全家桶了~
### 我为什么选用react
因为组件化呀~真的很方便，而且有庞大的社区作支持呢，我真的喜欢jsx的语法而不是模板，另外还有一点react可以为了我未来学习react-native先铺好道路.
### 为什么要写音乐播放器
一直觉得自己没有什么拿得出手的作品，我决定用心去做一个播放器吧，写好一点
### 基本功能
请看[查看演示](http://140.143.62.133/my-app-music/)
### 关于优化
优化做了一些包括

- dns预查询
- 浏览器缓存(nginx 配置 Etag和Expires字段 )
- 雪碧图
- 还有一些浏览器渲染的优化
- webpack打包压缩
### 自己实现的组件
- silder 无缝滚动（小圆点），以及自由横向滚动，
- 播放进度条组件
- 歌词组件 主要解析qq音乐的歌词
- List组件用于显示列表
### 功能
- [x] 记录播放历史
- [x] 播放音乐（列表循环、单曲循环、随机播放）上一首、下一首、
暂停、切换音乐
- [x] 歌词随时间滚动
- [x] 较为良好的交互
- [x] 搜索歌曲
- [x] 添加歌曲到播放列表
- [x] 歌单推荐
- [x] 流畅的滚动动画
- [ ] 添加歌曲到我喜欢
- [ ] 登录、注册
- [ ] 数据云端保存
- [ ] 收藏歌单