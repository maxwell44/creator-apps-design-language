# 27 开发落地原则

## 先 Tokens，后页面

禁止页面直接新增任意颜色、字号、圆角、动画时长、阴影和间距。新值应先进入语义 Token，再由组件使用。

## 统一语义层

建议统一：AppColor、AppTypography、AppSpacing、AppRadius、AppMotion、AppGlass、AppIcon。

旧的 GreenTheme、FocusTokens、UIKitSettingsTokens 等逐步映射到统一语义层，不要求一次删除。

## 渐进迁移

1. 先建立共享 Token。
2. 新页面只使用新系统。
3. P0 页面逐步替换组件。
4. 旧组件标记 Deprecated。
5. 每次改造保持功能和埋点稳定。
6. 不将 UI 重构与业务重构捆绑。

## 组件优先级

第一批：Primary/Secondary Button、Icon Button、Script Card、Floating Toolbar、Setting Group/Row、Modal Dismiss Button、Loading/Empty/Error、Glass Surface。

第二批：Teleprompter Controls、Recording Controls、Speed Selector、Context Settings Sheet、Subscription Entry。

## Visual Tests

为首页空/有内容/大字体/深色、脚本卡各颜色、提词 Idle/Playing/Hidden Controls、Recording Ready/Countdown/Recording、Settings Free/Pro 与 Reduce Transparency 建立截图测试。

## Design Lint

可由 Codex 或 CI 检查：硬编码颜色、字号和间距，小于 44 pt 的按钮，重复 Settings Row，新增阴影，未处理 Reduce Motion，以及页面中过多 Glass 容器。

## Definition of Done

UI 改造只有同时满足以下条件才算完成：

- 视觉符合 CADL；
- 功能无回归；
- 无障碍通过；
- Light/Dark 通过；
- 横竖屏通过；
- 边缘状态完整；
- Design QA Checklist 通过；
- 代码不再新增旧 Design System 依赖。
