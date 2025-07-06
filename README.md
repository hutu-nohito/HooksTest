# ナレッジベース - GitHub Pages サイト

このリポジトリは、技術情報とTipsをまとめたナレッジベースサイトです。

## サイト構造

```
/
├── index.html              # ホームページ（リンク集）
├── home.html              # ホームページのコピー（バックアップ）
├── README.md              # このファイル
│
└── LLM/                   # メインカテゴリ: LLM関連
    └── ClaudeCode/        # サブカテゴリ: Claude Code
        └── claude_code_tips.html  # Claude Code Tips Collection
```

## サイト運用ルール

### 1. ディレクトリ構造

- **メインカテゴリ**: 最上位のディレクトリとして作成
  - 例: `LLM/`, `Programming/`, `Tools/` など
- **サブカテゴリ**: メインカテゴリ内に作成
  - 例: `LLM/ClaudeCode/`, `LLM/ChatGPT/` など
- **個別ページ**: サブカテゴリ内にHTMLファイルとして配置

### 2. ファイル命名規則

- HTMLファイル名は小文字とアンダースコアを使用
  - 良い例: `claude_code_tips.html`
  - 悪い例: `Claude-Code-Tips.html`
- 分かりやすく、内容を表す名前を付ける

### 3. 新しいページの追加手順

1. 適切なカテゴリ/サブカテゴリディレクトリを作成（必要な場合）
2. HTMLファイルを作成
3. `index.html`（ホームページ）にリンクを追加
4. GitHubにコミット＆プッシュ

### 4. ホームページの更新

- `index.html`がメインのリンク集として機能
- 新しいページを追加したら必ず`index.html`を更新
- カテゴリとサブカテゴリを明確に分類
- 各リンクには簡潔な説明を付ける

### 5. スタイルガイド

- 統一されたCSSスタイルを使用
- レスポンシブデザインを維持
- 読みやすさを重視したレイアウト

### 6. コミットメッセージ

- 日本語で分かりやすく記述
- 変更内容を明確に記載
- 例: "LLM/ClaudeCodeカテゴリにXXXページを追加"

## GitHub Pages設定

- **URL**: https://hutu-nohito.github.io/HooksTest/
- **ブランチ**: main
- **ルートディレクトリ**: /

## 更新履歴

- 2025-01-06: サイト構造の初期設定、Claude Code Tips Collectionページ追加