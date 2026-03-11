# GitHub Pages 发布包使用说明

这个发布包已经包含：

- `index.html`
- `robots.txt`
- `sitemap.xml`

## 你需要改的唯一关键信息

把下面这个占位网址统一替换成你自己的 GitHub Pages 地址：

`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/`

例如，如果你的 GitHub 用户名是 `abc`，仓库名是 `carbon-site`，那么就改成：

`https://abc.github.io/carbon-site/`

## 需要替换的位置

### 1）index.html
搜索并替换：
- canonical
- og:url
- JSON-LD 里的 `"url"`

### 2）robots.txt
把 Sitemap 地址改成你的真实地址。

### 3）sitemap.xml
把 `<loc>` 改成你的真实地址。

## GitHub Pages 发布步骤

1. 新建一个公开仓库
2. 把这 4 个文件上传到仓库根目录
3. 打开仓库 `Settings`
4. 点击 `Pages`
5. Source 选择 `Deploy from a branch`
6. Branch 选择 `main`，目录选 `/root`
7. 保存
8. 等待 GitHub 生成公开网址

## 上线后建议

上线后，把站点提交到：
- Google Search Console
- Bing Webmaster Tools
- 百度搜索资源平台

这样更有利于搜索引擎发现你的页面。
