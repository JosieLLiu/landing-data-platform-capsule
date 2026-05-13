# landing-data-platform-capsule
这个目录已经是可直接部署到 GitHub Pages 的静态站版本。

## 目录内容

- `index.html`：站点入口文件

## 上传到 GitHub Pages

请将以下文件一起上传到仓库根目录：

- `index.html`
- `ws_logo.png`

如果后续只修改页面内容，通常更新 `index.html` 即可；如果更换公司 logo，也需要同步更新 `ws_logo.png`。

## GitHub Pages 最短路径

1. 新建一个 GitHub 仓库
2. 把这个目录里的文件上传到仓库根目录
3. 打开仓库的 `Settings`
4. 进入 `Pages`
5. 在 `Build and deployment` 里选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
6. 保存后等待 GitHub 生成公开链接

## 链接格式

通常会是下面两种之一：

- `https://<你的用户名>.github.io/<仓库名>/`
- 如果是用户主页仓库：`https://<你的用户名>.github.io/`

## 注意

- 首次发布通常需要等待几分钟
- 如果页面没更新，刷新或等待 1 到 5 分钟再试
- 这个页面依赖外部 Google Fonts，所以公开访问时需要能访问 Google Fonts
