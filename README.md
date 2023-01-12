naist-thesis-tmpl(2020-)
===============================

NAIST先端科学技術研究科情報科学領域の日本語修士論文用LaTeXテンプレートです．

[このリポジトリのフォーク元](https://github.com/kmiya/naist-thesis-tmpl)は情報科学研究科時代のもののため，修士論文の提出フォーマットが現在のものと異なります．

ここに公開しているtexファイル群は2020年度版のstyファイルに記載されたコードを一部流用しつつ，見た目がなるべく2020年度版のサンプルPDFに近づくように調整をしています．

## bibtexについて
参考文献にbibtexを使う場合はreference.tex内の1-4行目を削除し
新たに
```tex
\bibliographystyle{junsrt}
\bibliography{xxx.bib,yyy.bib}
```
などと記述してください．

## 付録について
付録を入れる場合は新規にtexファイルを配置し冒頭に
```tex
\appendix
\chapter*{付録}
\addcontentsline{toc}{chapter}{付録}
```
と記述してmthesis.tex内にファイルを`\input{}`してください．
付録を書くときは`\section`から始めてください．

その他の説明はフォーク元のREADMEをご覧ください．
