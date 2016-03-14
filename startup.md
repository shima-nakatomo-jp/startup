# 目次
1 Burp Suite 概要

 1.1 Burp Suiteとは

 1.2 特徴

 1.3 診断プロセス

2 インストール手順

 2.1 Windows版インストール手順

  2.1.1 Java実行環境の準備

  2.1.2 Burp Suiteのダウンロード

3 初回起動、使用準備

 3.1 初回起動

 3.2 Burp Suiteのアップデート

 3.3 Burp Suiteの設定

 3.4 ブラウザ（インターネットエクスプローラ）の設定

4 診断方法について

 4.1 画面構成

 4.2 Burp Suiteによる通信のキャプチャ

 4.3 その他

  4.3.1 Proxyインターセプトの使い方、Http history

  4.3.2 リクエストの再送信

  4.3.3 Scope設定

  4.3.4 サーバ証明書設定

  4.3.5 ログ保存設定

  4.3.6 アップストリームProxy設定

  4.3.7 Intruder

---

1 Burp Suite 概要
 1.1 Burp Suiteとは

 Burp SuiteはPortSwigger 社が作成したJava製のローカルProxyソフトです。ローカルProxyとは、会社や学校などで使用されているProxyとは異なり、Webアプリケーションのセキュリティ診断やデバックなどに活用されます。Burp SuiteはWebアプリケーションのセキュリティ診断に特化したツールで、Burp Suite以外にもOWASP ZAPやFiddlerなどが存在しています。

Burp Suite　 [http://portswigger.net/](http://portswigger.net/)

![Burp Suite](./img/logo.png "Burp Suite")

 1.2 特徴

Burp Suiteは、有償版（Professional Edition）と無償版（Free Edition）の2種類あります。最新バージョンは、無償版v1.6.32で、有償版v1.6.39です（2016年3月8日時点）。

Burp Suiteは以下の機能で構成されており、有償版でしか利用できない機能もあります。

- Target
	一部有償機能で、対象サイトの詳細情報を収集するsite mapやターゲットとなるスコープを設定する。

- Proxy

- Spider
- Scanner
- Intruder
- Repeater
- Sequencer
- Decoder
- Comparer
- Extender
- Options
- Alerts
- その他


 1.3 診断プロセス
 
2 インストール手順
 2.1 Windows版インストール手順
  2.1.1 Java実行環境の準備
  
  2.1.2 Burp Suiteのダウンロード

3 初回起動、使用準備
 3.1 初回起動
起動方法について記載。Excute形式のJARファイルをたたくだけでなく、コマンドラインについても。

 3.2 Burp Suiteのアップデート
起動時にアップデートされることについて記載。

 3.3 Burp Suiteの設定
Proxy設定。待ち受けアドレスやポートなどについて。

 3.4 ブラウザ（インターネットエクスプローラ）の設定
ブラウザのProxy設定

4 診断方法について
 4.1 画面構成
Proxyタブがどういう構成なのか。

 4.2 Burp Suiteによる通信のキャプチャ
インターセプト設定。

 4.3 その他
  4.3.1 Proxyインターセプトの使い方、Http history
4.2とかぶる？Http historyのみでいい？

  4.3.2 リクエストの再送信
Repeaterの使い方

  4.3.3 Scope設定
スコープ設定の必要性も。

  4.3.4 サーバ証明書設定
サーバ証明書、インポートしないとエラー表示されることについても。

  4.3.5 ログ保存設定
Loggingについて。Free edition前提なので。

  4.3.6 アップストリームProxy設定
なぜアップストリームを使うのかも含めて。

  4.3.7 Intruder
一番ベーシックな使い方。結果の見方も。Grep matchいれたい。