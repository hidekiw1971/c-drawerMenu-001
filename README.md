# compornent（共通部品）

## 概要

- JavaScript を使用せず、CSS だけでハンバーガーメニューを実装してます。

## 仕様

-　<input type="checkbox" id="menu-btn-check">を使用して実装。

## 注意事項

- reset.scss の以下の部分を修正しないと input の checkbox が表示されません。
- /_ フォームリセット _/
  input,
  button,
  select,
  textarea {
  // -webkit-appearance: none; -> コメントにする
  -moz-appearance: none;
  // appearance: none; -> コメントにする
  background: transparent;
  border: none;
  border-radius: 0;
  font: inherit;
  outline: none;
  }
- input[type="checkbox"],
  input[type="radio"] {
  // display: none; -> コメントにする
  display: block; -> none -> block に変更する
  }

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## イメージ画像

- xxx

## portfolio url:

- https://css-md-0017.wtb.cfbx.jp/

## 参考にしたサイト

- JavaScript 不要！CSS だけでハンバーガーメニューを実装する方法
- https://www.asobou.co.jp/blog/web/css-menu
- chromeでチェックボックスが表示されない
- https://concrete5-japan.org/community/forums/chat/post-9722/

## 更新履歴

- 2022/3/7 初版 作成中(三本線まで完成)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
