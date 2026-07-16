# 21 录制页规范

## 目标

用户从提词进入录制后，不应重新学习一套不同的控制语言。录制页继承提词页的字体、控制位置、速度逻辑、语音跟随状态、设置入口和动效节奏。

## 状态

### Ready
显示必要设置和录制按钮。

### Countdown
减少其它控制，倒计时清晰但不压迫。

### Recording
只保留录制状态、停止按钮、必要时间、核心脚本和极少量高频控制。

### Stopping / Processing
明确告诉用户正在保存，并防止重复操作。

## 录制状态

不能只使用红点。应同时提供颜色、文字“录制中”、时长、必要触觉和 VoiceOver 状态更新。

## 控制分层

高频：Start/Stop、Camera Switch、Speed、Speech Follow。

低频：Beauty、Quality、Stabilization、Mirror、Countdown、Text Styling。低频能力进入统一 Sheet，不使用多个临时 Overlay。

## 相机画面

Glass 控制必须在明暗背景上保持可读。必要时使用动态 Scrim，而不是厚重阴影。

## 不做

- 不同时展示所有录制与提词设置；
- 不让美颜面板永久占据画面；
- 不出现与提词页不同风格的按钮；
- 不在停止后让用户猜测是否保存。
