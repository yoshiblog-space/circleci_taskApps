# circleci_taskApps

# 開発環境の立ち上げ

1.イメージの作成

```
docker-compose build
```

2.コンテナを起動する

```
docker-compose up -d
```

## TodoAppsの起動
*開発環境が立ち上がっている必要があります。

```
docker-compose exec app npm run serve
```

起動ポート：4000
