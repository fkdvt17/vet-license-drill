# 獣医師国試ドリル v2.3.2 text fix / PWA

## 更新内容
- 75回NのビタミンB1表記を `B₁` に修正
- HTML内のLaTeX風表記をスマホ表示向けの通常文字に修正
  - `G₁`, `G₂`
  - `Na⁺`, `K⁺`, `Ca²⁺`, `Cl⁻`, `HCO₃⁻`
  - `B₁`, `CH₄`, `N₂O`, `SF₆`
- v2.3.1 の5択 / 2択すぐ選択機能とPWA構成は維持

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

公開済みのPWAを更新した場合、Service Workerのキャッシュが残ることがあります。
表示が古い場合は、ブラウザで再読み込みするか、ホーム画面アイコンを一度削除して追加し直してください。
