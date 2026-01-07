
# 大乐透摇号器（GitHub Pages 部署包）

两种部署方式：

1. **从分支发布**（Settings → Pages → Build and deployment → Source: *Deploy from a branch*，选择 `main` 与 `/`）
2. **GitHub Actions 自动发布**（将 Pages 的 Source 选择为 *GitHub Actions*，本仓库已提供 `.github/workflows/deploy.yml`）

> 注意：Pages 站点是公开访问的；自定义域名可在 *Settings → Pages → Custom domain* 设置，并在 DNS 里配置 A / CNAME 记录。详见 GitHub Docs。

