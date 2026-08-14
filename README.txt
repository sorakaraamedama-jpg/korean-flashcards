韓国語フラッシュカード PWA版
==============================

収録語数: 910語

対応:
- iPhoneホーム画面からアプリ風に起動
- standalone（SafariのタブUIを出さない）
- オフラインキャッシュ
- 単語・例文の韓国語読み上げ
- 日本語訳 / カタカナ読み / 例文 / 例文訳 / メモ
- お気に入り
- 正解 / もう一度 の学習記録
- 4級 / 5級絞り込み
- シャッフル

重要:
PWAとしてインストール・オフライン利用するには、これらのファイルをHTTPSで配信する必要があります。
単なる「ファイルをiPhoneにコピー」だけではService Workerは動作しません。

保存データ:
学習回数、お気に入り、メモなどはiPhoneのWebアプリ領域（localStorage）に保存されます。
サーバーへ学習データを送る処理はありません。

ファイル:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png
- korean_flashcards_complete_910.json（元データ）
