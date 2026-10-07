# 呪われた地下迷宮 ～Gilded Catacomb～

Godot製3Dアクションゲームです。ブラウザ版とWindows 64ビット版を配布しています。

[ブラウザーで遊ぶ](https://norimashi.github.io/claude_soullike_sakuya/)

[Windows版をダウンロード](https://github.com/norimashi/claude_soullike_sakuya/releases/latest/download/claude_soullike_sakuya-windows.zip) / [リリース一覧](https://github.com/norimashi/claude_soullike_sakuya/releases)

PCブラウザーで開き、画面内の操作説明に従ってプレイしてください。初回はゲームデータのダウンロードと描画の準備に時間がかかります。

## Windows版

Godotのインストールは不要です。ダウンロードしたZIPを「すべて展開」で展開し、`claude_soullike_sakuya.exe`をダブルクリックしてください。`.exe`と`.pck`は同じフォルダーに置いてください。

操作説明とライセンスをZIPに同梱しています。ゲーム内のF1でも操作説明を表示できます。

## 公開構成

このリポジトリには、Web実行に必要な`index.*`の9ファイルと公開用の設定・説明ファイルを収録しています。書き出しはスレッド無効、GDExtensionなしです。

Windows版ZIPはGitHub Releasesに添付しています。ブラウザ版の画面右下からもダウンロードページを開けます。

GitHub Pagesの公開元は`main`ブランチの`/(root)`です。`.nojekyll`でJekyllによる変換を無効にし、`.gitattributes`で書き出しファイルの改行を保持します。

## 公式資料

- [GodotのWebエクスポート](https://docs.godotengine.org/en/stable/tutorials/export/exporting_for_web.html)
- [GitHub Pagesの公開元設定](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
