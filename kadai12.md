```uml
@startuml
[*] --> トップページ
トップページ -> 会員登録
トップページ -left--> ログイン
トップページ --> スニーカー最新情報:最新情報をクリック
スニーカー最新情報 -> 抽選:抽選をクリック
トップページ --> スニーカーランキング:ランキングをクリック
スニーカーランキング -> スニーカーサイズ検索:サイズ検索をする
ログイン --> スニーカー一覧
スニーカー一覧 -> スニーカー検索
スニーカー一覧 -> トップページ
スニーカー検索 --> スニーカーサイズ検索
スニーカーサイズ検索 --> カラーセレクト:カラーを検索する
カラーセレクト -> カート:カートをクリック
トップページ --> カート:カートをクリック
カート -> お届け先入力
お届け先入力 -> お届け先入力内容確認
お届け先入力内容確認 -> 購入完了
購入完了 -> トップページ : トップページをクリック
購入完了 -> カート : カートをクリック
購入完了 -> トップページ : ログアウトをクリック
購入完了 -> トップページ : 商品検索する
@enduml
```
