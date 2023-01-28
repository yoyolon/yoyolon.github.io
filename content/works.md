---
title: "Works"
date: 2023-01-21T01:43:04+09:00
draft: false
---

これまでに個人開発した作品をご紹介します．

## ソフトウェア

主にCG関連のツールを開発しています．

- [testpt](https://github.com/yoyolon/testpt)
  - C++で開発したパストレーサー．
  - 物理ベースレンダリングを理解するために開発しました．
  - NEEやMISなどのモンテカルロ推定の分散低減手法も実装しています．

- [thinfilm_visualizer](https://github.com/yoyolon/thinfilm_visualizer)
  - Pythonで開発した薄膜干渉可視化ツール
  - 研究で扱っている薄膜干渉現象を簡単に可視化するために開発しました．
  - Tkinterを利用しているため，GUIによる直感的な操作が可能です．

- [py_raytracing](https://github.com/yoyolon/py_raytracing)
  - Pythonで開発した非常にシンプルなレイトレーサー(130行程度)．
  - レイトレーシングの基礎を復習する目的で開発しました．
  - ハイライトの表示のため，Phong反射モデルを実装しています．

## ゲーム

書籍などを参考にシンプルなゲームを開発しています．

- [fruits_catch](https://github.com/yoyolon/fruits_catch)
  - C++で開発したシンプルな2Dゲーム．
  - ゲームプログラミングの基礎的な仕組みやクラス設計を理解するために，[ゲームプログラミングC++(翔泳社)](https://www.shoeisha.co.jp/book/detail/9784798157610)で学んだ内容をベースに開発しました．
  - グラフィックス処理には低レイヤーライブラリの[SDL](https://github.com/libsdl-org/SDL/tree/SDL2)を利用して実装しました．
  - ゲームに使用したアセットはPhotoshopで自作しました．
