# *Node.js*

## 概要

Nodeはスケーラブルなネットワークアプリケーションを構築するために設計された非同期型のイベント駆動のJavaScript環境

* JSのプラットフォームであって、フレームワークでもライブラリでもない
* サーバーサイトで実行されるJS
* 非同期、ノンブロッキングI/O、chromeのJSエンジンv8で動作


## パッケージマネージャー

### パッケージとは

処理やプログラムの部品をひとまとめにしたもの

### パッケージマネージャーとは

パッケージのインストールや削除などの管理をしやすくしたもの

* Homebrew
  - macOS用Node.jsパッケージマネージャー
* npm
  - Node Package Manager
  - `package.json`にパッケージの依存関係を書き、`node_modules`にパッケージをインストール
* yarn
  - 2016年にFacebookが発表したパッケージマネージャー
  - `package.json`にパッケージの依存関係を書き、`node_modules`にパッケージをインストールすること自体はnpmと変わりなし。
  - npmとの違いは、packageの並列インストールと出力の簡素化

### Node.jsのバージョン管理システム

Node.jsのバージョンは日々アップデートしており、バージョンに依存するパッケージも大量に。  
Node.jsのバージョンを簡単に切り替えることのできるバージョン管理システムが必要。

#### nvm

Node Version Manager  
スター数やコミッターが一番多いNode.jsのバージョン管理システム。

#### 

## 現状

### バージョン管理

nodebrew

### 最新版のstable version install

nodebrew install-binary stable

### version 切り替え

#### インストールされているバージョンの確認

nodebrew ls

#### バージョン切り替え

nodebrew use v12.1.0