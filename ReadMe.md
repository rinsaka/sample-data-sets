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

## [names.json](https://github.com/rinsaka/sample-data-sets/blob/master/names.json), [novels.json](https://github.com/rinsaka/sample-data-sets/blob/master/novels.json), [scores.json](https://github.com/rinsaka/sample-data-sets/blob/master/scores.json), [scores2.json](https://github.com/rinsaka/sample-data-sets/blob/master/scores2.json), [scores3.json](https://github.com/rinsaka/sample-data-sets/blob/master/scores3.json)
- JSONファイルの読み書きに関するサンプルデータ
- [https://rinsaka.com/python/file/04-01-json.html](https://rinsaka.com/python/file/04-01-json.html)


## [tegaki-number.zip](https://github.com/rinsaka/sample-data-sets/blob/master/tegaki-number.zip)
- 手書き数字の認識のためのサンプルデータ
- [https://rinsaka.com/python/tegaki/index.html](https://rinsaka.com/python/tegaki/index.html)

## hyaku.json
- 百人一首のデータ
