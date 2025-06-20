```mermaid
flowchart TB
  node_1("トップページ")
  node_2("ログインページ")
  node_3("会員登録ページ")
  node_4("書籍一覧ページ")
  node_5("マイページ")
  node_6("会員情報ページ")
  node_7("注文履歴ページ")
  node_8("商品検索ページ")
  node_9("カテゴリ一覧ページ")
  node_10("書籍詳細ページ")
  node_11("カートページ")
  node_12("カートページ")
  node_13("購入ページ")
  node_14("配送先・決済方法選択ページ")
  node_15("購入完了ページ")
  node_1 --> node_2
  node_1 --> node_3
  node_1 --> node_4
  node_2 --> node_5
  node_3 --> node_5
  node_5 --> node_6
  node_5 --> node_7
  node_4 --> node_8
  node_4 --> node_9
  node_8 --> node_10
  node_9 --> node_10
  node_5 --> node_11
  node_10 --> node_2
  node_2 --> node_12
  node_12 --> node_13
  node_13 --> node_14
  node_14 --> node_15
``` 
