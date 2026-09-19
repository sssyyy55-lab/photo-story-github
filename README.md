# フォトストーリー GitHub Pages版

写真から動画を作るブラウザアプリの試作版です。サーバー処理・APIキー・ビルドは不要です。

## 配置

このフォルダーの中の index.html、style.css、app.js、README.md をGitHubリポジトリの一番上にアップロードしてください。ZIP自体ではなく展開したファイルをアップロードします。

GitHubの Settings → Pages → Build and deployment で、Source を Deploy from a branch、Branch を main、フォルダーを / (root) にして保存します。main 以外を使う場合は実際のブランチ名を選びます。公開後のURLはPages画面に表示されます。

一般的なGitHub Pages公開では誰でもアプリにアクセスできます。現在のChatGPT Sites版の本人限定アクセスは引き継がれません。写真やBGMをリポジトリにアップロードする必要はありません。

## 使い方

1. 写真を追加します。
2. 5種類から目的を選びます。
3. タイトル・長さ・画面方向・BGMを設定します。
4. 写真の章やテロップを調整します。
5. プレビュー後に動画を書き出し、完了後に保存します。

最初は写真3〜5枚、15秒・動作確認、BGMなしで試してください。

## 現在の制限

- 画像の内容をAIで分類する機能、顔ぼかし、人物の公平性判定は未実装です。
- 章は選択順をもとに割り当てられ、手動変更できます。撮影日時の解析はありません。
- 写真とBGMはブラウザ内で処理します。ページを閉じると編集内容は失われます。
- 動画は横1280×720または縦720×1280です。
- 書き出しには動画と同じ時間が必要です。画面を開いてお待ちください。
- 保存形式はブラウザによりMP4またはWebMです。iPhone実機での保存は未検証です。
- GitHub Pages上での実機動作は公開後に確認してください。

公式設定案内: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
