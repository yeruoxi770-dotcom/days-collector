# 日子收藏家

私人电子手账：打开日记本、编辑文字、添加图片和贴纸，并在浏览器本地保存。

## 网站

https://yeruoxi770-dotcom.github.io/days-collector/

## 发布与更新

- `github-pages-site.zip` 保存完整静态网站的 HTML、JavaScript、CSS、图片和字体。
- `.github/workflows/deploy-pages.yml` 自动解压并发布至 GitHub Pages。
- 上传新的同名部署包到 main 分支会触发更新；也可在 Actions 中手动运行。
- Pages 来源设置为 GitHub Actions；部署包内的资源路径使用 `/days-collector/assets/`。
- 当前仓库存放可直接发布的构建产物，不包含原始开发工程。

## 数据

日记保存在访问者自己的浏览器（IndexedDB/localStorage），不会上传至此仓库，不提供账号登录或跨设备同步。更换浏览器或网址前，请使用页面的备份功能导出数据。
