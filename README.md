# 令和6年能登半島地震 被災状況マップ
令和6年能登半島地震に関連して被災地の人口分布をMapLibre GL JSで表示するデモサイトです。

## Public Website
https://shi-works.github.io/noto-hanto-earthquake-2024-100m-mesh-pop-map-on-maplibre-gl-js/

## Data Source
### 人口分布データ
- 令和2年簡易100mメッシュ人口データ（石川県、富山県）（FlatGeobuf形式）
    - 出典：https://github.com/shi-works/noto-hanto-earthquake-2024-100m-mesh-pop-data
        - 原初データ出典：[地域分析に有用なデータの提供, 地域・交通データ研究所代表（東京大学空間情報科学研究センター客員研究員）西澤明](https://gtfs-gis.jp/teikyo/index.html)
    - 概要：地域・交通データ研究所にて公開されている令和2年簡易100mメッシュ人口データをFlatGeobuf形式に変換したデータ。
    - ライセンス：[西澤明](https://gtfs-gis.jp/teikyo/index.html)、[@shi-works](https://twitter.com/shi__works)、[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)

### 背景地図及び地形データ
- 国土地理院 最適化ベクトルタイル
    - 出典：https://github.com/gsi-cyberjapan/optimal_bvmap
- 国土地理院 地理院タイル（デジタル標高地形図：【技術資料D1-No.959】）
    - 出典：https://maps.gsi.go.jp/development/ichiran.html#digiele
- 産業技術総合研究所 シームレス標高タイル（統合DEM）
    - 出典：https://tiles.gsj.jp/tiles/elev/tiles.html
