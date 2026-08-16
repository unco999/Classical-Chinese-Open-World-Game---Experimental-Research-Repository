# 古典中文开放世界游戏 — 任务生成实验仓库

事件积木（原型骨架 × 主题肌理 = 演绎内容）的交互设计工具。

## 在线试玩

<https://unco999.github.io/Classical-Chinese-Open-World-Game---Experimental-Research-Repository/>

## 工具说明

- 单文件 HTML（无外部依赖），浏览器直接打开即可使用
- 两种生成模式：
  - **🌐 随机漫游**：从主题词池出发，按"可链接类型表"随机漫游（逆序构建：先定结局后推前置），候选耗尽自动剪枝回溯，收束到 结果→业力→事件→新需求 回环
  - **🏗 骨架对照**：固定 14 节点 / 13 边示范骨架
- 主题肌理：和尚·施舍 / 道士·降妖 / 镖师·护送 / 医者·采药——同一词池结构，抽中不同主题内容即不同
- 支持：抽主题、换一套演绎（重新漫游）、过程展示（漫游 → 收束 → 回环）、节点详情与可链接类型、任务合述（`{槽位}` 组合）、结构体 JSON 导出（供游戏内逻辑消费）

## 本地使用

```text
git clone https://github.com/unco999/Classical-Chinese-Open-World-Game---Experimental-Research-Repository.git
# 直接双击 index.html 即可
```

## 更新

推送到 `main` 分支后，GitHub Pages 自动重新部署（约 1 分钟生效）。