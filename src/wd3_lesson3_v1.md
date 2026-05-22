# ウェブデザイン技能検定3級 第3回 v1

## テーマ
CSSで箱を理解する

## 正式構成
- 本問20問
- 実技5問
- 復習5問
- 応用5問
- 知識5問
- 宿題：復習10問 / アレンジ5問 / 知識5問

---

# ■ 本問 20問

---

## Q01
枠線を表示するCSSプロパティはどれか

【A】 `line`  
【B】 `frame`  
【C】 `border`  
【D】 `flex`  

⭕ 正解【C】

解説  
`border` は要素の枠線を指定するCSSプロパティです。太さ、線の種類、色をまとめて指定できます。

👉 よくあるミス  
`line` や `frame` はそれっぽく見えますが、CSSで枠線を指定する正式なプロパティは `border` です。

■ ポイント  
border = 箱の枠線。授業では「どこまでが箱か」を見えるようにするためにも使います。

---

## Q02
背景色を指定するCSSプロパティはどれか

【A】 `background-color`  
【B】 `text-color`  
【C】 `box-color`  
【D】 `color-background`  

⭕ 正解【A】

解説  
`background-color` は要素の背景色を指定するCSSプロパティです。

👉 よくあるミス  
文字色を指定する `color` と混同しやすい。

■ ポイント  
background-color = 背景色。color = 文字色。

---

## Q03
要素の角を丸くするCSSプロパティはどれか

【A】 `corner`  
【B】 `round-border`  
【C】 `border-round`  
【D】 `border-radius`  

⭕ 正解【D】

解説  
`border-radius` は要素の角を丸くするCSSプロパティです。ボタンやカードの角丸によく使います。

👉 よくあるミス  
`border` と同じく枠線そのものを指定するものだと思ってしまう。

■ ポイント  
radius = 半径。border-radius = 角丸。

---

## Q04
要素に影をつけるCSSプロパティはどれか

【A】 `shadow-box`  
【B】 `box-shadow`  
【C】 `border-shadow`  
【D】 `drop-border`  

⭕ 正解【B】

解説  
`box-shadow` は要素に影をつけるCSSプロパティです。箱が浮き上がって見える表現に使います。

👉 よくあるミス  
`shadow-box` のように英語の順番を逆にしてしまう。

■ ポイント  
box-shadow = 箱の影。

---

## Q05
文字やインライン要素など、中身を中央揃えにするCSSはどれか

【A】 `margin: 0 auto;`  
【B】 `align: center;`  
【C】 `text-align: center;`  
【D】 `center: true;`  

⭕ 正解【C】

解説  
`text-align: center;` は、テキストやインライン要素など、要素の中身を中央に揃える指定です。

👉 よくあるミス  
要素そのものが中央に移動すると勘違いしやすい。

■ ポイント  
text-align = 中身を揃える。

---

## Q06
幅が指定されたブロック要素そのものを横方向中央に配置するCSSはどれか

【A】 `text-align: center;`  
【B】 `display: center;`  
【C】 `center-block: true;`  
【D】 `margin: 0 auto;`  

⭕ 正解【D】

解説  
`margin: 0 auto;` は左右の余白を自動調整する指定です。幅が指定されたブロック要素では左右の余白が均等になり、要素そのものが中央に配置されます。

👉 よくあるミス  
`text-align: center;` で箱そのものも中央に動くと思ってしまう。

■ ポイント  
margin auto = 箱を中央へ。ただし width が必要。

---

## Q07
要素の幅を指定するCSSプロパティはどれか

【A】 `wide`  
【B】 `width`  
【C】 `box-size`  
【D】 `size-x`  

⭕ 正解【B】

解説  
`width` は要素の横幅を指定するCSSプロパティです。中央寄せやレイアウト調整でよく使います。

👉 よくあるミス  
`wide` のような英単語そのものを選んでしまう。

■ ポイント  
width = 幅。

---

## Q08
要素の高さを指定するCSSプロパティはどれか

【A】 `height`  
【B】 `high`  
【C】 `size-y`  
【D】 `box-height-auto`  

⭕ 正解【A】

解説  
`height` は要素の高さを指定するCSSプロパティです。ただし実際のWeb制作では内容量に合わせて自然に高さが決まることも多いです。

👉 よくあるミス  
`high` のような英単語と混同しやすい。

■ ポイント  
height = 高さ。

---

## Q09
要素の内側に余白を作るCSSプロパティはどれか

【A】 `margin`  
【B】 `border`  
【C】 `padding`  
【D】 `spacing`  

⭕ 正解【C】

解説  
`padding` は要素の中身と枠線の間にできる内側の余白です。

👉 よくあるミス  
`margin` と逆に覚えてしまう。

■ ポイント  
padding = 内側余白。

---

## Q10
要素の外側に余白を作るCSSプロパティはどれか

【A】 `padding`  
【B】 `margin`  
【C】 `border`  
【D】 `inner-space`  

⭕ 正解【B】

解説  
`margin` は要素の外側に余白を作るCSSプロパティです。他の要素との距離を調整するときに使います。

👉 よくあるミス  
`padding` と混同して、内側余白だと思ってしまう。

■ ポイント  
margin = 外側余白。

---

## Q11
1行を使う箱として扱われ、前後で改行されやすいdisplayはどれか

【A】 `inline`  
【B】 `none`  
【C】 `flex`  
【D】 `block`  

⭕ 正解【D】

解説  
`display: block;` は、要素をブロックとして扱う指定です。基本的に横幅いっぱいに広がり、前後で改行されます。

👉 よくあるミス  
`flex` と混同して横並びの指定だと思ってしまう。

■ ポイント  
block = 1行を使う箱。

---

## Q12
文章の一部のように扱われ、横に並びやすいdisplayはどれか

【A】 `inline`  
【B】 `block`  
【C】 `grid`  
【D】 `none`  

⭕ 正解【A】

解説  
`display: inline;` は、文章の一部のように横に並ぶ表示方法です。代表例として `a` 要素があります。

👉 よくあるミス  
`block` と逆に覚えてしまう。

■ ポイント  
inline = 行の中。文字っぽい動き。

---

## Q13
横に並びつつ、幅や高さも指定しやすいdisplayはどれか

【A】 `inline`  
【B】 `block`  
【C】 `inline-block`  
【D】 `none`  

⭕ 正解【C】

解説  
`inline-block` は、インライン要素のように横に並びながら、ブロック要素のように幅や高さを指定しやすい表示方法です。

👉 よくあるミス  
`inline` と同じだと思ってしまう。

■ ポイント  
inline-block = 横並び + サイズ指定。

---

## Q14
代表的なブロック要素はどれか

【A】 `a`  
【B】 `span`  
【C】 `img`  
【D】 `div`  

⭕ 正解【D】

解説  
`div` は代表的なブロック要素です。グループ分けやレイアウトの箱としてよく使います。

👉 よくあるミス  
`span` と同じような役割だと思ってしまう。

■ ポイント  
div = 箱。span = 文章の一部。

---

## Q15
代表的なインライン要素はどれか

【A】 `a`  
【B】 `div`  
【C】 `section`  
【D】 `p`  

⭕ 正解【A】

解説  
`a` は代表的なインライン要素です。リンクとして文章の中に自然に入るため、横に並びやすい特徴があります。

👉 よくあるミス  
`div` と同じように幅や高さが効く箱だと思ってしまう。

■ ポイント  
a = インライン要素の代表例。

---

## Q16
inline要素に `width: 300px;` を指定した場合の説明として正しいものはどれか

【A】 必ず300pxの幅になる  
【B】 widthは基本的に効きにくい  
【C】 要素が非表示になる  
【D】 背景色だけ300pxになる  

⭕ 正解【B】

解説  
通常のインライン要素は文字の流れの中で扱われるため、`width` や `height` が効きにくい特徴があります。

👉 よくあるミス  
どの要素にも同じようにwidthが効くと思ってしまう。

■ ポイント  
inline = 文字扱い。widthは箱に効く。

---

## Q17
inline要素で `padding` を大きくしたときに起きやすい現象はどれか

【A】 周囲の要素と重なって見えることがある  
【B】 必ず改行される  
【C】 要素が消える  
【D】 角丸になる  

⭕ 正解【A】

解説  
インライン要素にも `padding` は指定できますが、行の高さや周囲との関係によっては重なって見えることがあります。

👉 よくあるミス  
ブロック要素とまったく同じように余白が確保されると思ってしまう。

■ ポイント  
inlineのpaddingは見た目に注意。

---

## Q18
`margin: 0 auto;` を使って中央寄せするために必要な条件として適切なものはどれか

【A】 文字色が指定されている  
【B】 背景色が指定されている  
【C】 幅が指定されている  
【D】 影が指定されている  

⭕ 正解【C】

解説  
`margin: 0 auto;` は左右の余白を自動調整する指定です。そのため、中央寄せしたい要素に幅が指定されている必要があります。

👉 よくあるミス  
marginだけ書けば必ず中央に寄ると思ってしまう。

■ ポイント  
中央寄せ = width + margin auto。

---

## Q19
`display: none;` の説明として正しいものはどれか

【A】 要素は見えないが場所は残る  
【B】 要素が表示されず、場所も取らない  
【C】 要素が透明になるだけ  
【D】 要素が横並びになる  

⭕ 正解【B】

解説  
`display: none;` は要素を表示せず、レイアウト上の場所も取りません。

👉 よくあるミス  
`visibility: hidden;` と同じだと思ってしまう。

■ ポイント  
display:none = 表示も場所も消える。

---

## Q20
CSSのボックスモデルの構成として正しいものはどれか

【A】 HTML・CSS・JavaScript・画像  
【B】 header・main・footer・nav  
【C】 content・padding・border・margin  
【D】 id・class・href・src  

⭕ 正解【C】

解説  
CSSのボックスモデルでは、要素は内容領域、padding、border、marginで構成されます。

👉 よくあるミス  
HTMLの構造や属性と混同してしまう。

■ ポイント  
中身 → padding → border → margin。

---


# ■ 実技 5問

---

## P01
border と background-color

次の条件を満たす `.box` を作成しなさい。
- 幅300px
- オレンジ色の枠線
- 水色の背景色
- 中の文字は「BOX」

初期コード

```html
<div class="box">
  BOX
</div>
```

初期コード

```css
.box{

}
```

正答例

```css
.box{
  width:300px;
  border:3px solid orange;
  background-color:skyblue;
}
```

⭕ 正答例

解説  
border は箱を見えるようにし、background-color は箱の範囲を確認しやすくします。

---

## P02
text-align と margin auto

次の条件を満たす `.box` を作成しなさい。
- 幅300px
- border を付ける
- 箱そのものを中央寄せ
- 文字も中央寄せ

初期コード

```html
<div class="box">
  CENTER
</div>
```

初期コード

```css
.box{

}
```

正答例

```css
.box{
  width:300px;
  border:3px solid orange;
  margin:0 auto;
  text-align:center;
}
```

⭕ 正答例

解説  
margin auto は箱を中央へ移動し、text-align は中身を中央へ揃えます。

---

## P03
inline-block

次の条件を満たすリンクボタンを作成しなさい。
- 横並び
- 幅200px
- padding 20px
- 枠線あり
- display を使う

初期コード

```html
<a href="#">ボタン1</a>
<a href="#">ボタン2</a>
```

初期コード

```css
a{

}
```

正答例

```css
a{
  display:inline-block;
  width:200px;
  padding:20px;
  border:2px solid blue;
}
```

⭕ 正答例

解説  
a は通常 inline要素です。inline-block を使うことで、横並びとサイズ指定を両立できます。

---

## P04
display:none と visibility:hidden

次の2つのクラスを作成しなさい。
- `.hide1`：要素も場所も消す
- `.hide2`：見えなくするが場所は残す

初期コード

```html
<div class="hide1">BOX1</div>
<div class="hide2">BOX2</div>
```

初期コード

```css
.hide1{

}

.hide2{

}
```

正答例

```css
.hide1{
  display:none;
}

.hide2{
  visibility:hidden;
}
```

⭕ 正答例

解説  
display:none は表示も場所も消えます。visibility:hidden は見えませんが場所は残ります。

---

## P05
box model を確認する

次の条件を満たす `.box` を作成しなさい。
- width 300px
- padding 30px
- border 5px
- margin 40px
- background-color を付ける

初期コード

```html
<div class="box">
  BOX MODEL
</div>
```

初期コード

```css
.box{

}
```

正答例

```css
.box{
  width:300px;
  padding:30px;
  border:5px solid orange;
  margin:40px;
  background-color:skyblue;
}
```

⭕ 正答例

解説  
外側から margin → border → padding → content の順で確認します。

---


# ■ 復習 5問

---

## R01
`text-align:center;` が中央揃えする対象はどれか

【A】 border  
【B】 要素そのもの  
【C】 中身  
【D】 margin  

⭕ 正解【C】

解説  
text-align は中身を中央に揃えます。

---

## R02
`margin:0 auto;` が中央揃えする対象はどれか

【A】 箱そのもの  
【B】 文字色  
【C】 背景色  
【D】 border  

⭕ 正解【A】

解説  
margin auto は箱を中央へ移動します。

---

## R03
代表的な block 要素はどれか

【A】 `a`  
【B】 `span`  
【C】 `div`  
【D】 `img`  

⭕ 正解【C】

解説  
div は代表的な block 要素です。

---

## R04
代表的な inline 要素はどれか

【A】 `div`  
【B】 `section`  
【C】 `p`  
【D】 `a`  

⭕ 正解【D】

解説  
a は代表的な inline 要素です。

---

## R05
横並びしつつ width も使いやすい display はどれか

【A】 `inline-block`  
【B】 `inline`  
【C】 `none`  
【D】 `grid`  

⭕ 正解【A】

解説  
inline-block は inline と block の特徴を両方持ちます。

---


# ■ 応用 5問

---

## B01
次のCSSを指定した場合、中央寄せされるものはどれか

正答例

```css
.box{
  width:300px;
  margin:0 auto;
}
```

【A】 文字  
【B】 箱  
【C】 borderだけ  
【D】 paddingだけ  

⭕ 正解【B】

解説  
margin auto は箱を中央寄せします。

---

## B02
次のうち、width が効きにくい要素はどれか

【A】 `div`  
【B】 `section`  
【C】 `a`  
【D】 `p`  

⭕ 正解【C】

解説  
a は inline 要素なので width が効きにくいです。

---

## B03
次のCSSを追加したときの変化として正しいものはどれか

正答例

```css
display:block;
```

【A】 横並びになる  
【B】 改行される  
【C】 非表示になる  
【D】 透明になる  

⭕ 正解【B】

解説  
block は1行を使う表示方法です。

---

## B04
次のCSSを追加したときの変化として正しいものはどれか

正答例

```css
display:none;
```

【A】 要素が中央寄せになる  
【B】 角丸になる  
【C】 要素は見えないが場所は残る  
【D】 要素も場所も消える  

⭕ 正解【D】

解説  
display:none は表示も場所も消えます。

---

## B05
次の説明として正しいものはどれか

【A】 padding は外側余白  
【B】 margin は内側余白  
【C】 padding は内側余白  
【D】 border は余白  

⭕ 正解【C】

解説  
padding = 内側余白、margin = 外側余白です。

---


# ■ 知識 5問

---

## K01
Webページの場所を表すものはどれか

【A】 HTML  
【B】 URL  
【C】 CSS  
【D】 PNG  

⭕ 正解【B】

解説  
URL はWebページやファイルの場所を表します。

---

## K02
1つ上の階層へ移動する相対パスはどれか

【A】 `./`  
【B】 `//`  
【C】 `../`  
【D】 `/root`  

⭕ 正解【C】

解説  
`../` は1つ上の階層を表します。

---

## K03
現在のフォルダを表す相対パスはどれか

【A】 `./`  
【B】 `../`  
【C】 `//`  
【D】 `/index`  

⭕ 正解【A】

解説  
`./` は現在のフォルダを表します。

---

## K04
Webサイトを高速表示するため、一時保存を行う仕組みはどれか

【A】 Cookie  
【B】 Cache  
【C】 Session  
【D】 URL  

⭕ 正解【B】

解説  
Cache は画像やデータを一時保存する仕組みです。

---

## K05
ログイン情報などを保存する仕組みとして使われるものはどれか

【A】 Cookie  
【B】 URL  
【C】 HTML  
【D】 margin  

⭕ 正解【A】

解説  
Cookie はログイン状態などを保存する仕組みです。

---


# ■ 宿題 復習 10問

---

## HR01
枠線を指定するCSSはどれか

【A】 `frame`  
【B】 `border`  
【C】 `line`  
【D】 `shadow`  

⭕ 正解【B】

解説  
border は枠線を指定します。

---

## HR02
背景色を指定するCSSはどれか

【A】 `color-box`  
【B】 `background-color`  
【C】 `bg`  
【D】 `font-color`  

⭕ 正解【B】

解説  
background-color は背景色を指定します。

---

## HR03
文字を中央寄せするCSSはどれか

【A】 `text-align:center;`  
【B】 `margin:auto;`  
【C】 `display:block;`  
【D】 `padding:0 auto;`  

⭕ 正解【A】

解説  
text-align は中身を中央寄せします。

---

## HR04
箱そのものを中央寄せするCSSはどれか

【A】 `text-align:center;`  
【B】 `center:block;`  
【C】 `margin:0 auto;`  
【D】 `align:center;`  

⭕ 正解【C】

解説  
margin:0 auto は幅のある箱を中央寄せします。

---

## HR05
内側余白を指定するCSSはどれか

【A】 `padding`  
【B】 `margin`  
【C】 `border`  
【D】 `inside`  

⭕ 正解【A】

解説  
padding は内側余白です。

---

## HR06
外側余白を指定するCSSはどれか

【A】 `padding`  
【B】 `margin`  
【C】 `space`  
【D】 `border`  

⭕ 正解【B】

解説  
margin は外側余白です。

---

## HR07
block 要素の特徴として正しいものはどれか

【A】 横並びになる  
【B】 width が効かない  
【C】 改行される  
【D】 文字扱いになる  

⭕ 正解【C】

解説  
block 要素は前後で改行されやすいです。

---

## HR08
inline 要素の特徴として正しいものはどれか

【A】 改行されやすい  
【B】 width が必ず効く  
【C】 1行を使う  
【D】 横並びになりやすい  

⭕ 正解【D】

解説  
inline 要素は横並びになりやすいです。

---

## HR09
横並びしつつ width も使える display はどれか

【A】 `inline`  
【B】 `block`  
【C】 `inline-block`  
【D】 `none`  

⭕ 正解【C】

解説  
inline-block は横並びとサイズ指定を両立します。

---

## HR10
display:none; の説明として正しいものはどれか

【A】 中央寄せになる  
【B】 要素も場所も消える  
【C】 透明になる  
【D】 横並びになる  

⭕ 正解【B】

解説  
display:none は表示も場所も消えます。

---


# ■ 宿題 アレンジ問題 5問

---

## HA01
角丸を指定するCSSはどれか

【A】 `round-border`  
【B】 `border-radius`  
【C】 `corner`  
【D】 `radius-box`  

⭕ 正解【B】

解説  
border-radius は角丸を指定します。

---

## HA02
影を付けるCSSはどれか

【A】 `shadow-box`  
【B】 `border-shadow`  
【C】 `box-shadow`  
【D】 `drop-shadow-box`  

⭕ 正解【C】

解説  
box-shadow は影を付けます。

---

## HA03
次のうち inline 要素はどれか

【A】 `div`  
【B】 `section`  
【C】 `p`  
【D】 `a`  

⭕ 正解【D】

解説  
a は代表的な inline 要素です。

---

## HA04
次のうち block 要素はどれか

【A】 `a`  
【B】 `span`  
【C】 `div`  
【D】 `img`  

⭕ 正解【C】

解説  
div は代表的な block 要素です。

---

## HA05
次のうち box model に含まれるものはどれか

【A】 URL  
【B】 Cookie  
【C】 JavaScript  
【D】 padding  

⭕ 正解【D】

解説  
padding は box model に含まれます。

---


# ■ 宿題 知識問題 5問

---

## HK01
Webページの場所を表すものはどれか

【A】 CSS  
【B】 HTML  
【C】 URL  
【D】 Cookie  

⭕ 正解【C】

解説  
URL はWebページやファイルの場所を表します。

---

## HK02
1つ上の階層を表す相対パスはどれか

【A】 `./`  
【B】 `../`  
【C】 `//`  
【D】 `/top`  

⭕ 正解【B】

解説  
`../` は1つ上の階層を表します。

---

## HK03
現在のフォルダを表す相対パスはどれか

【A】 `./`  
【B】 `../`  
【C】 `/root`  
【D】 `//`  

⭕ 正解【A】

解説  
`./` は現在のフォルダを表します。

---

## HK04
一時保存によってWeb表示を高速化する仕組みはどれか

【A】 Cookie  
【B】 Cache  
【C】 URL  
【D】 Session  

⭕ 正解【B】

解説  
Cache は一時保存によって表示を速くします。

---

## HK05
ログイン情報などを保存する仕組みはどれか

【A】 Cache  
【B】 Cookie  
【C】 HTML  
【D】 border  

⭕ 正解【B】

解説  
Cookie はログイン状態などを保存する仕組みです。

---

# CHANGELOG

## v1
- 第3回を「箱を見る → 箱を動かす → displayで性格を変える」流れに再構成
- 本問20問をHTML/CSSに特化
- 相対パス・URL・Cookie・Cacheを知識問題へ分離
- 実技問題を5問に拡張
- HTMLでは選択直後に正誤色を出さず、解説を開いた時点で正誤表示する仕様
