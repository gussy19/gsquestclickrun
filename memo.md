## 参考

上昇または下降速度Vnewは下記式で計算
(式) Vnew = Vold + 重力加速度 * 単位時間

# 参考

■ canvasのgetContext("2d")って何
https://qiita.com/manten120/items/86c087b937708697acec

// canvas要素を取得
const canvas = document.getElementById('canvas');

// canvas要素が持つgetContext()メソッドを実行し、
// グラフィック描画のためのメソッドやプロパティを
// 持つオブジェクトを取得する。
// 引数を"2d"とすることで2Dグラフィックの描画に
// 特化したメソッドやプロパティを持つオブジェクトを取得し、
// 定数ctxに格納する。
const ctx = canvas.getContext("2d");
// 定数ctxに格納したオブジェクトがもつプロパティやメソッドは
// ctx.プロパティ名、ctx.メソッド名() で呼び出せる

// 描画する色を指定するプロパティflillStyle
ctx.fillStyle = 'black';

// 四角形を描画するメソッドfillRect()
ctx.fillRect(15, 10, 150, 100);


■ Firefoxのcanvas上でフォントの斜体(italic)が効かないなら斜めにして書けばいいじゃない
https://qiita.com/tyoukan__/items/58ac289c89e98c11d7dc

■ clearInterval()
https://developer.mozilla.org/ja/docs/Web/API/clearInterval
以前に setInterval() の呼び出しによって確立されたタイマーを利用した繰り返し動作を取り消します。

■【JavaScript】 addEventListener()の第三引数useCaptureの謎
https://note.affi-sapo-sv.com/js-addeventlistener-usecapture.php

■ .pageX
https://js.studio-kingdom.com/javascript/event/page_x
ドキュメント全体の相対的なイベント発生場所の水平位置を返します。

■ data()
HTML要素内に付与されたdata属性に対して、取得・設定・変更などが簡単に行える