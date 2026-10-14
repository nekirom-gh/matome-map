# まとめてマップ

行きたい場所を順に並べて、Googleマップにルートとしてまとめて渡すWebアプリ。`index.html` 1枚で動き、APIキーは不要。

- 入力中に候補を表示（OpenStreetMap の [Photon](https://photon.komoot.io/) 検索）。1つ前の地点の近くを優先して距離順に並ぶ。
- 候補から選んだ地点は座標でGoogleマップに渡すので、同名の別の場所に飛ばない。
- 「Googleマップで開く」で公式の経路URL（`/maps/dir/?api=1`）を開く。以降の操作はGoogleマップで。目的地は最大10か所。
- 入力内容はブラウザの localStorage にだけ保存。

地図データ © OpenStreetMap contributors
