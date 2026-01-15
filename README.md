# ゆれどろーるど(yuredrold)

スマートフォンなどに搭載されている加速度センサの値をバックグラウンドで取得して送りつける

## これはなに

[m-tsuru/yuredroid](github.com/m-tsuru/yuredroid) をSDKVersion 24(Android 7)に対応させたフォークです。  
GPT-5 miniによって改変されました。  
リニア加速度センサを使用します。無ければ加速度センサで代用します~~が、正常に動作しません。~~ →リニア化して表示するようになったため、正常に動作します  
また、このフォークはupstreamに大きな変更が無い限り変更がありません。  
古いAndroid向けのアプリケーションです。新しいOSを使用している場合、本家を使用するとよいでしょう。  

## つかいかた
### リニア加速度センサがある場合
1. [Releases](https://github.com/SHINTRANET-Lab/yuredrold/releases) から最新の無印版 apk ファイルをダウンロードする

2. アプリの中央の `Start` ボタンを押下する
### リニア加速度センサがない場合
1. [Releases](https://github.com/SHINTRANET-Lab/yuredrold/releases) から最新のLinear版 apk ファイルをダウンロードする

2. アプリの中央の `Start` ボタンを押下する
## 動作確認済み端末
- SONY Experia Z5(SO-01H) Android 7
- STS-TOTTORI チャレンジタッチ3(TAB-A03-BR3) Android 7 ##Linear版のみ動作
- Nothing Phone(2a) Plus(A142P) Android 16
## ライセンス

©️ 2026 Michiru Tsurumaru / KusaReMKN / Taiga Takatani (Modified) / MIT License
