## 概要
libftは、標準Cライブラリの関数の一部と追加のユーティリティ関数を再実装するプロジェクトです。  
このプロジェクトは、42東京のカリキュラムの一部であり、学生がC言語のプログラミングスキルを向上させることを目的としています。

## プロジェクトの目的
このプロジェクトの主な目的: 
- 標準Cライブラリの関数の内部動作を理解する
- ライブラリをゼロから実装する方法を学ぶ
- 再利用可能なコードを書く方法を学ぶ

このプロジェクトを通して、身につけられるスキル: 
- 文字列操作
- メモリ管理
- ポインタの使用

## コンパイル方法
1. リポジトリをクローン: ```git clone https://github.com/ANS0025/42_libft.git```
2. プロジェクトディレクトリに移動: ```cd 42_libft```
3. コンパイル: ```make```

## テスト方法
1. テストファイル（例：main.c）を作成し、libft.hをインクルードする
2. 必要な関数を呼び出すテストコードを書く
3. テストファイルをコンパイル: ```cc -Wall -Wextra -Werror main.c libft.a```
4. 生成された実行ファイルを実行し、関数の動作を確認

サードパーティ製のテスター:
- https://github.com/Tripouille/libftTester
- https://github.com/alelievr/libft-unit-test  
これらのテスターを使用する場合は、それぞれのREADMEファイルに従ってセットアップとテストを行ってください。
