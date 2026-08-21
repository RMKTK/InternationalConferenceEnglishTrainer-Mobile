International Conference English Trainer v0.12
GitHub Pages / Smartphone版
===============================================

このZIPは、GitHub Pagesにそのまま置きやすいよう、
index.html をリポジトリ直下にした版です。

■ GitHub Pages公開
1. GitHubで新しいリポジトリを作成
   例: conference-english-trainer

2. このZIPを展開し、中のファイルをすべてリポジトリ直下へアップロード
   index.html
   app.css
   app.js
   manifest.webmanifest
   sw.js
   icon-192.png
   icon-512.png
   apple-touch-icon.png
   materials/

3. GitHub
   Settings
   → Pages
   → Build and deployment
   → Source: Deploy from a branch
   → Branch: main
   → Folder: /(root)
   → Save

4. 数分後に表示される
   https://<GitHubユーザー名>.github.io/<リポジトリ名>/
   をスマートフォンで開く

■ iPhone
Safariで開く
→ 共有ボタン
→「ホーム画面に追加」
→「追加」

■ Android
Chromeで開く
→ 右上メニュー
→「ホーム画面に追加」または「アプリをインストール」

■ オフライン
初回はインターネット接続が必要です。
一度正常に読み込むと、Service Workerがアプリ本体と教材をキャッシュするため、
その後は基本画面・教材をオフラインでも利用できます。

※ 音声読み上げ（Web Speech API）は、端末・ブラウザ・インストール済み音声によって
   オフライン時の動作が異なる場合があります。

■ 更新方法
1. 新しい版のファイルでGitHub上のファイルを置き換える
2. commit
3. GitHub Pagesの再デプロイを待つ
4. スマホ側で更新されない場合は、Safari/Chromeを一度閉じて再度開く
   必要に応じてサイトデータ/キャッシュを削除

お気に入りは端末のlocalStorageに保存されます。
同じスマホ・同じブラウザで使う限り、通常は保持されます。
