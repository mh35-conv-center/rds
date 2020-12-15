# DBスタック定義

## 基本的な説明

このレポジトリは、DBをデプロイするためのテンプレートを定義したものです。使うのはAurora MySQLです。

## コスト管理タグ

このレポジトリでは、CostTagをコスト管理タグとして用いるために使います。変数名CostTagNameでそのタグ名を指定します。指定しなかった場合、スタック名を用います。

## 依存関係

このスタックは、先にVPCスタックをデプロイしておく必要があります。