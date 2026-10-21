# 无文字立体卡片动效 Skill

为 Codex 提供一套从图片制作网页交互卡片的工作流程，包含可直接运行的无文字模板及机器人分层示例。

- 牌背翻入、主题光效、主体显现，约 4.3 秒后定格。
- 鼠标在舞台内移动，卡牌倾斜，主体与背景产生不同方向的视差；支持触屏拖动。
- 主体位于底板前方 80px，配合卡框厚度、柔和投影和动态遮罩光照增强立体感。
- 不添加标题、赠言、指引、幸运值或说明文案；仅保留图形重播按钮。
- 支持减少动态效果的系统偏好。

## 使用

将仓库安装为 Codex Skill 后，提供图片并说：

> 使用 `$image-card-motion-no-text`，把这张图做成无文字的立体交互卡片。

单张图片需要先通过可用的图像工具拆成同坐标系的完整原画、补全背景和透明主体。本 Skill 包含制作与验收规范，不包含图像生成模型服务，也不保证任意图片无需修整就能自动分层。

## 查看示例

下载仓库后，在浏览器中打开 `assets/card-template.html` 即可查看机器人示例。模板与 `assets/example/` 素材应保持相对目录关系。

## 文件

- [SKILL.md](SKILL.md)：工作流程与无文字约束。
- [assets/card-template.html](assets/card-template.html)：独立运行的动画模板。
- [references/motion-contract.md](references/motion-contract.md)：运动参数和验收要求。
- `assets/example/`：原画、背景和透明主体 PNG。

本例是图片分层与 CSS 3D 的交互效果，不是可任意环绕观察的三维角色模型。
