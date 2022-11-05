# 初期設定

## 環境
Node.js: 16.17.1<br>
npm: 8.15.0

## 新規で作成する場合
1. 「npm i」でモジュールをインストール<br>
1. 「npx clasp create --title <プロジェクト名> --rootDir ./src」で standalone を選び、【.clasp.json】【appscript.json】を作成<br>
1. 【appscript.json】内 "timeZone" の値を "Asia/Tokyo" に変更<br>
1. 【.clasp.json】を ルートディレクトリに移動

## 既存の Google Apps Script ファイル(スプレッドシート接続済) を使用する場合
1. 「npm i」でモジュールをインストール<br>
1. 「npx clasp clone --rootDir ./src <スクリプトID>」で src ディレクトリに【**.js】【.clasp.json】【appscript.json】をクローン<br>
1. 【appscript.json】内 "timeZone" の値を "Asia/Tokyo" に変更<br>
1. 【.clasp.json】を ルートディレクトリに移動