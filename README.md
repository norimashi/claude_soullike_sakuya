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

## 更新

1. GodotでWeb版を再エクスポートします。
2. 個人情報や認証情報が公開用ファイルやPCK内に含まれていないか確認します。
3. このリポジトリの書き出しファイルを最新の一式に置き換えます。HTML・JavaScript・WASM・PCKは同じ書き出しの組み合わせで更新してください。
4. 変更をコミットして`main`へプッシュします。
5. GitHubのActionsでPagesの公開処理が成功したことを確認し、公開URLで起動を確認します。
6. Windows版も更新する場合は、起動と梱包内容を確認したZIPを、新しいGitHub Releaseに添付します。

`.gitignore`は公開対象を現在の書き出しファイルと設定ファイルに限定しています。追加の実行ファイルが生成された場合は、その内容を確認したうえで許可リストを更新してください。監査データ、ログ、開発資料、認証用ファイルは登録しないでください。

コミット作者のメールを公開したくない場合は、GitHubのnoreplyアドレスを使用してください。今回の公開用作業コピーには、作者名`norimashi`とGitHubのnoreplyアドレスをローカル設定しています。

## 公式資料

- [GodotのWebエクスポート](https://docs.godotengine.org/en/stable/tutorials/export/exporting_for_web.html)
- [GitHub Pagesの公開元設定](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
