# ShotBar99 AI Bartender

ShotBar99 の店内用Webアプリ。KARAOKE AI（点数チャレンジ・AI選曲アドバイザー）と SHOT AI（AIショット診断・ショットルーレット）。

- `index.html` 1ファイルで動作（サーバー不要・GitHub Pages で公開可）
- ショットメニュー：`index.html` 内の `const MENU = [` を編集
- カラオケ曲リスト：`const SONGS = [` に1行ずつ追加
- 点数チャレンジの初期範囲：`CONFIG.scoreRange`
- OpenAI API を使う場合：APIキーを持つ自分のサーバーのURLを `CONFIG.aiEndpoint` に設定（APIキーはこのファイルに書かない）
