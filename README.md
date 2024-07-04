# markit
## 开发列表
当前开发版本![markit alpha tag](https://img.shields.io/github/v/tag/heiyehk/markit-updater-test)

未来正式版本开源地址：**[markit](https://github.com/heiyehk/markit)**

## v0.0.9-alpha
feature:
1. 增加微软TTS朗读引擎
2. 增加朗读聚焦段落功能，可在主题中配置是否打开，默认关闭
3. 增加选项中朗读功能的人声试听功能
4. 增加选项侧边标题功能

refactor:
1. 重构获取章节内容功能，抽离公共部分

pref: 一些优化
bugfix: 一些bugfix

## v0.0.8-alpha
feature:
1. 调整朗读功能，可全局显示朗读控件
2. 优化选项部分功能

bugfix: 修复部分bug

## v0.0.7-alpha
feature: 
1. 更新依赖版本；调整摸鱼模式，只在阅读下才有
2. 阅读模式的功能以及左右按键的滚动增加平滑滚动。

bugfix: 修复部分bug

**注意**: 需要清除缓存刷新后使用

## v0.0.6-alpha
feature: 增加部分快捷键操作，软件运行标题调整
pref: 优化部分UI
refactor: 重构渲染章节内容

## v0.0.5-alpha
**请注意改版本需要删除位于 `AppData\Roaming\com.markit.heiyehk` 数据库**   
此版本主要调整订阅相关的功能
feature: markdown body的一些功能，订阅功能调整  
refactor: 对于右键菜单的position传入参数调整  
bugfix: 右键弹窗的bug  

## v0.0.4-alpha
feature:
1. 增加便笺的图片本地化，支持粘贴

bugfix:
修复书源json解析bug，兼容漫画情况下的content问题

## v0.0.3-alpha
增加许多功能，修复许多bug。

feature:
1. 书源的排序和筛选功能
2. 部分右键弹出功能
3. 字体内容
4. 阅读小说界面的主题功能
5. 阅读小说界面底部工具功能
.....
refactor: 重构json数据格式解析，目前兼容绝大部分书源。
perf: 优化了许多功能

bugfix: 修复了许多bug
