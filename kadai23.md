```startuml
@startuml
!define MASTER_MARK_COLOR Orange
entity "顧客マスタ" as customer<m_customers> <<M，MASTER_MARK_COLOR>> {
    +customer_code [PK]
    --
    pass
    name
    address
    tel
    mail
    del_flag
    reg_date
}    
@enduml
```
```startuml
@startuml
!define MASTER_MARK_COLOR Blue
entity "購入テーブル" as customer<d_purchase> <<T，table_MARK_COLOR>> {
    +order_id [PK]
    --
    +customer_code [FK]
    purchase_date
    total_price
}    
@enduml
```
