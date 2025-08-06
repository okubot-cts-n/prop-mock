# CTS モック一覧

このリポジトリは、CTS（コミュニケーショントレーニングサポート）で開発中のプロトタイプとモックアップをGitHub Pagesで公開するためのものです。

## 📋 モック一覧

### 🎯 英語学習ナビゲーション
- **ファイル**: `english_learning_navigation.html`
- **説明**: 3つの質問で最適な英語学習サービスを診断・提案するインタラクティブなナビゲーションシステム
- **特徴**: 
  - ユーザーの英語レベル診断
  - パーソナライズされた学習プラン提案
  - 複数の英語学習サービスとの連携
  - レスポンシブデザイン

## 🚀 アクセス方法

GitHub Pagesで公開されているため、以下のURLでアクセスできます：

**メインページ**: https://okubot-cts-n.github.io/prop-mock/

**英語学習ナビゲーション**: https://okubot-cts-n.github.io/prop-mock/english_learning_navigation.html

## 🛠️ 技術仕様

- **フロントエンド**: HTML5, CSS3, JavaScript (Vanilla)
- **デザイン**: レスポンシブデザイン対応
- **ブラウザ対応**: モダンブラウザ（Chrome, Firefox, Safari, Edge）

## 🔗 iframe での使用について

### ⚠️ GitHub Pages の制限
GitHub Pagesはセキュリティヘッダー（X-Frame-Options: DENY）により、iframeでの表示が制限される可能性があります。

### ✅ 推奨解決策

#### 1. Netlify でのホスト（推奨）
```bash
# 1. GitHubリポジトリをNetlifyに接続
# 2. netlify.tomlファイルでヘッダー設定
# 3. 自動的にiframe表示が可能になる
```

#### 2. iframe 埋め込みコード例
```html
<iframe 
    src="https://your-netlify-url.netlify.app/english_learning_navigation.html"
    title="英語学習ナビゲーション"
    width="100%"
    height="800px"
    allowfullscreen>
    お使いのブラウザはiframeをサポートしていません。
</iframe>
```

#### 3. レスポンシブ対応CSS
```css
.iframe-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 100%;
    overflow: hidden;
}

.iframe-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: none;
}
```

## 📝 開発メモ

- このリポジトリは単発案件のモックをGitHub Pagesで見れるように作成されています
- 新しいモックを追加する際は、`index.html`のモックリストに追加してください
- 各モックは独立したHTMLファイルとして管理されています

## 🔄 更新履歴

- **2025-01-08**: 初回コミット - 英語学習ナビゲーションの追加

## 📞 お問い合わせ

CTS（コミュニケーショントレーニングサポート）までお問い合わせください。

---

© 2025 CTS. All rights reserved. 