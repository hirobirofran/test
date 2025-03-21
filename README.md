# test
テストん

参照した資料  

Nest.jsとは─軽量JavaScriptフレームワークの基本を解説 https://kinsta.com/jp/knowledgebase/nestjs/

# 補足
## mongoDB
```
解決方法
1. MongoDB サーバーが起動しているか確認
ローカルまたは Codespaces 上で MongoDB サーバーが起動しているか確認します。

ローカル環境の場合:

サーバーが停止している場合は、以下のコマンドで起動します:
sudo systemctl start mongod
Codespaces 環境の場合: Codespaces では MongoDB がデフォルトでインストールされていないため、Docker を使用して MongoDB をセットアップする必要があります。

2. Docker を使用して MongoDB を起動（Codespacesの場合）
Codespaces 上で MongoDB を使用するには、Docker コンテナを起動します。

Docker がインストールされていることを確認:

docker --version
MongoDB コンテナを起動:

MongoDB コンテナが起動していることを確認:

mongo コンテナがリストに表示されていれば、MongoDB が起動しています。
```
