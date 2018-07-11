## 特徴量
以下からダウンロードできます。
https://www.dropbox.com/s/crm7501jgjje4nz/features.7z?dl=0

- *_time_diff : S1~S5,S24,S25の中での最大時間 - 最小時間
- *_diff2adj : (Id順でソートしたときに)mean_numについて、前後の行との差をとったもの
- *_adj_failed : (Id順でソートしたときに)前後の行が失敗しているかどうか。
- *_adj_failed_t : (時間順でソートしたときに)前後の行が失敗しているかどうか
- *_mean_num : 数値型の特徴量の上位について、列全体で平均をとったもの

## コード
notebook/以下

## Submitファイル
lgb_private0.41291.csv : notebook/LightGBMで学習したもの。
