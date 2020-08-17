# InputTester
<p>htmlコードをテストできるhtmlページです。</p>
<p>
左の「入力」枠にHTMLコードを入力してボタンを押すと、右の「結果」枠に反映してくれます。<br>
結果は、入力枠のどのボタンを押すかで変わります。
</p>
<hr>
<dl>
  <dt>HTML出力</dt>
  <dd>HTMLコードを入力するとそのまま反映されます。</dd>
  <dt>TEXT出力</dt>
  <dd>htmlタグ等を反映せず、そのまま表示してくれます。意味があるかは疑問。</dd>
  <dt>初期化</dt>
  <dd>文字通りの意味です。「結果」枠と「入力」枠の中身を削除します。</dd>
  <dt>縦書き</dt>
  <dd>
    入力した文字列を縦書きにしてくれます。<br>
    なるべく正方形になるよう調節して縦書きの文字列を生成します。<br>
    本当に縦に並べるだけなのでローマ字は不向きです。<br>
    改行も非対応のため改行を削除して一行の文字列として処理しています。今後の更新課題です。
  </dd>
</dl>
<hr>
<p>「結果」枠右下のボタンを押すと、クリップボードに内容をコピーしてくれます。</p>
<p>
　コピーボタンではHTMLコードをそのまま取得します。<br>
　プレインでは、タグなど一部の文字列を特殊文字にエスケープして取得します。
</p>
<hr>
<p>
  一応、フレキシブル対応してますのでスマートフォンでも使えるかもしれません。
  試していないためおススメはできませんが...
</p>
