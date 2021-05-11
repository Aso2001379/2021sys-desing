@startuml
 ユーザー -> webサーバー:商品検索
 webサーバー -> DBサーバー:商品検索
 DBサーバー -> DBサーバー:検索処理
 DBサーバー -> webサーバー:検索結果
 DBサーバー -> ユーザー:検索結果
 end
 @enduml





