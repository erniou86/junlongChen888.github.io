
# 大乐透摇号器（GitHub Pages 部署包 · junlongChen888）

**你的公开链接将是：**
- 项目页：`https://junlongChen888.github.io/<仓库名>/`（仓库任意名字，例如 `dlt-shaker`）
- 用户主站：`https://junlongChen888.github.io/`（如果仓库名为 `junlongChen888.github.io`）

## 上线步骤（从分支发布）
1. 在 GitHub 新建 *Public* 仓库（例如 `dlt-shaker`）。
2. 上传本包所有文件到仓库根目录（确保 `index.html` 在根目录）。
3. 打开 **Settings → Pages**：在 **Build and deployment** 的 **Source** 选择 **Deploy from a branch**，分支选 `main`，文件夹选 `/`；保存。
4. 等待几秒，系统会生成公开网址。

## 上线步骤（GitHub Actions 自动发布）
1. 上传本包所有文件（包含 `.github/workflows/deploy.yml`）。
2. 在 **Settings → Pages** 把 **Source** 改为 **GitHub Actions**。
3. 推送到 `main` 后，Actions 会自动部署；完成后看到公开链接。

> 参考：GitHub Pages 官方文档（发布源/Actions/自定义域名）。

## 自定义域名（可选）
- `example.com`：在 DNS 添加 A 记录到 GitHub Pages IP；`www.example.com`：CNAME 到 `junlongChen888.github.io.`；然后在 **Settings → Pages → Custom domain** 填写域名，并启用 HTTPS。

