# MySQL Docker コンテナを立ち上げる

## Requirement

- Docker 最新

## 導入手順

1. .envを作成

```shell
# 雛形をコピーして作成
cp .env.example .env

# .envファイルを開き、シークレット情報を更新する(パスワードは複雑なものに更新すること!)
vi .env
```

2. 立ち上げる

```shell
docker compose up -d
```

3. データストア

seedsディレクトリに準備データがあるのでそれを使ってスキーマを構成する

