# tsukuba_symposium_2024

## LaTeX install

```
sudo apt install texlive-lang-cjk xdvik-ja evince texlive-science texlive-fonts-recommended texlive-fonts-extra
```

## ビルドの方法

```
git clone https://github.com/CIT-Autonomous-Robot-Lab/tsukuba_symposium_2024.git
cd tsukuba_symposium_2024
make
```

## pushする前に

余計なファイルを削除できます

```
make clean
```

## 内容について・進め方について

* 各チームでやったことをどんどん書いていく
* とりあえず、各チーム間のつながりは気にしないで良い
* 修正したい箇所を見つけたら、自分のではなくてもどんどん修正して欲しい（改悪はなるべく避けて欲しい）

## TeXファイルの構成について
- main.tex
    - チームの共通事項の記述と以下のTeXファイルを読み込んで統合をするファイル
- robot_mugimaru.tex
    - むぎまるチームのロボットの構成を書くファイル
- robot_kinako.tex
    - 上のファイルのきなこチーム版
- result_mugimaru.tex
    - むぎまるチームの走行結果を書くファイル
- result_kinako.tex
    - 上のファイルのきなこチーム版

## 締め切りについて

2025/1/31締切  
[第18回つくばチャレンジシンポジウム](https://tsukubachallenge.jp/2024/about/symposium)
