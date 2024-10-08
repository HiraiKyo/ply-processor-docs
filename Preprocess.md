# 実データの特徴と前処理の対応表

## ノイズ除去
| 手法 | 検索用ワード | 実装 |
| --- | --- |
| 近傍点との距離でフィルター | Statistical outlier removal | [Open3d](https://www.open3d.org/docs/latest/tutorial/Advanced/pointcloud_outlier_removal.html#Statistical-outlier-removal) |
| 近傍点密度でフィルター | Radius outlier removal | [Open3d](https://www.open3d.org/docs/latest/tutorial/Advanced/pointcloud_outlier_removal.html#Radius-outlier-removal) |
| 深層学習によるノイズ除去モデル | PCPNet, PointCleanNet | |
| 近傍特徴からノイズ点学習 | DMR Denoise | |