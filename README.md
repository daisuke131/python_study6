# 実案件ベースの課題

こちら実際にランサーズであった案件になります。  
こちらをベースにした課題になります。
![image](https://user-images.githubusercontent.com/16814992/132815947-615d427e-c3c1-4245-bc73-a2469d0ff124.png)

## GUI化
アプリの画面を作成し、
- キーワード
- 参考上代 下限額～上限額  
それぞれテキストボックスを設け、検索ボタンによって、それらの条件で検索できるようにしましょう。

## 内部処理
- マルチスレッドで処理するようにしましょう。
- CSVで出力するようにしましょう。
  - ファイル名は、どういう条件で検索したかわかるようにしましょう。後ろに年月日時間をつけましょう。
- ログを出力しましょう。

## CSVの出力項目
- 商品掲載URL
- 商品タイトル
- サイズ（複数の場合はカンマ区切り）
- 画像URL1（1枚目）
- 画像URL2（2枚目まで）
- JANコード
- 商品コード
