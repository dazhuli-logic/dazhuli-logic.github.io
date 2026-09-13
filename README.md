# Dazhu Li academic website

这是一个可直接用于 GitHub Pages 的纯静态学术主页模板。它只使用 HTML 和 CSS，没有外部字体、JavaScript 或 Google 资源。

## 文件结构

- `index.html` — Home（About + News）
- `publications.html` — Publications
- `teaching.html` — Teaching
- `talks.html` — Talks
- `students.html` — Students
- `activities.html` — Academic Activities
- `cv.html` — CV
- `style.css` — 全站共用样式

所有 `[方括号中的文字]` 都是需要替换的占位内容。

## 发布到 GitHub Pages

### 方法一：个人主页仓库（推荐）

1. 在 GitHub 新建一个仓库，名称必须是 `你的用户名.github.io`。例如用户名为 `dazhuli-logic`，仓库名就是 `dazhuli-logic.github.io`。
2. 解压下载的 ZIP。不要只把 ZIP 文件上传到 GitHub；要上传解压后的网页文件。
3. 在仓库页面选择 **Add file → Upload files**，把本文件夹中的全部文件上传并提交。
4. 确认 `index.html`、`style.css` 和其他页面都直接位于仓库最上层，而不是藏在另一个子文件夹中。
5. 打开 **Settings → Pages**。
6. 在 **Build and deployment** 下，将 **Source** 设为 **Deploy from a branch**，分支选 `main`，文件夹选 `/(root)`，然后保存。
7. GitHub 完成发布后，网址是 `https://你的用户名.github.io/`。发布有时需要几分钟，GitHub 官方说明最长可能约 10 分钟。

### 方法二：普通项目仓库

也可以使用任意仓库名，例如 `academic-website`。发布设置相同，最终网址是：

`https://你的用户名.github.io/academic-website/`

## 发布前建议修改

1. 在全部 HTML 文件中替换职位、单位、邮箱、地址和日期。
2. 在 `index.html` 中更新个人简介与 News。
3. 将各内容页面中的示例条目替换为真实资料。
4. 把 Google Scholar、ORCID、论文 PDF、DOI 等文字改成真实链接。
5. 更新每页页脚中的 “Last updated”。

## 添加个人照片

把照片放到本文件夹，例如命名为 `profile.jpg`。然后在 `index.html` 中找到：

```html
<div class="portrait-placeholder" role="img" aria-label="Portrait placeholder with the initials DL">DL</div>
```

替换为：

```html
<img class="portrait" src="profile.jpg" alt="Portrait of Dazhu Li">
```

建议使用竖版照片，宽高比例约为 4:5，并先压缩到约 600–1000 像素宽。

## 添加 PDF 版 CV

把 PDF 放到本文件夹，例如命名为 `dazhu-li-cv.pdf`。然后在 `cv.html` 的说明文字下方加入：

```html
<p><a href="dazhu-li-cv.pdf">Download CV (PDF)</a></p>
```

## 本地查看

直接双击 `index.html` 即可浏览。上传前请依次点开顶部导航，确认七个页面都能正常打开。

## 官方说明

- [GitHub Pages 快速入门](https://docs.github.com/en/pages/quickstart)
- [创建 GitHub Pages 站点](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [配置发布来源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [向仓库添加文件](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
