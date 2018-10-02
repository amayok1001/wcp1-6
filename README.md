# wcp1-6

## メイン要素の制作
### <main>タグ
	body要素のメインコンテンツを表す
	1HTMLに一回しか使えない

### line-height:文字の行の高さを決める
	line-height: 40px; /* 単位を付ける場合 / 文字の行の高さは40pxになる */
  	line-height: 1.5; /* 単位を付けない場合 / 文字の行の高さは親要素の行の高さの1.5倍になる*

### <span>タグ
	<div>タグ同様、タグ自体に意味をもっていないが
	インライン要素なので<p>タグ内などで使用する

### border-radiusプロパティ
	箱の枠線の角を丸める
	50%で正円にする

### <section>タグ
	子要素に<h>タグを含む箱
	意味合いは<div>と同じ

### displayプロパティを使った横並びの方法
	横並び⇨block,inline-block

### 余白を使って距離をつくるときはpaddingを使う

## 確認問題
問1 2.
問2/3/4
HTML
<section>
	<h1>折り返し<span>地点</span></h1>
</section>
CSS
section {
	width: 300px;
	height:300px;
	border: 2px solid #fa5893;
}
.span {
	color: #fa5893
}