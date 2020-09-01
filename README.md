html 
- tplファイルの一番親divに、tplファル名を同じclass名を書く
- class名は、aboutページ独自の名称を使う
- 小要素のdomには、親要素の名前を踏襲した名称にする。長すぎたら短調にしてよい。
- cordy_design側のcssは、jsに依存してしなければ削除する。

scss
- importantは使わない
- floatは使わない
- class名の記述に & は使わない。
- color , font-size , margin padding レスポンシブは 変数を使用する。
- スタイリングは モバイルファースト
- min-widt で拡張するスタイリングにする
- tabletも考慮する。
- scssの階層は3階層までを目安にする