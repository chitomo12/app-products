# TrainSpeech プライバシーポリシー・利用規約

このリポジトリは、iOSアプリ「フランス語会話練習 Macha (TrainSpeech)」のプライバシーポリシーおよび利用規約を公開するための静的Webサイトです。

## 公開URL

GitHub Pagesで公開されています：

```
https://[your-username].github.io/[repository-name]/
```

## ファイル構成

```
site/
├── index.html      # プライバシーポリシー・利用規約ページ
├── styles.css      # スタイルシート（iOS風デザイン）
└── README.md       # このファイル
```

## セットアップ手順

### 1. 新しいリポジトリを作成

GitHubで新しいリポジトリを作成します（例: `trainspeech-privacy-policy`）

### 2. ファイルをコミット・プッシュ

```bash
cd site
git init
git add .
git commit -m "Initial commit: Privacy policy and terms of service"
git remote add origin https://github.com/[your-username]/[repository-name].git
git branch -M main
git push -u origin main
```

### 3. GitHub Pagesを有効化

1. GitHubリポジトリページで「Settings」タブを開く
2. 左メニューから「Pages」を選択
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で `main` ブランチと `/root` を選択
5. 「Save」をクリック

数分後、公開URLにアクセスできるようになります。

## カスタマイズ方法

### 連絡先メールアドレスの更新

`index.html` の以下の部分を更新してください：

```html
<p class="contact-email">
    Email: <a href="mailto:your-email@example.com">your-email@example.com</a>
</p>
```

### アプリ情報の更新

必要に応じて以下の情報を更新してください：

- アプリバージョン
- リリース日
- 開発者情報
- 最終更新日

### デザインのカスタマイズ

`styles.css` を編集することで、デザインをカスタマイズできます。

ヘッダーのグラデーションカラーは以下の部分で変更可能：

```css
header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## App Store審査用

App Store Connectでアプリを申請する際、以下のURLを入力してください：

- **プライバシーポリシーURL**: `https://[your-username].github.io/[repository-name]/`
- **利用規約URL**: `https://[your-username].github.io/[repository-name]/#terms`

## ライセンス

このWebサイトのコンテンツは、TrainSpeechアプリの開発者に帰属します。

## 更新履歴

- 2025-12-31: 初版作成
# chitomo-apps
