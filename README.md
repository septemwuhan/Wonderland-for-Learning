# Math Wonderland · 数学奇幻乐园

一个适合 7–9 岁儿童的纯前端加减法练习 Web App。

## 功能
- 每轮 15 道动态生成的 100 以内加减法题
- 加减混合、只做加法、只做减法
- 轻松、标准、进阶三档练习
- 触屏数字键盘及物理键盘输入
- 即时反馈、进位/退位步骤提示
- 练习总结、错题回顾
- 使用浏览器 LocalStorage 保存累计星星和最近练习记录
- 响应式布局：横屏平板优先，兼容手机

## 本地预览
直接用浏览器打开 `index.html` 即可，无需安装依赖或启动后端。

## 部署到 GitHub Pages
1. 在 GitHub 创建一个 **Public** 仓库，名称填写 `math-wonderland`。
2. 将本项目中的全部文件上传到仓库根目录（确保 `index.html` 位于根目录）。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中，将 Source 设为 **GitHub Actions**。
5. 等待 Actions 工作流完成。之后网址为：

   https://septemwuhan.github.io/math-wonderland/

仓库名或 GitHub 用户名发生变化时，网址也会相应变化。

## 数据说明
应用不向服务器发送答题记录。练习历史仅保存在当前浏览器、当前设备的 LocalStorage 中；清理浏览器数据或更换设备后不会自动同步。
