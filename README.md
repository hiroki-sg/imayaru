# いまやる v7

修正:
- 「追加する」を本物のHTMLフォーム送信に変更
- JavaScriptでは submit イベントを受けてタスクを追加
- localStorage が禁止された環境でも、画面を閉じるまではメモリ上で動作
- JavaScript自体が禁止されたプレビューでは <noscript> で明示
- Safari / GitHub Pages 等の通常ブラウザでの利用を前提

重要:
ChatGPT内のHTMLプレビューはJavaScriptを実行しないことがあり、その場合
タスクの追加・保存・自動推薦は動作しません。CSSだけの画面切替は動きます。
