リポジトリの作成手順

repogen -p packages repo

Offline インストーラの作成手順

binarycreator --offline-only -c config/config.xml -p packages installer_offline


Online インストーラの作成手順

binarycreator --online-only -c config/config.xml -p packages installer_online


参考

リポジトリの一部のフォルダだけをアップするには、以下を実行。

repogen -p packages --update --include (更新するパッケージ) repo

