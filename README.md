cors_sample
===========

# 概要

ブラウザからS3へ  
直接ファイルをアップロードするサンプルプログラム。  
CORS




# 使い方

## 1.S3へ設定

`src/CORS_CONFIG.xml`をS3に設定する。  
https://console.aws.amazon.com/s3/home
から行う。

## 2.webサーバにアップロード画面設置

`src/www/`をwebサーバ上に設置.  
S3のキーなどは個々に指定すること。


# 参考

http://dev.classmethod.jp/cloud/cors-cross-origin-resource-sharing-cross-domain/