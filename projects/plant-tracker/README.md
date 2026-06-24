# Plant Tracker Portfolio Site

这是 Plant Tracker 项目的静态作品集网站，可以直接部署到 GitHub Pages。

## 文件结构

上传到 GitHub 仓库根目录后应该长这样：

```text
index.html
assets/
  home.webp
  login.webp
  register.webp
  my-plants.webp
  ...
README.md
```

## GitHub Pages 上传方式

1. 解压这个 ZIP
2. 打开解压后的 `plant_tracker_portfolio_site` 文件夹
3. 只上传里面的内容：
   - `index.html`
   - `assets` 文件夹
   - `README.md`
4. 不要把外层 `plant_tracker_portfolio_site` 文件夹整个传进去
5. 在 GitHub 仓库 Settings → Pages 里选择：
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root

## 注意

这个网站是静态作品集展示页，适合 GitHub Pages。
原本的 Flask 后端项目不能直接跑在 GitHub Pages 上；如果要部署真实可运行的 Flask App，需要用 Render、Railway、PythonAnywhere 等支持后端的平台。
