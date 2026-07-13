# CostCue 安装说明 / Installation / インストール

CostCue 目前采用免费社区分发。应用经过正式 Release 构建、App Sandbox、Hardened Runtime 和临时代码签名；由于尚未使用 Apple Developer Program，当前安装包没有 Developer ID 与 Apple 公证票据。

CostCue is currently distributed as a free community build. It uses a Release build, App Sandbox, Hardened Runtime, and ad hoc code signing. This package does not yet include a Developer ID signature or Apple notarization.

CostCue は現在、無料のコミュニティビルドとして配布されています。Release ビルド、App Sandbox、Hardened Runtime、アドホック署名を使用しています。Developer ID 署名と Apple の公証はまだ含まれていません。

## 中文

1. 打开下载的 `CostCue-*-community.dmg`，将 `CostCue.app` 拖入 `Applications`。
2. 在“应用程序”中双击 CostCue。
3. 首次打开若被拦截，请关闭提示，进入“系统设置”→“隐私与安全性”，找到 CostCue 后点击“仍要打开”。
4. 只从 CostCue 官方 GitHub Release 下载，并核对发布页的 SHA-256。

数据和自定义图标保存在：

```text
~/Library/Containers/com.lqc.CostCue/Data/Library/Application Support/
```

卸载或清理前，请先在 CostCue 设置中导出 `.costcue.json` 备份。

## English

1. Open the downloaded `CostCue-*-community.dmg`, then drag `CostCue.app` into `Applications`.
2. Double-click CostCue in the Applications folder.
3. If macOS blocks the first launch, close the message, open System Settings → Privacy & Security, find CostCue, and click Open Anyway.
4. Download only from the official CostCue GitHub Release and verify the published SHA-256 checksum.

Subscriptions and custom icons are stored at:

```text
~/Library/Containers/com.lqc.CostCue/Data/Library/Application Support/
```

Before uninstalling or clearing data, export a `.costcue.json` backup from CostCue Settings.

## 日本語

1. ダウンロードした `CostCue-*-community.dmg` を開き、`CostCue.app` を `Applications` にドラッグします。
2. 「アプリケーション」フォルダで CostCue をダブルクリックします。
3. 初回起動がブロックされた場合は、警告を閉じて「システム設定」→「プライバシーとセキュリティ」を開き、CostCue の「このまま開く」をクリックします。
4. CostCue 公式 GitHub Release からのみダウンロードし、公開されている SHA-256 を確認してください。

サブスクリプションとカスタムアイコンの保存先：

```text
~/Library/Containers/com.lqc.CostCue/Data/Library/Application Support/
```

アンインストールやデータ消去の前に、CostCue の設定から `.costcue.json` バックアップを書き出してください。
