「[ちいさな Web ブラウザを作ってみよう](https://browserbook.shift-js.info/)」 の学習に使ったサンプルコード

## memo

* HTMLの解析→DOMの構築
    * HTML文字列から、DOMを表すNodeオブジェクト作成
* CSSの解析→CSSOMの構築
    * CSS文字列から、CSSOMを表すStylesheetオブジェクト作成
* レンダーツリーの構築
    * Nodeオブジェクト&Stylesheetオブジェクトから、StyledNodeを作成
        * StylesheetにRule作成/macher関数: Nodeを渡してマッチするか確認
        * StylesheetのRuleにNodeが一致するかみていく
* レンダリング
    * レイアウト処理
    * ペイント処理

※ レイアウト処理とペイント処理については演習なし