# 呪われた地下迷宮 ～Gilded Catacomb～

Godot製3Dアクションゲームです。ブラウザ版とWindows 64ビット版を配布しています。

[ブラウザーで遊ぶ](https://norimashi.github.io/claude_soullike_sakuya/)

[Windows版をダウンロード](https://github.com/norimashi/claude_soullike_sakuya/releases/latest/download/claude_soullike_sakuya-windows.zip) / [リリース一覧](https://github.com/norimashi/claude_soullike_sakuya/releases)

ブラウザーで開き、画面内の操作説明に従ってプレイしてください。PCではキーボードとマウス、スマートフォン・タブレットでは横向きのタッチ操作に対応しています。初回はゲームデータのダウンロードと描画の準備に時間がかかります。

ブラウザ版は日本語・英語を切り替えられます。PCではポーズ中にF3で言語、F2で画質を切り替えられます。読み込み時に指定する場合は、URLの末尾に`?lang=en`や`?q=low`を付けてください。

## Windows版

！注意！
現在、Windows版はトロイの木馬として判定されるケースがあります。
誤判定かとは思いますが、不安な方はこちらではなくブラウザーでのプレイをお勧めします。

Godotのインストールは不要です。ダウンロードしたZIPを「すべて展開」で展開し、`claude_soullike_sakuya.exe`をダブルクリックしてください。`.exe`と`.pck`は同じフォルダーに置いてください。

操作説明とライセンスをZIPに同梱しています。ゲーム内のF1でも操作説明を表示できます。

## 公開構成

このリポジトリには、Web実行に必要な`index.*`の9ファイルと公開用の設定・説明ファイルを収録しています。書き出しはスレッド無効、GDExtensionなしです。

Windows版ZIPはGitHub Releasesに添付しています。マウスで操作するブラウザでは画面右下からもダウンロードページを開けます。

GitHub Pagesの公開元は`main`ブランチの`/(root)`です。`.nojekyll`でJekyllによる変換を無効にし、`.gitattributes`で書き出しファイルの改行を保持します。

## 公式資料

- [GodotのWebエクスポート](https://docs.godotengine.org/en/stable/tutorials/export/exporting_for_web.html)
- [GitHub Pagesの公開元設定](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
