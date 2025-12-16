# ToDoList / 计划控制器

简要说明（中文）

这是一个基于静态 HTML 的离线代办/计划页面。主页面为 `todo.html`，无需服务器：直接在浏览器中打开即可使用。仓库采用 MIT 许可证（详见 LICENSE 文件）。

Short description (English)

A lightweight offline ToDo / Plan HTML page. The main page is `todo.html`. No server required — open it in your browser. This repository is licensed under the MIT License (see the LICENSE file).

---

## 状态 / Repository status

- 语言：HTML（仓库语言统计显示 100% HTML）
- 主页面：`todo.html`
- 包含文件：`README.md`, `LICENSE`, `todo.html`

---

## 快速开始 / Quick start

中文：
1. 克隆或下载仓库：
   ```bash
   git clone https://github.com/Muimi272/ToDoList.git
   ```
2. 进入仓库并在浏览器中打开主页面：
   - 打开 `todo.html`（双击文件或通过浏览器的“打开文件”）。
3. 若页面包含 JavaScript 并使用 `localStorage`，任务会保存在本地浏览器（不会上传网络）。

English:
1. Clone or download the repo:
   ```bash
   git clone https://github.com/Muimi272/ToDoList.git
   ```
2. Open the project folder and open the main page in your browser:
   - Open `todo.html` (double-click or use your browser's File > Open).
3. If the page uses JavaScript with `localStorage`, tasks are stored locally in the browser (no network upload).

---

## 功能 / Features

- 在浏览器中添加、查看与管理任务（视 `todo.html` 的实现而定）
- 离线可用：无需后端，适合静态托管
- 轻量、零依赖：纯前端，无构建步骤

Features (English)

- Add, view and manage tasks in the browser (depending on `todo.html` implementation)
- Offline usage — no backend required
- Lightweight and zero-dependency: pure front-end, no build step

---

## 使用示例 / Usage example

中文：
- 在页面中输入任务标题或描述，点击“添加”或对应按钮将任务加入列表。
- 使用页面提供的编辑/删除控件修改或移除任务。
- 如果页面提供复选框或状态按钮，可用于标记任务完成/未完成。

English:
- Enter a task title/description and click the Add button (or equivalent) to add it to the list.
- Use edit/delete controls provided on the page to modify or remove tasks.
- Use any checkbox or status control to mark tasks complete/incomplete.

---

## 项目结构（当前） / Project structure (current)

- todo.html — 主页面（Main page）
- README.md — 项目说明（本文件）
- LICENSE — 许可证文件（MIT）

---

## 建议改进 / Suggested improvements

- 若未实现持久化：使用 `localStorage` 或 `IndexedDB` 保存任务
- 增加任务元数据：截止日期、优先级、标签/分类
- 响应式样式以适配移动端
- 导入/导出（JSON/CSV）以便备份
- 若需要多人同步：考虑添加后端或使用第三方云同步服务

---

## 贡献 / Contributing

欢迎提交 issue 或 pull request。请在 PR 中说明修改内容与验证步骤，保持改动小且易审阅。

Contributing

Feel free to open issues or submit pull requests. Explain your changes and verification steps in the PR and keep changes small and reviewable.

---

## 许可证 / License

本项目采用 MIT 许可证 — 详见 LICENSE 文件。

License

This project is licensed under the MIT License — see the LICENSE file for details.

---

## 联系 / Contact

作者: Muimi272
仓库: https://github.com/Muimi272/ToDoList

Contact

Author: Muimi272
Repo: https://github.com/Muimi272/ToDoList
