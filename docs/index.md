- 目次
{:toc}


## 基本情報

|key|value|
|---|-----|
|Name|堀切 佑太郎（ほりきり ゆうたろう）|
|Bluesky|[@y-horikiri](https://bsky.app/profile/y-horikiri.bsky.social)|
|Qiita|[@y_horikiri](https://qiita.com/y_horikiri)

## スキル
### 言語
- Python
  - Django
  - FastAPI
- Rust
- Go
- TypeScript
- SQL
- Bash
- C#
- Ruby
- PHP
- HTML, CSS

### インフラ
- AWS
  - ECS
  - EC2
  - ALB
  - WAF
  - VPC
  - S3
  - RDS
  - SES
  - SNS
  - DocumentDB
  - ElastiCache
  - CloudWatch
  - EventBridge
  - StepFunction
  - CodeBuild
  - AppSync
  - Lambda
  - API Gateway
  - Athena
  - Kinesis Data Firehose
  - OpenSearch（ElasticSearch）
  - Elemental MediaConvert
- Terraform
- AWS CDK
- Docker
- Kubernetes
- fluent-bit

### 開発手法
- ウォーターフォール
- アジャイル
  - スクラム

### 開発ツール
- Git
- GitHub
- Postman
- Gatling
- Locust
- VSCode

### その他ツール
- Slack
- Notion
- Backlog
- Asana
- Jira
- Confluence
- Google Workspace
- Microsoft Excel

### 資格
- AWS クラウドプラクティショナー（2023年11月）
- AWS システムアーキテクト アソシエイト（2024年2月）
- 基本情報技術者試験（2018年5月）
- 日商簿記2級（2013年2月）

### 自然言語
- 日本語
  - ネイティブ
- 英語
  - TOEIC-IP: 770点（2015年11月）
  - 英検2級
  - CEFR B2

### その他
- DTM（作曲）
  - ボーカロイド楽曲の最高再生数は14000（ニコニコ動画）

## 強み
- 新規技術の習得に抵抗がない

会社の特性上、言語もOSも異なるプロジェクトに移動することが多いが、それが初見だったとしても人より早く慣れることができる。

- 要件のキャッチアップが早い

業務システムのような複雑な要件のシステムの開発に慣れている。


## 職務経歴
↑新
↓古


### 2022/02 - : フィグニー株式会社
サーバーサイドエンジニアとして入社。

---
#### 2024/12 - 2025/05 : 人事評価システムリプレース
- Python
  - FastAPI
  - SQLAlchemy
- AWS
  - AppRunner
  - Lambda
  - SES
  - CDK
  - Route53
- Supabase

すでにサポートが終了しているPHP7系からのリプレース。  
セキュリティ、可用性の向上や、デザインのブラッシュアップが狙い。  
インフラ、サーバーサイド、現システムからのデータ移行を担当した。  
実装フェーズ後半からの参画で、前任者がほとんどドキュメントを残していなかったので、仕様の把握に時間を要した。

---
#### 2024/10 - 2024/12 : 求人メディアサイト新規開発
- Next.js
- Refine
- Vercel
- Supabase
- Resend

インタビュー形式の記事を掲載できる求人メディアサイトの新規開発。  
主にインフラ、管理画面の実装（Refine）を担当した。  
サーバーサイドAPIがなく、クライアントからSupabaseのAPIに直アクセスするアーキテクチャなので、SupabaseのRLSでセキュリティを担保する必要があったのが難しかった。  


---
#### 2024/04 - 2024/09 : 動画SNS新規開発
- Python
- AWS CDK (TypeScript)
- AWS
  - AppSync
  - Lambda
  - RDS Aurora Serverless
  - Elemental MediaConvert
  - Cognito
    - Apple, Googleログイン連携
  - S3
  - EventBridge
  - SNS
  - Route53
  - Certificate Manager

ある県の10代〜20代をターゲットにした動画SNSの新規開発。  
AWS AppSyncを利用したGraphQL APIを中心とした、サーバーサイド、インフラの全てを一人で担当した。  
AppSync、CDKなど、初めて触るものが多かったが、無事スケジュール通りに納品できた。  
前の案件での学びを活かして、非機能の部分まで考慮した設計、実装ができたと感じている。


---
#### 2023/05 - 2024/04 : 通信会社向けAPIゲートウェイ保守・スマートシティ対応
- Go
- Python
- Shell
- AWS
  - ECS
  - EC2
  - ALB
  - WAF
  - VPC
  - S3
  - EFS
  - DocumentDB
  - ElastiCache
  - CloudWatch
  - EventBridge
  - StepFunction
  - CodeBuild
  - Lambda
  - API Gateway
  - Athena
  - Kinesis Data Firehose
  - OpenSearch（ElasticSearch）
- Terraform
- Docker
- Kubernetes
- fluent-bit
- Gatling
- アジャイル
  - スクラム

社内向けのAPIを取りまとめて認証・認可、流量制限等を行うリバースプロキシ。  
保守・運用改善とスマートシティ対応のフェーズ。  
スクラムチームの開発メンバーとして、コード修正、インフラ修正など、設計以降の業務を幅広く対応した。  
月間数十億リクエストあり、低遅延、低負荷、低コストを意識した設計が必要とされた。  


---
#### 2022/07 - 2023/04 : リフォーム会社向け業務システム開発
- Rust
  - Actix-web
  - Diesel
- AWS
  - ECS
  - Fargate
  - RDS
  - Site-to-Site VPN
- Docker
- ウォーターフォール

レガシーな業務アプリの刷新。サーバーサイドのAPI、バッチ、インフラを担当。  
AS400+グループウェア+Excelの現行システムをモダンなWebアプリに落とし込んだ。


---
#### 2022/02 - 2022/06 : 建設業界向けチャットアプリ開発
- Python
  - Django REST Framework
- AWS
  - ECS
  - Fargate
  - RDS
  - SES
  - MediaConvert
- ウォーターフォール

チャットアプリの新規開発。サーバーサイドのAPI、インフラを担当。

---
### 2017/04 - 2021/12 : 株式会社エイエイエスティ
新卒で入社し、2021年12月に退職。

---
#### 2021/07 - 2021/12 : 電力会社向け工事管理システム機能追加
- Red Hat Enterprise Linux
- C#.NET
- Oracle 12c

Webシステムの機能追加。
バックエンドの設計、コーディングを担当。

---
#### 2020/10 - 2021/06 : 電力会社向けサーバーリプレース
- HP-UX
- VB.NET
- Oracle 12c
- ShellScript

HP-UXサーバーのリプレースと、それに伴うWindowsアプリケーションのコンバージョン（VB6→VB.NET）のプロジェクト。  
Windowsアプリおよびそこから呼び出されるPL/SQL、ShellScriptのテスト・デバッグや、  
サーバー移行作業（ShellScriptでのツール作成を含む）を担当。

---
#### 2020/06 - 2020/09 : 電力会社向けRESTfulAPI開発
- Azure
- C#.NET
- Azure CosmosDB

スマホアプリの認証基盤APIの開発。  
設計（MarkDown）、コーディング・ユニットテスト（C#）、結合・システムテスト（JMeterを利用した負荷テスト含む）を担当。

---
#### 2020/01 - 2020/03 : 工場向けIoTシステムバッチ開発
- C#.NET
- SQL Server

IoTを利用した工場の生産性向上のためのパッケージ製品（の一部品）の開発。  
設計、コーディング・ユニットテスト（C#）、結合テストを担当。

---
#### 2019/04 - 2019/12 : 電力会社向け工事管理システム再開発
- Java（独自フレームワーク）
- Oracle

工事管理システムの深夜バッチの再開発（COBOL→Java）。  
結合テスト・デバッグを担当。  
大規模なシステムで単体テストレベルのバグが多く、バグ修正の作業量が多かったが、おかげで初見のコードを読み解く力がついた。

---
#### 2018/02 - 2019/03 : 電力会社向け電柱管理システム機能追加
- C#.NET, TypeScript
- SQL Server

Google Maps APIを用いたWebアプリの保守、機能追加。  
アジャイルのような進め方で、コミュニケーションの正確性が求められた。

---
#### 2017/08 - 2018/01 : 自動車メーカー向けサーバーリプレース
- Red Hat Enterprise Linux
- Oracle

Linuxサーバーのリプレース。  
exp/impツール、Oracle GoldenGateを使用したDB移行を担当。

---
#### 2017/06 - 2017/07 : 住宅メーカー向けカスタマイズ回答事例公開システム
- VB.NET
- SQL Server

Webアプリの開発。
コーディングを担当。

## 課外活動

### 個人開発
- げんログ(2020/05リリース、公開停止済み)

  弦楽器の弦交換の履歴が管理できるWebアプリ。  
  言語はPHP, フレームワークはLaravelを使用。
- Bottletter(2021/06リリース、公開停止済み)

  ボトルメールをモチーフとしたシンプルなSNS。
  言語はRuby(3系), フレームワークはRails(6系)を使用。

