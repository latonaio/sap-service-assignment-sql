# sap-service-assignment-sql

sap-service-assignment-sql は、主にエッジアプリケーションにおいて、SAPと連携されたサービス割当データを保存するSQLテーブルを作成するためのレポジトリです。  
sap-service-assignment-sql は、そのままクラウド環境におけるアプリケーションにも、適用可能です。  

## 前提条件  
sap-service-assignment-sql は、SQL の SAP とのデータ連携にあたり、オンプレミス版である（＝クラウド版ではない）SAPC4HANA API の利用を前提としています。  
クラウド版APIを利用する場合は、ご注意ください。  
https://api.sap.com/api/Assignment/overview  
本レポジトリ の sql設定ファイルの内容は、上記URL の API 仕様を前提としています。  

## sqlの設定ファイル

sap-service-assignment-sql には、sqlの設定ファイルとして、以下のファイルが含まれています。  

* sap-service-assignment-sql-service-assignment-collection-data.sql（SAP サービス割当 - サービス割当データ）  
  

## MySQLのセットアップ / Kubernetesの設定 / SQLテーブルの作成方法  

MySQLのセットアップ / Kubernetesの設定 / 具体的なSQLテーブルの作成方法、については、[mysql-kube](https://github.com/latonaio/mysql-kube)を参照ください。  