# 游戏设计与策划分析

个人游戏设计研究与拆解文章的 GitHub Pages 仓库。

## 当前文章

《绝区零》「迷宫诡域：贝果计划」搜打撤玩法拆解。

- `drafts/贝果计划_排版定稿.md`：与网站正文同步的 Markdown 稿。
- `index.html` 与 `assets/`：静态网页及配套图片。
- `.nojekyll`：让 GitHub Pages 直接发布这些静态文件。

## 本地验收

在仓库根目录运行 `python -m http.server 8000`，打开 <http://localhost:8000/>。检查文章目录与顶部导航能跳到对应章节，所有插图正常显示，点击图片能打开原图；再用窄屏或手机检查目录与正文。

## GitHub Pages 发布

推送 `main` 后，在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch → main → /(root)** 并保存。静态网页位于根目录，无需构建流程。发布状态可在仓库 **Actions** 的 Pages 部署记录中查看。

站点发布地址预计为：<https://nightstreetccia-creator.github.io/game-design-blog/>。

> 仓库文件就绪与网站已经上线是两件事；以上链接须在 Pages 部署成功后验收。

## 内容来源

当前网站正文、配图顺序和图注按用户的最终版拆解案同步；网页中的黄色标记用于提示关键判断。
