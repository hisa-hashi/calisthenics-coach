# Calisthenics Coach PWA v0.2

iPhone Safari向けの静的PWAです。HTTPSで配信し、Safariの共有メニューから「ホーム画面に追加」してください。

## 主な機能

- A/B/C・全12種目のお手本動画（YouTube公式埋め込み、タップ後に読み込み）
- 日本語のフォーム要点、低負荷の代替動作、出典表示
- 日本語音声コーチ、運動・休憩タイマー
- 完了履歴の端末保存とJSON書き出し
- アプリ本体のオフライン起動（動画再生には通信が必要）

## ローカル確認

`python3 -m http.server 8080` などでこのフォルダを配信し、`http://localhost:8080` を開きます。Service WorkerとYouTube埋め込みは、ファイルを直接開くのではなくHTTP/HTTPS経由で確認してください。
