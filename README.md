MariaDB インストール
===
## 概要
MariaDBのインストールと起動(enable)を行う  
1. MariaDBインストール
1. 文字コードとstrictの設定
1. MariaDB再起動 & enable設定

## 動作確認済み環境
CentOS 7.6.1810

## 変数
```
innodb_strict_mode    # テーブルの追加のエラー検査を行うか  
character_set_server  # サーバのデフォルト文字コード  
default_character_set # クラウイアンのデフォルト文字コード  
```

## 依存関係
なし