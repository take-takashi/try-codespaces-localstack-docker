# try-codespaces-localstack-docker
dockerfileを使ったCodespaces+localstackを試してみる

## 試したこと

- まずはCodespacesでDocker-composeを動かせるように、  
  サンプルの設定を漁ってみる。

- コマンドパレットから`python 3 & postgreSQL`の定義済みのcodespaces設定を適用してみた。
- クエリで以下の実施
  ```
  create table public.aaa (
    id integer
  );
  ```
  テーブルが作られたが、永続ではない？