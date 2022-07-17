# アプリケーション名：お問い合わせフォーム（管理システム付き）
### ○お問い合わせフォーム
- 「意見」を送信することができる。（お名前、メールアドレス、住所なども同時送信する）

![スクリーンショット (22)](https://user-images.githubusercontent.com/103915849/179387425-a077edcc-b7b7-4772-8e12-3a95bbf71ef9.png)



### ○管理システム
- 全データから、条件検索が可能。
##### ※下記、出力データはダミーデータです。

![スクリーンショット (20)](https://user-images.githubusercontent.com/103915849/179387324-5b446892-ed6e-4db3-b922-c1213dd80149.png)


## 作成した目的：Advanceタームテスト提出用
- Advanceタームテストのため、作成。

## 機能一覧
#### ○お問い合わせフォーム
- 入力項目「お名前、性別、メールアドレス、郵便番号、住所、建物名、ご意見」の入力項目あり。
- 建物名以外は必須項目。送信時バリデーションあり。
- 「郵便番号」入力時、「全角から半角へ自動変換」「住所自動反映」の機能あり。
- 入力確認画面あり：　修正ボタンで、入力値を保持し入力画面に戻ることが可能。
- 送信完了画面あり。
#### ○管理システム
- 条件検索：　「お名前、性別、登録日、アドレス」での検索が可能。（一項目でも一文字でも該当すれば検索が可能）
- 検索後：　検索項目の入力値保持が可能。
- ページネーション：　10件ごとに表示。閲覧中のページの視覚化。
- 削除機能：　表示データから削除ボタンで削除が可能。
- 初期画面：　全件表示となる。
- リセットボタン：　全件表示のページに戻せる。
- ご意見：　管理システム内では「25文字」までの表示としている。

## 使用技術（実行環境）
- Laravel Framework 8.83.18

## テーブル設計

![スクリーンショット (19)](https://user-images.githubusercontent.com/103915849/179387707-c5b62aec-3598-47f0-816e-dfa31945a2ce.png)

## ER図

![er drawio](https://user-images.githubusercontent.com/103915849/179387439-89e638e2-4719-447a-9f26-fab70e32e082.png)
