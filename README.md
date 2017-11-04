# 機械学習勉強会

## Introduction

機械学習の基礎を，二ヶ月で一通り復習します．

## Setup

[Python 3](https://www.python.org/)対応の[Anaconda](https://www.anaconda.com/download/)をインストールして頂ければ，問題ないと思います．Anacondaとは，Pythonのライブラリをまとめたディストリビューションです．以下が参考になります．

* [Qiita，Anaconda で Python 環境をインストールする](https://qiita.com/t2y/items/2a3eb58103e85d8064b6)

勉強会では，[Jupyter Notebook](http://jupyter.org/)を使います．Jupyter Notebookとは，ソースコードを含んだWebドキュメント作成を簡単に行える便利ツールです．使い方は以下をご参照ください．

* [Qiita，Jupyter事始め](https://qiita.com/taka4sato/items/2c3397ff34c440044978)
* [Qiita，はじめるJupyter Notebook](https://qiita.com/icoxfog417/items/175f69d06f4e590face9)


## Reference

本勉強会では，以下を参考にします．

* [scikit-learn:tutorials](http://scikit-learn.org/stable/tutorial/index.html)：Pythonの機械学習ライブラリであるscikit-learnのチュートリアルです．今回はテキスト処理は割愛します．
* [scikit-learn: Dimentionality reduction](http://scikit-learn.org/stable/modules/decomposition.html#decompositions)：Principal component analysis（PCA）を始めとする，次元削減技術のチュートリアルです．
* [scikit-learn: Preprocessing](http://scikit-learn.org/stable/modules/preprocessing.html#preprocessing)：正規化を始めとする，データの前処理のチュートリアルです．
* [久保拓哉，データ解析のための統計モデリング入門](http://amzn.asia/g3XaAKg)：データ解析の代表的な教科書です．Rのソースコードつき．

## Schedule

毎週木曜に開催します．

|#|日付|テーマ|
|:--|:--|:--|
|1|10/26|[scikit-learn入門](https://github.com/haltaro/ml-tutorial/blob/master/01.intro_to_scikit-learn.ipynb)|
|2|11/2|[scikit-learnで統計的学習](https://github.com/haltaro/ml-tutorial/blob/master/02.statistical-learning.ipynb)（1/2）|
|3|11/9|[scikit-learnで統計的学習](https://github.com/haltaro/ml-tutorial/blob/master/02.statistical-learning.ipynb)（2/2）|
|4|11/16|[scikit-learnで次元削減](https://github.com/haltaro/ml-tutorial/blob/master/03.dimensionaly_reduction.ipynb)（1/2）|
|5|11/23|[scikit-learnで次元削減](https://github.com/haltaro/ml-tutorial/blob/master/03.dimensionaly_reduction.ipynb)（2/2）|
|6|11/30|[scikit-learnで前処理](https://github.com/haltaro/ml-tutorial/blob/master/04.preprocessing.ipynb)（1/2）|
|7|12/7|[scikit-learnで前処理](https://github.com/haltaro/ml-tutorial/blob/master/04.preprocessing.ipynb)（2/2）|
|8|12/14|未定|

## Feedback

勉強会で頂いたフィードバックをまとめておきます．

- モデル，予測器，分類器等の用語を整理すること．

## Acknowledgement

建設的なフィードバックを下さった勉強会メンバーに感謝致します．

## License
MIT License

Copyright (c) 2017 haltaro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
