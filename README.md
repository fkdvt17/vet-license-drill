# 獣医師国試ドリル v2.3 PWA

## 配布方法
このフォルダ一式を GitHub Pages / Netlify / 大学サーバーなど、HTTPSで公開できる場所にアップロードしてください。

## 起動ファイル
- `index.html`

## PWA構成
- `manifest.webmanifest`: ホーム画面追加用のアプリ情報
- `service-worker.js`: オフラインキャッシュ用
- `icons/`: スマホホーム画面用アイコン

## 注意
- PWAのService Workerは、通常 `file://` でHTMLを直接開いた場合は登録されません。
- HTTPSで公開すると有効になります。GitHub PagesはHTTPS対応なので適しています。
- 成績データは端末・ブラウザ内のlocalStorageに保存されます。URLやドメインを変えると別データ扱いになります。
