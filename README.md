# リポジトリについて
laravel8、vue3、interiajs、typescriptを利用する際のテンプレート

# パッケージとバージョン
laravel8  
jetstream(interiajs) (2.4)  
laravel-mix (6.x)  
vue3  
typescript  
Docker  
Dcker Compose  

nginx 1.19  
php 7.4.1  
composer 2.0.x  
nodejs 16.x  
npm 8.x  
mysql 8.0  

# 起動方法
プロジェクトディレクトリ直下でやること。  
コマンドではdockerのCLIプラグインとしてDocker Composeを利用している。  
docker-composeでも動作は確認しているが、保証はしない。  
起動後はlocalhost:80へアクセスで見れる。  

docker imageの作成

```
docker compose build
```

コンテナ群の立ち上げ

```
docker compose up -d
```

appコンテナへ入る

```
docker compose exec app bash
```
