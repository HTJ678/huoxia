# 活下来 · 水资源枯竭

一个单文件的文字生存游戏。30 天，一天一个选择，撑到最后或者死在某个夜里。

四个世界共用一套骨架（水资源枯竭 / 海平面上升 / 温度过高 / 温度过低），**目前只做了第一个**。

## 玩法

打开网页就能玩，无需安装。点一个世界开始，每天选一个动作，第二天自动结算。

- 开局 6 瓶水，每天喝 1 瓶
- 摆盆接雨、下楼打井、去超市、看手机、在家躺着
- 夜里会有强盗；邻居会来借水；手机里的消息决定你能走哪条路
- 一共 7 个结局

## 技术

- 单文件 HTML，零依赖，可离线打开
- 音乐全部用 Web Audio 现场合成（没有音频文件）
- 强盗 / 夜里事件会调用 navigator.vibrate 并让画面轻微抖动（手机上有反馈）

## 关键词 / Keywords

survival game, text-based, single file, zero dependency, vanilla JS, Web Audio, procedural music, branching endings, 文字游戏, 生存游戏, 多结局

## License

MIT
