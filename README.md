# Wei Guo · 郭伟 — Academic Homepage

Wei Guo 的中英文学术主页，使用纯 HTML、CSS 和 JavaScript 构建，可直接部署至 GitHub Pages。

- Homepage: https://guowei1314.github.io/
- GitHub: https://github.com/guowei1314
- Current status: Ph.D. Student
- Current institution: Nanjing University of Science and Technology
- Previous institution: Southwest University
- Research interests: Multi-view Clustering, Incomplete and Unaligned Multi-view Learning, Multi-omics Cancer Subtyping, Tensor Learning

## 本地预览

在仓库根目录运行：

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

然后访问 http://127.0.0.1:8000/ 。

## 文件结构

- `index.html`：主页内容及 SEO / Open Graph 信息；中英文内容分别使用 `lang="en"` 和 `lang="zh-CN"` 标记。
- `styles.css`：桌面端、移动端、打印以及深浅主题样式。
- `site.js`：中英文切换、主题记忆、论文筛选、图片预览和页脚年份。
- `assets/portrait-white.png`：主页头像。
- `assets/institutions/`：教育经历使用的学校标识。
- `projects/`：保留的独立项目页面及其资源，不随主页身份信息修改。

## 维护说明

主页保留现有布局、响应式设计、中英文切换和深色模式。更新身份信息时，应同步检查页面标题、SEO / Open Graph、个人简介、Education、页脚以及本 README。

仓库根目录是 GitHub Pages 发布目录；`.nojekyll` 使 GitHub Pages 直接发布静态文件，无需运行 Jekyll 或其他构建步骤。
