## 自動販売機（データ構造と各種処理）のミニレポート
### Q5-1. 自動販売機の商品データついて説明せよ。
* データ構造（各項目とその説明）

  idは商品の番号、nameは商品名、priceは値段、stockは在庫数。
* 連想配列の配列として定義するメリット

  キーと値をペアで管理することができる。

  商品ごとの情報が管理しやすい。
### Q5-2. showItemListの処理内容について説明せよ。
* 配列の繰り返し処理

  商品一覧を表示するためにfor文を使う
  
* 連想配列の参照方法

  item.で参照する
  
### Q5-3. buyItemの処理内容について説明せよ。
* 商品購入の可否判定

  items.findによって商品に在庫があるか確認する

* 商品在庫を減らす処理

item.stock--で在庫を一つずつ減らしている
  
* 商品番号のエラー処理

  商品在庫や商品番号がない場合はメッセージを表示するようにしている
  
### Q5-4. プログラムの考察
* データ構造について

  商品情報を連想配列によって格納することで管理しやすくしている
* 商品一覧表示と購入処理を関数化したメリット

  コードが分かりやすくなる
### Q5-5. 感想
* 今回の課題で苦労したこと

  for文の使い方
* 演習を通して理解できたこと

console.logを使うことで開発者ツールのコンソールメニューで出力結果が見えること

連想配列を定義するメリット
* この自動販売機プログラムの追加機能や課題など

  課題3-2の合計値を出すコードなどを応用すれば複数個買ったときに合計金額を表示することができる。
