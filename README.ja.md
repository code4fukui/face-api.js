# face-api.js

**ブラウザ上で動作する JavaScript の顔認識 API**

## デモ
[こちらのデモページ](https://justadudewhohacks.github.io/face-api.js/)でfaceapi.jsの機能を体験できます。

## 機能
- 顔検出
- 顔ランドマーク検出
- 顔認証
- 表情認識
- 年齢推定と性別推定

## 使い方
npmからインストールできます:

```bash
npm i face-api.js
```

ブラウザで使用する場合は、distフォルダのface-api.jsを読み込むだけです。
Nodejsで使用する場合は、いくつかのブラウザ向けライブラリをpolyfillする必要があります。

モデルのダウンロードと読み込みが必要です。モデルは[こちら](https://github.com/justadudewhohacks/face-api.js/tree/master/weights)から入手できます。

## ライセンス
MITライセンス