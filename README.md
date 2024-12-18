# 老虎机游戏

这是一个简单的基于网页的老虎机游戏，使用 HTML, CSS, 和 JavaScript 实现。

## 功能特点

- 三个独立的滚轮，每个滚轮有 5 个图标
- 单次旋转和自动旋转功能
- 多种获奖组合：
  - 大奖：三个滚轮显示相同图标
  - 特别奖：对角线上的图标相同
  - 小奖：任意两个滚轮显示相同图标
- 视觉反馈：获奖时滚轮边框变色
- 结果显示：游戏结果实时显示

## 如何使用

1. 将 `slot.html` 文件下载到您的本地计算机。
2. 在网页浏览器中打开 `slot.html` 文件。
3. 点击 "Spin" 按钮进行单次旋转。
4. 点击 "Auto Spin" 按钮开始自动旋转，再次点击停止。

## 技术细节

- 使用 CSS 变量定义图标尺寸和数量
- 使用 JavaScript Promise 实现异步旋转效果
- 采用 CSS transitions 实现平滑的动画效果
- 自定义字体 "myFont" 用于游戏界面

## 自定义

您可以通过修改以下变量来自定义游戏：

- `numIcons`：更改图标数量
- `iconHeight`：调整图标高度
- CSS 中的 `:root` 变量：修改整体布局和尺寸

## 注意事项

确保 `myFont.ttf` 文件与 `slot.html` 在同一目录下，否则自定义字体可能无法正常显示。

## 贡献

欢迎提出建议和改进意见！请随时创建 issue 或提交 pull request。

## 许可

本项目采用 MIT 许可证。查看 [LICENSE](LICENSE) 文件了解更多信息。
