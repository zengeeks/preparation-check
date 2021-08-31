# 環境チェック用リポジトリ

このリポジトリは、ワークショップに参加する際に必要な環境を確認するためのリポジトリです。

## ワークショップに必要な準備

ご案内したワークショップの要件に応じて、下記をご準備ください。

### パターンA: GitHub を利用するワークショップ

- [GitHub アカウント](#github-アカウント)

### パターンB: Git を利用するワークショップ

当日利用する環境で、下記をご用意ください。

- [Git のインストール](#git-のインストール)

### パターンC: Microsoft Learn を利用するワークショップ

- [Microsoft アカウント](#microsoft-アカウント)

### パターンD: Microsoft Azure を利用するワークショップ

- [Azure アカウント](#azure-アカウント)

### パターンE: Terraform および Microsoft Azure を利用するワークショップ

当日利用する環境で、下記をご用意ください。

- [Git のインストール](#git-のインストール)
- [Terraform CLI のインストール](#terraform-cli-のインストール)
- [Azure CLI のインストール](#azure-cli-のインストール)

### パターンF: Jamstack を学ぶワークショップ

当日利用する環境で、下記をご用意ください。

- [Git のインストール](#git-のインストール)
- [Visual Studio Code のインストール](#visual-studio-code-のインストール)
- [Node.js のインストール](#nodejs-のインストール)

## 準備の手順

### GitHub アカウント

GitHub を利用する場合は、GitHub アカウントが必要です。また、ワークショップで GitHub Learning Lab を利用する場合も GitHub アカウントが必要になります。

新しく作成する方は [こちら](https://github.com/join) から作成してください。

### Microsoft アカウント

ワークショップで Microsoft Learn による学習を行う場合、学習結果を記録するには、Microsoft アカウントをご用意ください。

新しく作成される方は [こちら](https://account.microsoft.com/account/Account) から作成してください。

### Azure アカウント

Microsoft Azure へのデプロイを体験する場合は、Azure アカウントをご用意ください。

新しく作成する方は [こちら](https://azure.microsoft.com/ja-jp/free/) から作成してください。

### Git のインストール

Git の操作を実際に体験いただくワークショップで利用します。

[Git のダウンロードページ](https://git-scm.com/downloads)より、お使いの環境に合わせてインストールしてください。

Git が正しくインストールできたか確認するには、任意のシェルで `git --version` などのコマンドを実行し、エラーが出ないことをご確認ください。

```bash
git --version

git version 2.32.0.windows.2
...
```

### Visual Studio Code のインストール

Visual Studio Code をインストールするには、[Download Visual Studio Code - Mac, Linux, Windows](https://code.visualstudio.com/Download) を参考にご用意ください。

### Node.js のインストール



### Terraform CLI のインストール

Terraform CLI をインストールするには、[Install Terraform | Terraform - HashiCorp Learn](https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/azure-get-started) を参考にご用意ください。

Terraform CLI が正しくインストールできたか確認するには、任意のシェルで `terraform -v` などのコマンドを実行し、エラーが出ないことをご確認ください。

```bash
terraform -v

Terraform v1.0.5
...
```

### Azure CLI のインストール

Azure CLI をインストールするには、[Azure CLI をインストールする方法 | Microsoft Docs](https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli) を参考にご用意ください。

Azure CLI が正しくインストールできたか確認するには、任意のシェルで `az --version` などのコマンドを実行し、エラーが出ないことをご確認ください。

```bash
az --version

azure-cli                         2.27.2
...
```