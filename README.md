# 八五文化传媒 · 短视频服务展示页

商户短视频拍摄 & 新媒体代运营 商务展示页（GitHub Pages 部署版）

## 部署步骤（约 2 分钟）

### 1. 在 GitHub 新建仓库
- 登录 github.com → 右上角 `+` → `New repository`
- 仓库名填写：`85film`（或任意名字）
- 勾选 **Public** → Create

### 2. 上传本文件夹内容
网页方式（最简单）：
- 进入仓库 → `uploading an existing file` → 把 index.html 拖进去
- 再进入 `videos` 文件夹 → 上传你的 mp4 视频（按 videos/视频放置说明.md 里的编号命名）

命令行方式：
```bash
cd 85film-site
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin https://github.com/你的用户名/85film.git
git push -u origin main
```

### 3. 开启 GitHub Pages
- 仓库 → **Settings** → 左侧 **Pages**
- Source 选择 **Deploy from a branch** → Branch 选 `main` / `(root)` → Save
- 等 1~2 分钟，访问：`https://你的用户名.github.io/85film/`

## 换视频 / 改文字
- 替换视频：直接把 videos/ 里的 mp4 同名覆盖，重新 push 即可
- 改文字价格：直接改 index.html 里的文字，push 后自动更新
