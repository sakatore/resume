# 職務経歴書 - GitHub Pages

このリポジトリは、職務経歴書をGitHub Pagesで公開するためのプロジェクトです。

## 📋 概要

- モダンでレスポンシブなデザイン
- GitHub Pagesでの自動デプロイ
- 印刷対応
- モバイルフレンドリー

## 🚀 セットアップ手順

### 1. リポジトリのクローン
```bash
git clone https://github.com/yourusername/resume.git
cd resume
```

### 2. 個人情報の編集
`index.html`ファイルを開いて、以下の項目を自分の情報に変更してください：

- 名前
- 生年月日
- 連絡先（メールアドレス）
- GitHubユーザー名
- 職務経歴
- 技術スキル
- 学歴
- 資格

### 3. GitHub Pagesの有効化

1. GitHubリポジトリのページに移動
2. Settings → Pages を選択
3. Source で "GitHub Actions" を選択

### 4. デプロイ

mainブランチにプッシュすると、自動的にGitHub Pagesにデプロイされます：

```bash
git add .
git commit -m "Update resume"
git push origin main
```

## 📁 ファイル構成

```
resume/
├── index.html          # メインのHTMLファイル
├── styles.css          # CSSスタイル
├── .github/workflows/  # GitHub Actions設定
│   └── deploy.yml
└── README.md          # このファイル
```

## 🎨 カスタマイズ

### 色の変更
`styles.css`ファイル内の以下の変数を変更することで、色をカスタマイズできます：

- メインカラー: `#667eea`
- アクセントカラー: `#764ba2`

### レイアウトの変更
HTMLの構造を変更することで、セクションの追加・削除・並び替えが可能です。

## 📱 対応ブラウザ

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 📄 印刷対応

ブラウザの印刷機能を使用することで、PDFとして保存できます。

## 🤝 貢献

プルリクエストやイシューの報告を歓迎します。

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。

---

**注意**: 個人情報を含むため、公開前に必ず個人情報を適切に編集してください。
