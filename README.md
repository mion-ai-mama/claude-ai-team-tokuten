# Claudeで「AIチーム」を作るはじめてガイド

Instagramリールの無料特典ページ（静的サイト）。Claude Codeで、リサーチ→分析→台本の3人のAIチームを作る方法を、コピペのプロンプトで解説します。

## 確認のしかた

```bash
cd claude-ai-team-tokuten
python3 -m http.server 8765
# http://localhost:8765/ を開く
```

## 編集のしかた

| 変えたいこと | 場所 |
|---|---|
| 文章・プロンプト | `index.html`（単一の源） |
| LINE登録URL | `script.js` 先頭の `LINE_URL` |
| 色 | `style.css` の `:root` |
| 部品の見た目 | `components.css` |

プロンプトを変えたときは、`docs/requirements.md` §4 の手順で、実際に動かして再確認してください。
