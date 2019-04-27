# `Kibana`-`Elasticsearch`-`Docker`

## 概要

Kibana + Elasticsearch を Docker で起動する。  
過去に取得していたログをグラフィカルに参照できることを目的にするため、Elasticsearch へのデータ投入は、 `Embulk` を使用する。  
Embulk は Fluentd のバッチ版とも呼ばれ、 Fluentd がリアルタイムにデータを収集することを得意とすることに対し、 Embluk は溜め込んだデータを取り込むことを得意とする。

## 環境 
2019/05/01時点
* Kibana 7.0
* Elasticsearch 7.0
* Docker 18.09.2
* Docker Compose 1.23.2  
* Embulk x.x

<img width="648" alt="スクリーンショット 2019-04-28 1 00 08" src="https://user-images.githubusercontent.com/8340629/56852071-5e7c9080-6951-11e9-98f9-17bd0333430e.png">

## 前提

* macOS Mojave 10.14.4 
* Docker for mac がインストールされていること



## Kibana + Elasticsearch をインストール
docker-compose で起動する。

## Embulk を インストール

## サンプルログを取り込む

## 動作確認
