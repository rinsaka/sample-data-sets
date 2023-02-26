# サンプルデータ集
- このリポジトリに収録されているデータは [Python 入門](https://rinsaka.com/python/index.html)等で利用可能できるデータです．
- 実際のデータと演習のために生成されたデータの両方が混在しています．

## 電子機器販売業者の受注データ ([machine-sales.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales.csv) など)
- Pandas のグループ化とピボットテーブル，結合のためのサンプルデータ
- [https://rinsaka.com/python/pandas/12-groupby-pivot.html](https://rinsaka.com/python/pandas/12-groupby-pivot.html)
1. [machine-sales.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales.csv)
     - ピボットテーブルによる分析などを行うためのデータ
1. [machine-sales-utf8.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-utf8.csv)
     - machine-sales.csv の支店名や営業担当者名に漢字を使用 (UTF-8)
1. [machine-sales-sjis.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-sjis.csv)
     - machine-sales.csv の支店名や営業担当者名に漢字を使用 (Shift-JIS)
1. [machine-sales-sales.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-sales.csv), [machine-sales-branch.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-branch.csv), [machine-sales-staff.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-staff.csv)
     - machine-sales.csv を正規化して3つのファイルに分割したもの
     - 結合時には同じ系列名のリレーションシップをたどれば良い
1. [machine-sales-sales.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-sales.csv), [machine-sales-branch-id.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-branch-id.csv), [machine-sales-staff-id.csv](https://github.com/rinsaka/sample-data-sets/blob/master/machine-sales-staff-id.csv)
     - machine-sales.csv を正規化して3つのファイルに分割したもの
     - 3つのファイルの主キーがすべて id になっているため，結合時には系列名を明示的に指定する必要がある

## [corpora.zip](https://github.com/rinsaka/sample-data-sets/blob/master/corpora.zip)
- 自然言語処理で用いるテキストファイル
- [https://rinsaka.com/python/nltk/index.html](https://rinsaka.com/python/nltk/index.html)

## [ink_bk.png](https://github.com/rinsaka/sample-data-sets/blob/master/ink_bk.png)
- ワードクラウドのマスク用白黒画像データ
- [https://rinsaka.com/python/nltk/05-wordcloud.html](https://rinsaka.com/python/nltk/05-wordcloud.html)

## [clustering-sample.csv](https://github.com/rinsaka/sample-data-sets/blob/master/clustering-sample.csv)，[clustering-sample-notitle.csv](https://github.com/rinsaka/sample-data-sets/blob/master/clustering-sample-notitle.csv)
- クラスタリング (k-近傍法) などで利用する2次元データ
- [https://rinsaka.com/python/clustering.html](https://rinsaka.com/python/clustering.html)
- clustering-sample.csv は先頭行に列名があり，clustering-sample-notitle.csv は先頭行に列名がない

## [excel.xlsx](https://github.com/rinsaka/sample-data-sets/blob/master/excel.xlsx)
- 表計算 (Excel) の基礎実習
- [専門基礎講義](https://rinsaka.com/passitpass/)で使用

## [gochi-menue.csv](https://github.com/rinsaka/sample-data-sets/blob/master/gochi-menu.csv)
- 「ゴチ」バトルで用いるメニューと価格のデータ
- [https://rinsaka.com/python/gochi/index.html](https://rinsaka.com/python/gochi/index.html)

## [groupA-scores.csv](https://github.com/rinsaka/sample-data-sets/blob/master/groupA-scores.csv), [groupB-scores.csv](https://github.com/rinsaka/sample-data-sets/blob/master/groupB-scores.csv)
- 統計学の母平均の差の検定で用いる2つの母集団の得点データ
- [https://rinsaka.com/python/statistics/test-difference-between-means.html](https://rinsaka.com/python/statistics/test-difference-between-means.html)

## [kernel.csv](https://github.com/rinsaka/sample-data-sets/blob/master/kernel.csv)
- カーネル密度推定のためのサンプルデータ
- [https://rinsaka.com/python/kde.html](https://rinsaka.com/python/kde.html)

## [lr.csv](https://github.com/rinsaka/sample-data-sets/blob/master/lr.csv)
- 線形回帰モデルのためのサンプルデータ
- [https://rinsaka.com/python/linear-regression/index.html](https://rinsaka.com/python/linear-regression/index.html)

## [mra-01.csv](https://github.com/rinsaka/sample-data-sets/blob/master/mra-01.csv), [mra-02.csv](https://github.com/rinsaka/sample-data-sets/blob/master/mra-02.csv), [mra-02b.csv](https://github.com/rinsaka/sample-data-sets/blob/master/mra-02b.csv)
- 重回帰分析，ニューラルネットワークによる回帰分析のためのデータ
- [https://rinsaka.com/python/mra1.html](https://rinsaka.com/python/mra1.html)
- [https://rinsaka.com/python/mra2.html](https://rinsaka.com/python/mra2.html)
- [https://rinsaka.com/python/nn-regression.html](https://rinsaka.com/python/nn-regression.html)

## [ridge-train.csv](https://github.com/rinsaka/sample-data-sets/blob/master/ridge-train.csv), [ridge-test.csv](https://github.com/rinsaka/sample-data-sets/blob/master/ridge-test.csv)
- リッジ回帰のための学習データとテストデータ
- [https://rinsaka.com/python/ridge/index.html](https://rinsaka.com/python/ridge/index.html)

## [store-space-sales.csv](https://github.com/rinsaka/sample-data-sets/blob/master/store-space-sales.csv)
- 相関分析，線形回帰分析のためのサンプルデータ
- [https://rinsaka.com/python/corrcoef.html](https://rinsaka.com/python/corrcoef.html)
- [https://rinsaka.com/python/ols-linregress.html](https://rinsaka.com/python/ols-linregress.html)
- [https://rinsaka.com/python/ols.html](https://rinsaka.com/python/ols.html)
- [https://rinsaka.com/python/ols-sklearn.html](https://rinsaka.com/python/ols-sklearn.html)

## [corrcoef-sample.csv](https://github.com/rinsaka/sample-data-sets/blob/master/corrcoef-sample.csv)
- 相関分析，複数のグラフ（散布図）を作成するためのサンプルデータ
- データ数 100
- x列は 平均5, 標準偏差 2 の一様乱数
- その他の列は x との相関係数が -1.0 から +1.0 になるように生成したもの
- [https://rinsaka.com/python/matplotlib/10-subplot.html](https://rinsaka.com/python/matplotlib/10-subplot.html)

## [names.json](https://github.com/rinsaka/sample-data-sets/blob/master/names.json), [novels.json](https://github.com/rinsaka/sample-data-sets/blob/master/novels.json), [scores.json](https://github.com/rinsaka/sample-data-sets/blob/master/scores.json), [scores2.json](https://github.com/rinsaka/sample-data-sets/blob/master/scores2.json), [scores3.json](https://github.com/rinsaka/sample-data-sets/blob/master/scores3.json)
- JSONファイルの読み書きに関するサンプルデータ
- [https://rinsaka.com/python/file/04-01-json.html](https://rinsaka.com/python/file/04-01-json.html)


## [tegaki-number.zip](https://github.com/rinsaka/sample-data-sets/blob/master/tegaki-number.zip)
- 手書き数字の認識のためのサンプルデータ
- [https://rinsaka.com/python/tegaki/index.html](https://rinsaka.com/python/tegaki/index.html)

## 百人一首のデータ
- [hyaku.json](https://github.com/rinsaka/sample-data-sets/blob/master/hyaku.json) : JSON形式で文字コードは UTF-8
- [hyaku-utf-8-csv](https://github.com/rinsaka/sample-data-sets/blob/master/hyaku-utf-8.csv) : カンマ区切りテキストデータで文字コードは UTF-8
  - [https://rinsaka.com/python/hyaku/index.html](https://rinsaka.com/python/hyaku/index.html)
- [hyaku-sjis.csv](https://github.com/rinsaka/sample-data-sets/blob/master/hyaku-sjis.csv) : カンマ区切りテキストデータで文字コードは Shift-JIS（10番目の歌人「蟬丸」は「蝉丸」で代用していることに注意してください）

## 協調フィルタリングのためのデータ
- 協調フィルタリングによる推薦システムを作ってみよう
- [https://rinsaka.com/python/collaborative/index.html](https://rinsaka.com/python/collaborative/index.html)
- [collaborative_filtering_matrix.csv](https://github.com/rinsaka/sample-data-sets/blob/master/collaborative_filtering_matrix.csv) :
  - 行列形式の評価データ
- [collaborative_filtering_items.csv](https://github.com/rinsaka/sample-data-sets/blob/master/collaborative_filtering_items.csv), [collaborative_filtering_customers.csv](https://github.com/rinsaka/sample-data-sets/blob/master/collaborative_filtering_customers.csv), [collaborative_filtering_ratings.csv](https://github.com/rinsaka/sample-data-sets/blob/master/collaborative_filtering_ratings.csv)
  - 商品テーブル，顧客テーブル，評価テーブルのデータです．この3つを結合すると行列形式の評価データ ([collaborative_filtering_matrix.csv](https://github.com/rinsaka/sample-data-sets/blob/master/collaborative_filtering_matrix.csv)) を生成できます．

## Twitter のツイート数データ
- [tweet_20140617_hour.csv](https://github.com/rinsaka/sample-data-sets/blob/master/tweet_20140617_hour.csv)
  - 2014年6月17日の16時から8月7日12時までの1時間ごとの日本語ツイート数（全ツイートの1%を取得した結果を集計）
- [tweet_20140624_minute.csv](https://github.com/rinsaka/sample-data-sets/blob/master/tweet_20140624_minute.csv)
  - 2014年6月24日の5時から8時までの1分ごとの日本語ツイート数（全ツイートの1%を取得した結果を集計）
- [tweet_20140617_usj_hour.csv](https://github.com/rinsaka/sample-data-sets/blob/master/tweet_20140617_usj_hour.csv)
  - 2014年6月17日15時から8月6日13時までの1時間ごとのUSJ関連ツイート数
- [tweet_20140618_usj_day.csv](https://github.com/rinsaka/sample-data-sets/blob/master/tweet_20140618_usj_day.csv)
  - 2014年6月18日から8月6日までの1日ごとのUSJ関連ツイート数

## 画像内文字認識とPDFからの文字列抽出用テストデータ
- [https://rinsaka.com/python/tesseract/index.html](https://rinsaka.com/python/tesseract/index.html)
- [tesseract_data フォルダ](https://github.com/rinsaka/sample-data-sets/tree/master/tesseract_data)
- [tesseract_data.zip](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data.zip)
  - 上の tesseract_data フォルダのファイルを圧縮したもの
- [tesseract_data/en_1.docx](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_1.docx), [tesseract_data/en_1.pdf](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_1.pdf)
  - 英文のWordファイル（1ページ）とそれをPDFに変換したもの
  - PDFから文字列のコピーが可能
- [tesseract_data/en_1_img.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_1_img.png), [tesseract_data/en_1_img_trim.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_1_img_trim.png), [tesseract_data/en_1_img.pdf](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_1_img.pdf)
  - [tesseract_data/en_1.docx](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_1.docx) を画像に変換したもの（スクリーンショット）
- [tesseract_data/en_2.docx](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2.docx), [tesseract_data/en_2.pdf](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2.pdf)
  - 英文のWordファイル（合計2ページ）とそれをPDFに変換したもの
  - PDFから文字列のコピーが可能
- [tesseract_data/en_2_img1.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2_img1.png), [tesseract_data/en_2_img1_trim.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2_img1_trim.png), [tesseract_data/en_2_img2.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2_img2.png), [tesseract_data/en_2_img2_trim.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2_img2_trim.png), [tesseract_data/en_2_img.pdf](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2_img.pdf)
  - [tesseract_data/en_2.docx](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/en_2.docx) をページごとに画像に変換したもの（スクリーンショット）
- [tesseract_data/ja_1.docx](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/ja_1.docx), [tesseract_data/ja_1.pdf](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/ja_1.pdf)
  - 日本語のWordファイル（1ページ）とそれをPDFに変換したもの
  - PDFから文字列のコピーが可能
- [tesseract_data/ja_1_img.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/ja_1_img.png), [tesseract_data/ja_1_img_trim.png](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/ja_1_img_trim.png), [tesseract_data/ja_1_img.pdf](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/ja_1_img.pdf)
  - [tesseract_data/ja_1.docx](https://github.com/rinsaka/sample-data-sets/blob/master/tesseract_data/ja_1.docx) を画像に変換したもの（スクリーンショット）

## 物体検出のための画像データ
- [YOLOv5 で物体検出をしてみよう https://rinsaka.com/python/yolov5/index.html](https://rinsaka.com/python/yolov5/index.html)
- [yolo_images フォルダ](https://github.com/rinsaka/sample-data-sets/tree/master/yolo_images)
  - 20枚の写真データ
- [yolo_images.zip](https://github.com/rinsaka/sample-data-sets/blob/master/yolo_images.zip)
  - 20枚の写真データをzip形式に圧縮したもの

## staffs.sqlite
- SQLite データベースのサンプル
  - staffs テーブルは「id」「name」「age」「department」の列からなる
~~~
% sqlite3 staffs.sqlite
SQLite version 3.37.0 2021-12-09 01:34:53
Enter ".help" for usage hints.
sqlite> .tables
staffs
sqlite> .schema staffs
CREATE TABLE staffs (
    id INT NOT NULL,
    name VARCHAR(32),
    age INT,
    department VARCHAR(32),
    PRIMARY KEY(id)
);
sqlite> .headers ON
sqlite> SELECT * FROM staffs;
id|name|age|department
1|藤川|23|営業部
2|藤本|35|人事部
3|藤枝|32|製造部
4|藤原|48|営業部
5|藤森|44|人事部
6|藤平|28|製造部
7|藤谷|38|営業部
sqlite> .exit
%
~~~

