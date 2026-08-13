GitHub Pages PWA版 モルック スコアボード

ルートに以下を配置:
index.html
manifest.json
sw.js
icons/icon-192.png
icons/icon-512.png
icons/apple-touch-icon.png

重要:
以前作ったホーム画面ショートカットは削除してください。
その後、Chromeで公開URLを直接開き、ページを再読み込みしてください。
Chromeメニューに「アプリをインストール」が出る場合はこちらを使用してください。
「ホーム画面に追加」しか出ない場合は、PWAとして認識されていないため、
Chromeのサイト情報/インストール状態を確認してください。

GitHub Pagesが https://ユーザー名.github.io/リポジトリ名/ の場合でも、
manifestのstart_urlとscopeは相対指定なので対応できます。
