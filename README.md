# Yue Cao · 个人主页

一个可交互的 3D 机器狗个人主页，基于 three.js，纯静态页面，可直接部署到 GitHub Pages。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个 **Public** 仓库，名字必须是 `你的用户名.github.io`
2. 把本文件夹里的 `index.html`（和这个 README）上传到仓库根目录
   - 网页上传：仓库页面 → Add file → Upload files → 拖进去 → Commit changes
3. 等 1–2 分钟，打开 `https://你的用户名.github.io`
4. 如果没有生效：Settings → Pages → Source 选 `Deploy from a branch`，分支选 `main`、目录选 `/ (root)`

## 修改内容

所有文字都在 `index.html` 里，搜索下面的位置即可修改：

- 名字：`<h1>Yue Cao</h1>`
- 关于我：`id="card-head"`
- 技能：`id="card-legs"`
- 项目：`id="card-board"`
- 联系方式：`id="card-battery"`

## 本地预览

直接双击 `index.html` 用浏览器打开即可（需要联网加载 three.js 和字体）。
