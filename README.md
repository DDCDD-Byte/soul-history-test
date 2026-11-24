# 历史人物趣味测试

## 目录

- `site/`：可部署的静态网页（index.html、40题题库、7类结果）
- `发布素材/`：7张1080×1440结果卡、笔记标题/正文模板、商品详情文案
- `_result_cards.py`：结果卡生成脚本

## 本地预览

需要通过 HTTP 提供 JSON 资源，不能直接双击 `site/index.html`（浏览器会拦截 `fetch`）。在 `site/` 目录启动静态服务器，例如：

```bash
python -m http.server 8801
```

访问 `http://127.0.0.1:8801/`。

## GitHub Pages

- 仓库：<https://github.com/DDCDD-Byte/soul-history-test>
- 公网测试链接：<https://ddcdd-byte.github.io/soul-history-test/>
- Pages 从 `main` 分支根目录发布。
- 分享按钮调用系统分享面板；不支持时复制结果文案与当前链接。
- 已验证公网首页、40 题答题、结果展示、再测回到第 1 题；国内手机流量与微信内置浏览器仍需人工实测。

趣味测试，非专业心理诊断。
