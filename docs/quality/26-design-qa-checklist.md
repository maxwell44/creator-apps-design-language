# 26 Design QA Checklist

## 页面层级

- [ ] 用户第一眼能看到主内容。
- [ ] 主操作只有一个明显最高权重。
- [ ] 次级操作不会与主操作竞争。
- [ ] 页面没有不必要的卡片容器。
- [ ] 页面在 5 秒内可理解。

## Typography

- [ ] 使用语义 Typography Token。
- [ ] 单页字号数量受控。
- [ ] 数字使用等宽数字（如适用）。
- [ ] Dynamic Type 下不截断关键内容。

## Color

- [ ] 品牌色、脚本色、状态色职责分离。
- [ ] 不只依赖颜色表达状态。
- [ ] Light/Dark 均测试。
- [ ] 没有无意义的多彩图标。

## Layout

- [ ] 间距来自 4 pt 系统。
- [ ] 触控目标 ≥44×44 pt。
- [ ] 横屏布局经过设计。
- [ ] iPad 不无限拉伸。
- [ ] 控制出现不推动核心内容。

## Components

- [ ] 使用现有组件，不重复创建同义组件。
- [ ] Default/Pressed/Disabled/Loading 状态完整。
- [ ] SwiftUI/UIKit 表现一致。
- [ ] Back/Close/Done 语义正确。

## Motion 与 Glass

- [ ] 动画解释状态变化并使用统一 Token。
- [ ] Reduce Motion 有替代。
- [ ] Glass 只用于功能层。
- [ ] Reduce Transparency 可退化。
- [ ] 没有 Glass、厚阴影和渐变叠加。

## States

- [ ] Loading
- [ ] Empty
- [ ] Error
- [ ] Disabled
- [ ] Permission
- [ ] Success
- [ ] 内容安全与恢复路径清晰。

## Teleprompter 专项

- [ ] 脚本文字始终第一视觉层。
- [ ] 眼线位置稳定。
- [ ] 控制自动隐藏合理。
- [ ] 彩色脚本能力未被弱化。
- [ ] 录制状态持续清晰。
- [ ] 高频任务点击次数未增加。
