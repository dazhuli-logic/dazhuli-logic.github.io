# Dazhu Li academic website

这是一个可直接用于 GitHub Pages 的纯静态学术主页，只使用 HTML 和 CSS。

## 页面

- `index.html` — Home（About + News）
- `news.html` — 完整 News 列表；首页只保留最新三条
- `research.html` — Research（研究兴趣、当前研究、项目和发表）
- `teaching.html` — Teaching
- `talks.html` — Talks
- `students.html` — Students
- `activities.html` — Academic Service
- `dazhu-li-cv.pdf` — CV（顶部导航直接打开，可在浏览器中查看和下载）
- `cv.html` — 旧 CV 页面地址的兼容跳转
- `style.css` — 全站共用样式

`publications.html` 是旧地址的兼容跳转页，会自动转到 `research.html`。网站内容已根据 `CV_English.pdf` 填写；Students 与学术活动中仍缺少、且无法从 CV 确认的内容会等待补充。

## 发布到 GitHub Pages

1. 解压 ZIP；不要只上传 ZIP 文件。
2. 打开 GitHub 仓库，选择 **Add file → Upload files**。
3. 选中解压文件夹里面的所有文件并上传，确保 `index.html` 和 `research.html` 直接位于仓库最上层。
4. 提交到 `main` 分支。
5. 打开 **Settings → Pages**，将 Source 设为 **Deploy from a branch**，选择 `main` 和 `/(root)`。

## 已包含的附件

- `profile.jpg` — 首页个人照片
- `dazhu-li-cv.pdf` — 网站可查看、下载的英文 CV

以后替换照片或 PDF 时，保持这两个文件名不变，即可无需修改网页代码。
