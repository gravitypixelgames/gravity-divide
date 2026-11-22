# GRAVITY. — DIVIDE | GitHub Pages 公開手順

## 重要：公開前に2か所を編集

1. `privacy.html` の **運営者名／Operator** と **メール／Email** を実在する公開可能な内容へ置き換えます。
2. `support.html` の問い合わせ用メールを同じメールアドレスへ置き換えます。

> 個人メールを公開したくない場合、別のサポート用メールを作成してください。架空アドレスやプレースホルダーのまま公開しないでください。

## 公開（GitHub Pages）

1. https://github.com/ にサインイン（アカウントがなければ作成）
2. **New repository** を選び、リポジトリ名 `gravity-divide`、公開設定 **Public** で作成
3. このフォルダの中身（ZIP自体ではなく、`index.html`, `support.html`, `privacy.html`, `style.css`, `site.js`, `artwork.png`, `.nojekyll`）をリポジトリのルートにアップロードして Commit
4. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**
5. 公開後、ブラウザで2つのページを確認

想定URL（ユーザー名が決まるまでは仮の形式）:
- `https://YOUR_GITHUB_USERNAME.github.io/gravity-divide/privacy.html`
- `https://YOUR_GITHUB_USERNAME.github.io/gravity-divide/support.html`

実際にアクセスできたURLだけをApp Store Connectに登録してください。

## App Store Connect
- **アプリのプライバシー → プライバシーポリシーURL**: 上記 `privacy.html` の公開URL
- **iOSアプリ バージョン1.0 → サポートURL**: 上記 `support.html` の公開URL
- 日本語・英語双方の登録情報でも実際の公開URLを利用できます。ページ内で言語切り替え可能です。

## 注意
- 本サイトは公開前草案です。AdMob / Google UMP と Apple StoreKit を利用する採用版Ver03のコードを基に作成しましたが、最終ビルドのSDK・同意・広告配信の実態と突き合わせてください。
- Appleの「アプリのプライバシー」のデータ取扱い回答は本ページ作成だけでは完了しません。
- iPhoneアプリ本体からこの公開ページへアクセスできるリンクも追加してください。
