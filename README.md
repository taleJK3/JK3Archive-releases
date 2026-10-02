# JK3Archive

[English](#english) | [日本語](#日本語)

## English

A Windows tool for batch-converting images inside folders and ZIP / RAR / CBZ / CBR archives to WebP, JPEG XL (JXL), or AVIF.

Archives are rebuilt with the converted images inside. Images can also be resized.
Processing runs locally on your PC; images are not uploaded anywhere.
The interface supports English and Japanese.

JXL and AVIF are experimental features.

### Download

**[Download from Releases](https://github.com/taleJK3/JK3Archive-releases/releases)**

Under “Assets”, choose:

- **The ZIP ending in `win-x64.zip`** — the application. This is the only ZIP needed for normal use.
- **The ZIP ending in `ThirdPartySources.zip`** — third-party library sources and build materials. Not needed to run the app.
- GitHub’s automatically generated “Source code” downloads do not contain the application.

### Requirements and usage

- Windows 10 / 11 (x64)
- [.NET 10 Desktop Runtime for Windows x64](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)

Extract the entire application ZIP and launch `JK3Archive.exe`.
Review your settings, click “Save Settings”, then drag folders or supported archives onto the settings window.

You can also register JK3Archive in the Windows “Send to” menu from the settings window.
Individual image files cannot be passed directly.

### Before you start

- Defaults: WebP, quality 80, maximum long edge of 1920 px. Image quality and dimensions may change. Try copies of your data first.
- **With backups disabled, originals replaced during processing are deleted without using the Recycle Bin.**
- Archive and folder backups have separate settings. Folder backups are **off by default**; enable them if you want to keep the original images.
- Password-protected archives, split RAR archives, and 7z are not supported.

See the included `README_EN.txt` for detailed instructions and terms of use.

This repository is for distribution and documentation. The application’s source code is not published here.
Third-party license information is included in `ThirdPartyLicenses.txt` and the accompanying license files.

## 日本語

フォルダーやZIP・RAR・CBZ・CBRの中の画像を、WebP・JPEG XL（JXL）・AVIFへ一括変換するWindows用ツールです。

書庫は中の画像を変換して、書庫として作り直します。画像の縮小にも対応しています。
画像処理はPC内で完結し、画像を外部へ送信しません。
画面は日本語・英語に対応しています。

JXL・AVIFは実験機能です。

### ダウンロード

**[Releasesからダウンロード](https://github.com/taleJK3/JK3Archive-releases/releases)**

「Assets」から、必要なZIPを選んでください。

- **`win-x64.zip`で終わるファイル**：アプリ本体です。通常はこちらだけで使えます。
- **`ThirdPartySources.zip`で終わるファイル**：使用ライブラリのソースコード等です。通常の利用には不要です。
- GitHubが自動表示する「Source code」はアプリ本体ではありません。

### 動作環境・使い方

- Windows 10／11（x64）
- [.NET 10 Desktop Runtime（Windows x64）](https://dotnet.microsoft.com/ja-jp/download/dotnet/10.0)

本体ZIPをすべて展開し、`JK3Archive.exe`を起動します。
設定を確認して「設定を保存」を押し、フォルダーや対応する書庫を設定画面へドラッグ＆ドロップしてください。

設定画面で「送る」メニューに登録すると、右クリックからも変換できます。
画像ファイル単体の直接指定には対応していません。

### 使用前の注意

- 初期設定はWebP・品質80・長辺1920pxです。画質や画像サイズが変わるため、まずコピーしたデータでお試しください。
- **バックアップがOFFの場合、処理で置き換えた元の画像・書庫をゴミ箱を経由せず削除します。**
- 書庫用とフォルダー用のバックアップ設定は別です。フォルダー用は**初期設定でOFF**なので、原本を残す場合はONにしてください。
- パスワード付き書庫、分割RAR、7zには対応していません。

詳しい使い方・利用条件は、同梱の `README_JP.txt` を参照してください。

このリポジトリは配布・案内用です。アプリ本体のソースコードは公開していません。
第三者コンポーネントのライセンスは `ThirdPartyLicenses.txt` および各ライセンス文書を参照してください。

---

Author / 作者：= tale(JK, 3)

- [Website / 公式サイト](https://talejk3.com/)
- [BOOTH — Free download & optional support / 無料版・開発応援版](https://talejk3.booth.pm/items/8927867)
