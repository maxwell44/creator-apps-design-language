# 12 组件总则

## 组件存在的条件

一个模式只有在多个页面复用、行为需要保持一致、状态复杂、需要统一无障碍或长期维护时，才应成为组件。

## 每个组件必须定义

- Purpose
- Anatomy
- Variants
- States
- Behavior
- Content Rules
- Accessibility
- Motion
- Dark Mode
- Do / Don't

## 状态要求

正式组件至少考虑 Default、Pressed、Selected、Focused、Disabled、Loading，以及适用时的 Error 与 Pro Locked。

## 命名

使用语义命名：PrimaryButton、ScriptCard、FloatingToolbar、SettingRow。

不使用视觉命名：GreenButton、RoundedWhiteCard、GlassView2、ModernRow。

## 一致性

同一组件在 SwiftUI 和 UIKit 中必须共享 Token、尺寸、状态、动效、文案规则和无障碍语义。
