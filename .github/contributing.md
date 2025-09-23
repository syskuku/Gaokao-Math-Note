# 贡献指南 🤝

感谢你对 **高中数学快速上手文档** 的关注！  
我们欢迎任何形式的贡献，包括但不限于：修正错别字、补充知识点、优化示例题、改进排版等。  
为了保持项目的整洁和可维护性，请在贡献前阅读以下说明。

---

## 🛠 环境准备

1. **Fork 本仓库**
   - 点击右上角的 **Fork** 按钮，将仓库复制到你的 GitHub 账户。

2. **克隆到本地**
   ```bash
   git clone https://github.com/<你的用户名>/math-quickstart.git
   cd math-quickstart


3. **安装依赖**

   ```bash
   pnpm install
   ```

   > 推荐使用 [pnpm](https://pnpm.io/)，你也可以使用 npm 或 yarn。

4. **启动本地文档**

   ```bash
   pnpm docs:dev
   ```

   然后访问 [http://localhost:5173](http://localhost:5173) 预览 VitePress 文档。

---

## 📖 文档规范

1. 所有文档统一使用 **Markdown (`.md`)** 格式。
2. 文件命名请使用 **小写字母 + 中划线**，例如：

   * `functions-basic.md`
   * `trigonometry-intro.md`
3. 数学公式请使用 **LaTeX 语法**，例如：

   ```markdown
   $$
   f(x) = ax^2 + bx + c
   $$
   ```
4. 保持排版整洁，避免大段文字，推荐使用列表、表格、分节标题。
5. 新增章节请在 `docs/.vitepress/config.ts` 的侧边栏配置中注册。

---

## ✅ 提交规范

* 请确保提交信息简洁明了：

  * `fix: 修复二次函数部分的笔误`
  * `feat: 新增数列常见公式章节`
  * `docs: 优化三角函数示例题排版`

* 提交前请执行以下命令检查格式：

  ```bash
  pnpm lint
  ```

---

## 🔄 提交 PR

1. 在本地新建分支：

   ```bash
   git checkout -b feat/new-section
   ```
2. 修改并提交代码后，推送到远程仓库：

   ```bash
   git push origin feat/new-section
   ```
3. 在 GitHub 发起 Pull Request，并清晰描述你的修改内容。

---

## 🙌 如何贡献

* **修复错别字/公式错误**
* **补充知识点或例题**
* **改进目录结构**
* **提升文档可读性和排版**
* **翻译/多语言支持**

---

## 📜 协议

本项目使用 **MIT License**。
提交贡献即表示你同意你的修改在该许可下发布。

---

