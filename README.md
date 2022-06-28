README
-------------------------------------------------
### Kiyoraについて
 このアプリは建築設備業に特化した業務アプリです。    
伝票の起票から請求書発行までトータルに業務をサポート
します。
-------------------------------------------------

### 開発の理由
1. 前職で使用していたシステムがどのように設計されていたか  
詳しく知りたいと学習中に思うようになりました。
2. 就業前に業務アプリの作成をイメージしたかった為、  
自分に身近なテーマを選択。
3. 自分だったらどうやって作るのか作成のプロセスを確認した  
かった為です。
-------------------------------------------------
### 問題と解決
前職で使用していたシステムでは、下記の問題点がありました。
1. 伝票作成に時間がかかる。
2. 緊急の案件と定期のスケジュールがバッティングする。
3. 急な作業にも対応できるようにしたい。

この問題を解決する為、オリジナルアプリケーションでは下記の
解決策を持ったアプリとなっています。

解決策：
1. 検索機能を充実させること。
2. いつ誰が何を作業しているのか一眼でわかるようすること。
3. 天候に左右される作業がある為、天気予報も取得できること。
-------------------------------------------------
### 今後の課題
1. Google apiとの連携
2. AWS Dockerとの連携
3. Google Apps Script 
　　更新された時点でスプレッドシートにて共有
-------------------------------------------------
開発言語
-------------------------------------------------
* Ruby 3.0.1
* Ruby on Rails 6.0.3

就業Termの技術
-------------------------------------------------
* フォロー機能
* Devise

カリキュラム外の技術
-------------------------------------------------
* gem prown を使ったPDF作成機能
* AWS S3を使用したサンプル動画
* Openweather を利用したAPI機能連携による天気予報情報取得
* gem simple_calendarを利用したカレンダー表示機能
* gem ransackによる検索機能
-------------------------------------------------

使用したgem 一例
-------------------------------------------------
* gem 'gimei'
* gem 'seed-fu'
* gem 'jquery-rails'
* gem 'faker'
* gem 'cancancan'
* gem 'rexml'
* gem 'ransack'
* gem 'prawn'
* gem 'prawn-table'
* gem 'simple_calendar', '~>2.0'
* gem 'dotenv-rails'
* gem 'rails-i18n'
* gem 'devise-i18n'
* gem 'kaminari'
-------------------------------------------------
```
$ https://github.com/satokofuwa/kiyora.git
$ cd kiyora
$ bundle install
$ rails db:create && rails db:migrate
$ rails s
```  

カタログ設計
-------------------------------------------------
https://docs.google.com/spreadsheets/d/1JMhJOQS91-ZK-f73xL2tE2IqoGj7_gT2Rvn__vD_NuI/edit?usp=sharing


テーブル設計
-------------------------------------------------

https://docs.google.com/spreadsheets/d/1JMhJOQS91-ZK-f73xL2tE2IqoGj7_gT2Rvn__vD_NuI/edit?usp=sharing



画面遷移図 E-R図　ワイヤーフレーム 
--------------------------------------------------

https://github.com/satokofuwa/kiyora/blob/step13/Kiyora.pdf




