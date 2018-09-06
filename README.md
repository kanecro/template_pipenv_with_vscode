# pipenv + Visual Studio Code 開発のプロジェクトテンプレート

lintはflake8 + 各種プラグイン を使います。

pipenvでインストールするライブラリは `.venv` ディレクトリ配下に格納します。

## 事前準備

```shell
export PIPENV_VENV_IN_PROJECT=1
```

## 環境構築

```shell
git clone git@github.com:kanecro/template_pipenv_with_vscode.git
pipenv install -d
```
