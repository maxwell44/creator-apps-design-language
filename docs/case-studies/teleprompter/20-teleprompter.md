# 20 提词页规范

## 核心目标

提词页的最高优先级是阅读舒适与表达稳定。

> The script is the primary visual layer.

## 页面层级

1. 脚本文字。
2. 当前阅读状态。
3. 播放/暂停。
4. 进度与时间。
5. 高频调整。
6. 低频设置。

## 默认状态

进入页面时可短暂显示控制。开始播放后，保持眼线稳定，控制层自动隐藏，触摸屏幕后恢复。

## 高频控制

建议保留 Play/Pause、Progress/Remaining Time、Speed 与 Record。是否常驻 Speech Follow 由真实数据决定。Mirror、Repeat、PiP 与完整字体设置进入统一上下文 Sheet。

## Typography

- 文本占据主要空间；
- 当前阅读行位于靠近镜头的稳定眼线区域；
- 控件出现不推动文本；
- 语音跟随高亮温和、不闪烁。

## Liquid Glass

可用于顶部轻量控制、底部浮动工具栏和快速速度面板。相关操作尽量合并在 1–2 个 Glass 容器中。

## 必须设计的状态

Idle、Countdown、Playing、Paused、Controls Hidden、Speech Listening、Speech Searching、Speech Error、PiP Active、Mirror、Ended。

## 不做

- 不设计成视频播放器；
- 不把所有功能常驻；
- 不使用大面积彩色面板；
- 不让速度、时间与状态抢夺文字焦点；
- 不因控制栏出现而改变脚本位置。
