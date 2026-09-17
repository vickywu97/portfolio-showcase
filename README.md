# Vicky Wu · AI 法律合规产品作品集（展示站）

静态作品集展示页，部署在 GitHub Pages。内容串联三件生产力型合规工具与作品集主入口。

- 在线地址：`https://vickywu97.github.io/portfolio-showcase/`（启用 Pages 后生效）
- 主仓库（作品集入口）：<https://github.com/vickywu97/vickywu97>

## 内容

- 双支柱定位：法律 AI 可靠性基准（评测）/ 生产力型合规工具（求职三件套）
- 三件套：`oss-license-checker` · `privacy-policy-checker` · `token-classifier`
- 可复制作品集文案（中英文一句话定位 + LinkedIn / 脉脉段落）
- 工程与合规姿态 + 诚实声明

## 本地预览

```bash
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000/
```

## 部署（GitHub Pages）

本仓库已配置 `.github/workflows/pages.yml`：每次 push 到 `main` 自动构建并发布到 `gh-pages` 分支。

首次启用（仓库网页一次设置）：

1. 仓库 **Settings → Pages → Build and deployment → Source** 选择 **Deploy from a branch**
2. **Branch** 选择 `gh-pages` / `(root)`，保存
3. 此后每次 `git push origin main` 即自动部署

## 合规说明

- 全部仓库开源 MIT，离线优先、零依赖 Python。
- 系统研习 GDPR 与欧盟数据保护框架（含 IAPP CIPP/E 知识体系），但未持有 CIPP/E 等国际隐私认证。
- 从业时长统一表述为「六年法律实务经验」。

© Vicky Wu (vickywu97) · MIT
