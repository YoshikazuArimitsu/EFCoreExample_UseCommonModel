# EntityFramework Core モデル共有サンプル モデル仕様側

## 概要

  git submodule 機能を使用し、[EFCoreExample_CommonModel](https://github.com/YoshikazuArimitsu/EFCoreExample_CommonModel) リポジトリを取り込む。

  UseCommonModel プロジェクトでサブモジュールの CommonModelLib プロジェクト参照を設定し、CommonModelLib 内で定義されているモデル・DBコンテキストを使用する事ができる。

## git submodule 機能について

外部リポジトリの特定コミットをリポジトリ内に取り込む機能。

[Git submodule の基礎](https://qiita.com/sotarok/items/0d525e568a6088f6f6bb)
