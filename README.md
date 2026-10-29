# Chouaibou Toure - 自己紹介サイト

HTMLとCSSだけで作った、シンプルな自己紹介サイトです。

## ファイル

- `index.html`：ページの内容
- `style.css`：レイアウト、配色、レスポンシブデザイン
- `images/profile.jpg`：プロフィール欄に使うマリのホンボリ山の写真
- `images/festival-segou.jpg`：セグーの「Festival sur le Niger」の写真
- `images/mount-fuji.jpg`：背景に使う富士山の写真

富士山の背景写真はCC0です。ホンボリ山の写真はCC BY 2.0、祭りの写真はCC BY-SA 4.0のライセンスです。ページ内に作者名と出典へのリンクを記載しています。写真を再利用する場合は、クレジットとライセンス表記を残してください。

GitHubへのリンクは `https://github.com/ToureTank` に設定されています。

ページ上部のボタンで日本語・フランス語・英語を切り替えられます。隣のスイッチでライトモードとダークモードを切り替えます。どちらもJavaScriptを使わずに動作します。再読み込みすると日本語・ライトモードに戻ります。

## ローカルで確認する

1. 3枚の写真はすでに `images` フォルダーにあります。
2. `index.html` をブラウザーで直接開くか、このフォルダーで `python3 -m http.server 8000` を実行します。
3. サーバーを起動した場合は `http://localhost:8000` を開きます。終了するときは `Ctrl+C` を押します。
4. ブラウザーの幅を狭めるか、スマートフォンで開いて表示を確認します。

## GitHub Pagesで公開する

1. GitHubのリポジトリで **Settings** を開き、**Pages** を選びます。
2. **Build and deployment** の **Deploy from a branch** を選択します。
3. ブランチに `main`、フォルダーに `/(root)` を選び、**Save** を押します。
4. デプロイが完了すると、Pagesの設定画面に公開URLが表示されます。このサイトのURLは `https://touretank.github.io/introductofID/` です。

ページや画像がすぐに表示されない場合は、少し待ってから公開URLを再読み込みしてください。GitHub Pagesは静的ファイルを配信するため、フレームワークやビルド手順は不要です。