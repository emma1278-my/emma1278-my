## データベース設計における悩み

- エンティティの数が多い
（DB設計が定まらないとプログラム設計が確定しない、実力がシステム開発のボトムネックになりやすい、バックアップや領域管理等の運営に影響を与える、アクセスが集中するためパフォーマンスに影響を及ぼす等）
正規化の悩みよりも、データ項目の洗い出しに対する自身の欠如の方が大きなウェイトを占めている。

## 箱（エンティティ）の見出し方
- 集まりに入っているかどうかを明確に区別するため、エンティティという箱に入れるイメージをする
- 模擬的に図式化すること「モデリング」
- 

主キーの設定
重複の排除（いわゆる正規化）

データベースにおける「レコード」
消えると困るデータの「記録」。
「タプル」
一般にレコードと呼ばれる「データ項目の組み合わせの構造」のこと。
「インスタンス」
タプルに実際の値が入って現実化したもの。
リレーショナルデータベースにおいての「ドメイン」
カラム（列）のこと。
データベース設計の3つのポイント
