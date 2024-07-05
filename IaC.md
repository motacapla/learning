# Infrastructure as Code (IaC)
> Infrastructure as Code (IaC) とは、手動のプロセスや設定の代わりに、コードを使用してインフラストラクチャの管理とプロビジョニングを行うことを言います。インフラの構成や設定をコード化するため、手動設定によるエラーを減らし、一貫性を確保できます。
source: https://www.redhat.com/ja/topics/automation/what-is-infrastructure-as-code-iac

# 著名なIaCツール
ツールによって構成管理可能なリソースや言語が異なる。
## Terraform
https://www.terraform.io/
モジュールの再利用が可能。
結合テストのみサポート。
### 言語
HCL (独自言語)

## Pulumi
https://www.pulumi.com/
### リソース定義
関数、クラス、パッケージなどの再利用が可能。
一般的なテストフレームワークをサポート。

### 言語
汎用言語（Python, TypeScript, Goなど）

## AWS Cloud Formation
### リソース定義
AWSリソース全般。

### 言語

### CDKとCloudFormationの関係性
> ご存知のように、CDK は TypeScript や Python など一般の言語で AWS の環境を定義できるツールセットです。
> そして、その実体は CloudFormation のテンプレートを生成するテンプレートエンジンです。デプロイメントはあくまで CloudFormation が行う。そして CDK はあくまで CFn テンプレートを書きやすくするためのツールであると割り切ってしまうと、悩むことが少なくなります。
https://qiita.com/yktko/items/7bcc9df940194ee62d8c

## Ansible
https://www.ansible.com/

## Chef
https://www.chef.io/


# AWS CDK
## disable rollback
https://qiita.com/yktko/items/7bcc9df940194ee62d8c#disable-rollback

## hotswap
https://qiita.com/yktko/items/7bcc9df940194ee62d8c#hotswap

