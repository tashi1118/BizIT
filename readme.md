## BizITについて

BizITは、ビジネス・ITについての相談や質問ができるWeb掲示板サービスです。 
ビジネス担当者やIT担当者がお互いに対して抱えている困りごとについて気軽に発信し、「困った」を解決します。
https://bizit.work

## 機能について
- ログイン機能
- 投稿機能
- 自分の投稿一覧機能
- 投稿更新機能
- 投稿削除機能
- 投稿へのコメント機能
- 投稿お気に入り機能
- お気に入り数ランキング機能
- 権限管理（admin/master）機能
- 投稿のカテゴリー機能
- カテゴリー申請機能
- プロフィール画像投稿機能

## 技術的ポイントについて
- AWS EC2/RDSを用いた本番環境構築
- AWS ALBによるロードバランシング（マルチAZ）
- AWS ACMでのSSL証明書発行、常時SSL化
- 独自ドメインの取得、AWS Route53による運用
- GitHubによるバージョン管理

## その他環境など
- Laravel5.7
- PHP7.2
- テストユーザーとしてログイン可能