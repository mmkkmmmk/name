# name

figma:https://www.figma.com/file/IDbUNwP6LEjThwOOi9qqaR/%E3%82%B5%E3%83%B3%E3%83%A9%E3%82%A4%E3%82%BA%E4%BA%BA%E4%BA%8B%E7%AE%A1%E7%90%86?type=design&node-id=0-1&t=a1dxw8SWtckPbvXx-0

■ サービス概要
面接から退社処理まで人に関する情報や処理を明確にし、
各現場直行直帰が多く連携がとりずらい常駐型の仕事に関して
日々の動向や処理が可能となる人事管理サービスです

■ ユーザーが抱える課題
常駐現場と本社の距離が遠く直行直帰が多いため
連携をとるのに時間がかかる
紙でのやり取りは紛失を招きコストもかかる

■ 課題に対する仮説
現場との連携を図るために現地に行かなければなら無い
紙媒体によるやり取りは郵送時間などに時間がかかる
一人一人の申請を紙媒体で処理や承認をすることに時間がかかる
集計してデータに打ち込むことが時間がかかる
現地で予定通り出勤退勤ができているかは
月末の出勤簿を見て知ることになり当日は従業員からの連絡がなければ
状況はわから無い
従業人に関する情報の更新や出勤日がバラバラなため周知するのに時間がかかる
現場数や一人現場でパソコンを各現場用意する環境が作れ無い
またパソコンを必要とする作業現場が少ない
予定表配布や出勤簿提出など郵送や持参による移動時間やタイムラグが発生してしまう
社員に知らせたい情報周知に時間がかかる

■ 解決方法
従業員は
出勤確認、申請、予定表、出勤簿、資機材発注
を各自のスマホよりログインし、処理を行うことにより
タイムラグ短縮化、処理のリアルタイム化
いつでも活用でき時間帯に縛られ無い
電子化することにより紙媒体の費用削減や紛失を防ぎ
データを収集活用することにより資機材がどの程度出ているかコストなど
分析が可能

■ メインのターゲットユーザー
直行直帰型社員　　　　 → 本社とのやりとりがしやすくなる
パソコンが不得意な社員 → 一貫性のあるデータ作り
管理職　　　　　　　　 → 確認しやすい仕組みづくり

■ 実装予定の機能 -一連処理の情報共有化  
 顧客情報 → 見積作成 → 日程調整 → 報告書 → 請求書 → 集金、入金確認

【予定表作成】
・現場社員
休暇願いが申請できる
予定表を確認することができる
・本社社員
休暇願いをもとに予定表を作成することができる
予定表完成後の変更をかけることができる

【出勤簿作成】
・現場社員
自身のアカウントにより出勤、退勤を送信することができる（GPS 連動）
有給申請をすることができる
・本社社員
予定表との差を日々確認することができる
有給申請の回答ができる
給料プログラムにインポートすることができる

【資機材発注】
・現場社員
必要資機材を申請することができる
配布日を確認できる
・本社社員
各現場で必要資機材申請を集計し
現在在庫数で足りるか判断する
在庫が足り無いものに関しては購入伺いを作成できる
配布日を入力できる
配布の確認ができる
・管理職
年間の現場による資機材発注量や金額が確認できる

【制服申請】
・現場社員
写真添付と交換申請ができる
・本社社員
制服申請による承認確認
現在在庫数で足りるか判断する
在庫が足り無いものに関しては購入伺いを作成できる
支給予定日入力できる
支給確認ができる
・管理職
全社員の制服種類や配布枚数が確認できる

【給与明細確認】
・現場社員
自分の給与明細を確認することができる
・本社社員
給与プログラムよりインポートして
現場社員に配布することができる

【退社処理】
・本社社員
退社に必要なデータをフォームにより入力することができる

■ なぜこのサービスを作りたいのか？
現場と本社との連携強化を図るため
タイムラグがあるプロセスをなくすため
管理しやすく見える化を図るため
月毎の処理を短縮化することにより
他のことに力を入れるため

■ スケジュール
企画〜技術調査：5/16 〆切
README〜ER 図作成：5/31 〆切
メイン機能実装：6/1〜9/1
β 版を RUNTEQ 内リリース（MVP）：9/1 〆切
本番リリース：9 月末

■ 技術選定

- Rails7
- postgresql
- JavaScript
- Bootstrap
- heroku
