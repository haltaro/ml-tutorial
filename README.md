# 機械学習勉強会

## はじめに

機械学習の基礎を，二ヶ月で一通り復習します．

## 環境構築

言語は[python3](https://www.python.org/)と[R](https://www.r-project.org/)を想定します．環境設定ファイルは，`env.yml`です．`conda`コマンドが使える場合は，以下で仮想環境を構築できます．

```bash
$ conda create --file env.yml
$ activate ml #MacやLinuxの場合は，source activate mlかも．
```

## 参考

本勉強会では，以下を参考にします．

* [Scikit-learn:tutorials](http://scikit-learn.org/stable/tutorial/index.html)：Pythonの機械学習ライブラリであるscikit-learnのチュートリアルです．今回はテキスト処理は割愛します．
* [Scikit-learn: Dimentionality reduction](http://scikit-learn.org/stable/modules/decomposition.html#decompositions)：Principal component analysis（PCA）を始めとする，次元削減技術のチュートリアルです．
* [Scikit-learn: Preprocessing](http://scikit-learn.org/stable/modules/preprocessing.html#preprocessing)：正規化を始めとする，データの前処理のチュートリアルです．
* [久保拓哉，データ解析のための統計モデリング入門](http://amzn.asia/g3XaAKg)：データ解析の代表的な教科書です．Rのソースコードつき．

## 全体計画

毎週木曜の夕方に開催します．

|#|日付|テーマ|
|:--|:--|:--|
|1|10/26|[Scikit-learn入門](https://github.com/haltaro/ml-tutorial/blob/master/01.intro_to_scikit-learn.ipynb)|
|2|11/2|[Scikit-learnで統計的学習](https://github.com/haltaro/ml-tutorial/blob/master/02.statistical-learning.ipynb)（1/2）|
|3|11/9|[Scikit-learnで統計的学習](https://github.com/haltaro/ml-tutorial/blob/master/02.statistical-learning.ipynb)（2/2）|
|4|11/16|[Scikit-learnで次元削減](https://github.com/haltaro/ml-tutorial/blob/master/03.dimensionaly_reduction.ipynb)（1/2）|
|5|11/23|[Scikit-learnで次元削減](https://github.com/haltaro/ml-tutorial/blob/master/03.dimensionaly_reduction.ipynb)（2/2）|
|6|11/30|[Scikit-learnで前処理](https://github.com/haltaro/ml-tutorial/blob/master/04.preprocessing.ipynb)（1/2）|
|7|12/7|[Scikit-learnで前処理](https://github.com/haltaro/ml-tutorial/blob/master/04.preprocessing.ipynb)（2/2）|
|8|12/14|未定|

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
