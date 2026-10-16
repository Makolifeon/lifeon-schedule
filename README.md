# Life On Schedule

独立した日程調整Webアプリです。Google Calendar FreeBusy APIの読み取り連携に対応します。

## GitHub Pages
Settings → Pages → Deploy from a branch → main / (root) → Save

## Google認証
Google CloudでCalendar APIを有効化し、OAuthクライアント（ウェブアプリケーション）を作成。承認済みJavaScript生成元に `https://makolifeon.github.io` を登録してください。

## 制限事項
Googleへの書き込みやリアルタイムの予約確定は未実装。候補URLは作成時点のスナップショットです。予定あり時間のみを参照し、予定内容は公開しません。個人情報や秘密情報を公開リポジトリに入れないでください。