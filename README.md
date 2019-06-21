# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

小さなWindowsで「こんにちわ」と言う表示画面が出てきて、閉じるを押すと元の画面に戻ると言う変化があった。

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

参照エラー：定義されていません

## Chromeデベロッパーツール：Consoleの実行結果

```
Failed to load resource: net::ERR_FAILED
const prefList = ["北海道"]
undefined
const prefList = ["北海道","青森"];
VM482:1 Uncaught SyntaxError: Identifier 'prefList' has already been declared
    at <anonymous>:1:1
for (let i = 1; i = <= 5 ; i++){
VM592:1 Uncaught SyntaxError: Unexpected token <=
for (let i = 1; i = <= 5 ; i++)
VM614:1 Uncaught SyntaxError: Unexpected token <=
const number = 1;
undefined
for (let i = 1; i = <= 5 ; i++){
VM737:1 Uncaught SyntaxError: Unexpected token <=
for (let i = 1; i = <= 5 ; i++){ comsole.log(i);}
VM787:1 Uncaught SyntaxError: Unexpected token <=
﻿
​

```

## ターミナルの実行結果

```
Last login: Fri Jun 21 08:55:55 on console
JinnoMacBook-Pro:~ jinmizou$ cd ~/fujiwara
JinnoMacBook-Pro:fujiwara jinmizou$ git clone git@github.com:jin112343/learning-javascript-01.git
Cloning into 'learning-javascript-01'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.
JinnoMacBook-Pro:fujiwara jinmizou$ cd learning-javascript-01
JinnoMacBook-Pro:learning-javascript-01 jinmizou$ code .
JinnoMacBook-Pro:learning-javascript-01 jinmizou$ node node-main.js
/Users/jinmizou/Documents/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/jinmizou/Documents/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
JinnoMacBook-Pro:learning-javascript-01 jinmizou$ node node-main.js
Goodmorning, Node.js!!
JinnoMacBook-Pro:learning-javascript-01 jinmizou$ 






```

