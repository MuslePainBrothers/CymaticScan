# CymaticScanApp
## 概要
性格診断メーカー

## 機能
* 幾つかの質問に答えて、ユーザの性格を診断する.
* 質問から評価値を計算して,診断結果をユーザに伝える.

## 開発環境
* 言語 python
* フレームワーク django
* python 3.6.3

## 準備
1. pip install

```
pip install -r requirements.txt
```
2. consumer.txt の配置
``` 
{'consumer_key': '*****', 'consumer_secret': '*****'}
```

と記述した`consumer.txt`を`CymaticScanApp/setting.py`と同じ階層におく。

## 起動
```
python manage.py runserver 0.0.0.0:8080
```

## 管理サイト

http://0.0.0.0:8080/admin/
* user: admin
* password:adminadmin

## 画面
* トップ画面
![top.jpeg](https://raw.githubusercontent.com/MuslePainBrothers/CymaticScanApp/develop/screen_shot/top.jpeg)

* 質問画面
![question.jpeg](https://raw.githubusercontent.com/MuslePainBrothers/CymaticScanApp/develop/screen_shot/question.jpeg)

* 結果画面
![result.jpeg](https://raw.githubusercontent.com/MuslePainBrothers/CymaticScanApp/develop/screen_shot/result.jpeg)
