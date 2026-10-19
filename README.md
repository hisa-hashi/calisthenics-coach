# Calisthenics Coach PWA v0.3

iPhone Safari向けの静的PWAです。HTTPSで配信し、Safariの共有メニューから「ホーム画面に追加」してください。

## 主な機能

- A/B/C・全12種目のオフライン動作ステップとフォーム図解
- 日本語のフォーム要点、低負荷の代替動作、参考動画へのリンク
- 3セットを含む全メニューの自動連続進行
- 日本語音声コーチ、運動・休憩・種目間タイマー
- トレーニング中の画面スリープ防止（対応するiPhone/Safari）
- 完了履歴の端末保存とJSON書き出し
- アプリ本体と動作ガイドのオフライン起動

## ローカル確認

`python3 -m http.server 8080` などでこのフォルダを配信し、`http://localhost:8080` を開きます。Service WorkerとYouTube埋め込みは、ファイルを直接開くのではなくHTTP/HTTPS経由で確認してください。
