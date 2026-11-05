# pagesmock

GitHub Pages で Markdown の設計書がどう見えるかを確認するためのダミーサイトです。設計書は架空の画面（図書検索）で、実在する内容は含みません。

## Pages の有効化

1. Settings → Pages → Build and deployment → Source: Deploy from a branch
2. Branch: `main` / `/ (root)` → Save
3. 1〜2 分後に表示される URL を開く

## 構成

- `index.md` … 一覧（トップ）
- `docs/DEMO-001_図書検索サンプル/設計書.md` … 標準の見え方（テーマなし）
- `docs/DEMO-001_図書検索サンプル/設計書_調整版.md` … 表の横スクロールと Mermaid を効かせた見え方
- `_layouts/review.html` … 調整版のレイアウト
- `assets/` … 同梱の CSS と mermaid.min.js（外部 CDN に依存しない）
# github-pages-mock
