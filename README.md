# ticket_site
* チケットサイトを作ってみる

## ユースケース
* ユーザーログイン
* 主催者
  * 自分の主催しているイベントの一覧・参加者を見れる
  * イベントのキャンセル
  * イベントを作成する
* 参加者
  * イベントに申し込む
  * 参加キャンセル
  
## テーブル
* User
  - name
  - age
  - sex
* Event
  - name
  - detail
  - start_at
  - end_at
  - capacity_count
* Participant
  - user_id
  - event_id
