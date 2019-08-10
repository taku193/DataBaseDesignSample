# DB設計

## groups_usersテーブル

|Column|Type|Option|
|------|----|------|
|user_id|integer|null: false, foreign_key: true|
|group_id|intefer|null: false, foreign_key: true|

### Association
- belong_to :group
- belong_to :user