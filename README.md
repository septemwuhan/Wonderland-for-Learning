# Wonderland · 综合学习平台

一个持续建设中的多学科学习平台。目前提供语文、数学、英语、历史和西班牙语的独立学习入口。

## 学科模块

| 学科 | 目录 | 当前状态 |
|---|---|---|
| 语文 Chinese | `chinese-2026/` | 已建立入口，教材内容与练习模块待建设 |
| 数学 Math | `math-2026/` | 已建立入口，数学练习模块待建设 |
| 英语 English | `english-2026/` | 已有 U1—U8 学习内容、词汇、语法、阅读与练习 |
| 历史 History | `history-2026/` | 已建立入口，教材内容与练习模块待建设 |
| 西班牙语 Spanish | `spanish-2026/` | 保留原西班牙语词汇学习应用 |

各学科页面相互独立。新增或调整某一学科时，应优先在对应目录内修改，避免影响其他学科。

## 在线访问

- **综合学习首页：** https://septemwuhan.github.io/Wonderland-for-Learning/
- 语文：https://septemwuhan.github.io/Wonderland-for-Learning/chinese-2026/
- 数学：https://septemwuhan.github.io/Wonderland-for-Learning/math-2026/
- 英语：https://septemwuhan.github.io/Wonderland-for-Learning/english-2026/
- 历史：https://septemwuhan.github.io/Wonderland-for-Learning/history-2026/
- 西班牙语：https://septemwuhan.github.io/Wonderland-for-Learning/spanish-2026/

## 本地预览

本项目为纯前端网页，不需要后端服务。可以直接用浏览器打开相应目录中的 `index.html` 预览。若页面使用相对路径加载资源，建议通过本地静态服务器预览，以获得与 GitHub Pages 更接近的运行环境。

## 部署到 GitHub Pages

1. 将仓库代码提交到 GitHub 默认分支 `main`。
2. 打开仓库的 **Settings → Pages**。
3. 在 **Build and deployment** 中确认 Source 设置为 **GitHub Actions**。
4. 等待 GitHub Actions 工作流完成，并确认状态为 **Success**。
5. 打开上方综合学习首页及各学科链接，检查页面是否正常显示。

仓库当前名称为 `Wonderland-for-Learning`。如果仓库名或 GitHub 用户名再次变化，需要相应更新以上访问地址，以及本地 Git remote 地址。

## 数据与隐私说明

各学习模块的数据保存方式以模块自身实现为准。若使用浏览器 LocalStorage，学习记录仅保存在当前浏览器和设备中；清理浏览器数据或更换设备后，记录不会自动同步。除非另有说明，平台不提供跨设备账号同步功能。

## 项目维护建议

- 综合首页：维护根目录的 `index.html`。
- 学科内容：分别维护 `chinese-2026/`、`math-2026/`、`english-2026/`、`history-2026/` 和 `spanish-2026/`。
- 修改后检查 GitHub Actions 部署状态。
- 新增学科时，建立独立目录，并在根目录首页添加对应入口。
