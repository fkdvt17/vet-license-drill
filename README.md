# 獣医師国試ドリル v2.3.1 choice toggle / PWA

## 更新内容
- トップページ「すぐ始める」に、5択 / 2択を選択する大型ボタンを追加
- 選択中の出題形式をボタンの強調表示で確認可能
- 2択選択時は、2正答問題を除外
- 選択した形式を端末に保存し、次回起動時にも反映
- GitHub Pages公開用に PWA 関連ファイルを同梱

## GitHub Pagesで公開する場合
このフォルダ内のファイルを、リポジトリのrootにアップロードしてください。

必要な構成:

```
index.html
manifest.webmanifest
service-worker.js
icons/icon-192.png
icons/icon-512.png
```

その後、GitHubの `Settings → Pages` で以下を指定します。

- Source: Deploy from a branch
- Branch: main
- Folder: / root

公開URLをスマホで開き、iPhoneならSafariの共有ボタンから「ホーム画面に追加」できます。
