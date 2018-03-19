# kaggle_leaf_classification

kaggleのLeaf Classificationに取り組みました。
https://www.kaggle.com/c/leaf-classification

99個の葉の種類を、画像から学習させるというものです。

実行環境　
*windows 10 *Python 3.6.2 *chainer 2.0.0

Outline
1. データの読み込み
2. 画像のテンソル化
3. 大きさを64*64のテンソルに統一する
4. データのaugumentationを行う。
5. CNNを定義し学習を行う。


結果　20epoch回したのですが10epochあたりから過学習の傾向が顕著になってきました。
やはりラベル数99に対してデータ数990個では画像データの水増しをしても限界があるようです。
あとパソコンのCPUだけではかなりしんどかったです。
