<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>ibukiTenC 公式サイト</title>
<link rel="canonical" href="https://www.mat.info.gifu-u.ac.jp/ikd/ibukiTenC/">
<link href="style.css" type="text/css" rel="stylesheet">
<meta http-equiv="Content-Style-Type" content="text/css">
<meta name="keywords" content="ibukiTenC,点字,点訳,自動点訳システム,岐阜大学">
<meta name="description" content="ibukiTenC site">
</head>

<body>

<!--■■開始-->
<div id="container">


<!--■ヘッダー欄-->
<div id="header">

<div id="logo">
	<a href="index.html"><img src="img/ibukitenc_logo.png" title="ibukiTenC トップペーシ" alt="ibukiTenC トップページ"></a>
</div>

<div id="navigation">
	<a href="function.html">機能紹介</a>
	<a href="download_user.html">ダウンロード</a>
	お問い合わせ
	<!--
	<a href="support.html">お問い合わせ</a>
	-->
</div>

<div id="introduction">
自動点訳システムibukiTenCを無償で公開しています。
</div>


</div><!--header'sEND-->


<div id="all-columns">


<!--■プライマリアンドセカンダリカラム-->
<div id="primary_and_secondary-column">

<!-- ::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: -->
<h1 class="hidden">ibukiTenC</h1>

<div style="text-align:center;">
<img src="img/ibukitenc_ss_top.png" title="ibukiTenCとibukiTenCEditの動作画面" alt="ibukiTenCとibukiTenCEditの動作画面">
<p>現在の最新版は2009年3月12日公開のver.0.65です。<br><a href="history.html">詳しい情報は更新履歴をご覧ください。</a></p>

<hr style="width: 20em">
<p>
<a href="download_user.html">ibukiTenCおよびibukiTenCEditのダウンロード</a><br>
<a href="http://www.ikd.info.gifu-u.ac.jp/ibukiTenC/Edit2Beta/">ibukiTenCEdit2のダウンロード</a><br>
</p>
</div>


<div class="attention">
<p><span style="font-size:1.1em; font-weight: bold;"><span style="color:#ff0000">重要なお知らせ</span> ibukiTenCのメンテナンスについて</span></p>
<br>
<p>ibukiTenCは今回のversion0.65で一段落として、人手の関係もあって当面改版作業をお休みすることと致しました。<br>
システムの公開は今後ともこれまでどおり続けます。これまでどおりダウンロードできます。<br>
ご意見等のメールアドレスは開いておきますが、修正のご要望等にすぐに対応出来かねることになります。ご了解ください。<br>
今後の改版への対応等については、また改めてアナウンスいたします。</p>
<br>
<p>これまで利用していただいた方々、ご意見・ご指摘・ご要望をお寄せ頂いた方々に感謝いたします。
以上、今後ともよろしくお願い致します。</p>
<br>
<p>2009年3月12日<br>
池田尚志</p>
</div>

<div class="attention">
<p><span style="font-size:1.1em; font-weight: bold;">ibukiTenCEdit2について</span></p>
<br>
<p>ibukiTenCEdit2は、ibukiTenCEditの後継を目指して開発したもので、点訳エンジンにはibukiTenCをそのまま用いています。ibukiTenCEdit2は、ibukiTenCグループの一部として、同じように公開します。</p>
<p>ibukiTenCEdit2については、開発後未だあまり日も経ていませんが、人手の関係もあって今後のメンテナンスについては必ずしも保障できません。ibukiTenCEdit2については、ソースプログラムも公開することと致しました。無償利用許諾契約書の範囲内でご自由にお使いください。</p>
</div>

<!-- ::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: -->
<h1>ibukiTenCについて</h1>

<p>ibukiTenCは、国立大学法人岐阜大学（工学部応用情報学科池田研究室）で開発した自動点字翻訳編集システムです。前身のibukiTenを引き継いでいますが、辞書がibukiDicに変わりました。</p>
<p>ibukiTenCは、漢字かな混じりで書かれた通常の日本語文章のテキストファイルを入力すると、日本語解析システムibukiCを用いて文節分かち書きを行い、読みかなを付与し、さらに点字の規則に則った分かち書きや読み、制御コード等を整えて、仮名表記で、あるいは点字コードで出力します。</p>
<p>ibukiTenCには、後編集の機能を持たせたibukiTenCEditもあります。またibukiTenCEditの後継として、最近開発したibukiTenCEdit2もあります。</p>
<p>ibukiは、岐阜県と滋賀県の県境に聳える名山「伊吹山」から拝借した名前です。</p>
<p>ibukiTenCは、非商業的な利用に限り、無償で自由にお使い頂けます。ibukiTenC SDKによってibukiTenCをユーザのプログラムから呼び出して使うこともできます。ibukiTenC SDKも非商業的な利用に限り、無償で自由にお使い頂けます。詳細はそれぞれ<a href="download_user.html#license">「ibukiTenCの無償利用許諾契約書」</a>および<a href="download_developer.html#license">「ibukiTenC SDKの無償利用許諾契約書」</a>として記載してありますので、お読み頂いて御了解の上御利用ください。</p>
<p>｛なおibukiTenC SDKを商業的に利用されることをご希望の場合は｛<img src="img/mailaddress_yugo.png" alt="メールアドレスは画像に表示" class="mail_img">又は<img src="img/mailaddress_ikeda.png" alt="メールアドレスは画像に表示" class="mail_img">｝にご相談ください。｝</p>


<!-- ::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: -->
<!--
<h1>ibukiTenがibukiTenCになりました！</h1>
<p>ibukiTenでは自立語辞書のベースとして"EDRの辞書の一部"を用いておりましたが、ibukiTenCでは我々独自の新たな辞書(ibukiDic)を使用するようにしました。</p>
<p>機能的にはibukiTenCはibukiTenとほとんど同じです。ibukiTenCのversionはibukiTenの最後のversionであるver0.56の後に続けて、ver0.6からスタートすることにしました。</p>
<p>ibukiTenも、これまでと同様にそのまま公開を続けますが(<a href="http://www.ikd.info.gifu-u.ac.jp/IBUKI-TEN/">旧IBUKI-TENのページ</a>)、メンテナンスはibukiTenCのほうに移行します。</p>
<p>ibukiTenでユーザ辞書を定義して使っておられた方も、そのままibukiTenCでもお使いになれます。ただしユーザ辞書を改めて読み込みなおす必要があります。</p>
-->

<!-- ::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: -->
<h1>開発の経緯</h1>

<p>ibukiTenCは、基盤となっている日本語解析システムがibukiBからibukiCに改版されたのに伴って、前身のibukiTenを改版したものです。ibukiTenCでは内容語辞書がEDRの辞書の一部をベースにしたものから自前の辞書ibukiDicになりました。</p>
<p>これらのibukiシステムは池田研究室の歴代のメンバーが引き継ぎながら開発・改良を続けてきました。最近では、ibukiCとibukiTenCに関して、H20年度修士課程修了の高田和典君、脇田貴之君が中心になって進めてくれました。またibukiTenCEdit2は同じくH20年度修士課程修了の江本倫基君が開発してくれたものです。このほか、最近ではH18年度修士課程修了の山田佳裕君、H17年度修士課程修了の高松大地君、石原吉晃君、H16年度修士課程修了の伊佐治和也君、などが中心になって進めてくれました。Ibukiシステムの開発には、このほか池田研究室に在籍したすべての学生たちが何らかの貢献をしています。皆さんに感謝します。（<a href="http://www.ikd.info.gifu-u.ac.jp/IBUKI-TEN/index_main.html#thanks">旧IBUKI-TENのページの「8.謝辞」</a>）</p>
<p>また全国の多くの点訳ボランティアの方々、視覚障害者の方々に使って頂き、たくさんの貴重なご意見を頂きました。有り難うございました。</p>

<p>平成21年3月<br>岐阜大学工学部応用情報学科 教授　池田尚志</p>

<!-- ::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: -->
<h1>お知らせ</h1>

<div class="attention">
<h2 class="attention">WindowsVistaへの対応状況について</h2>
<p>こちらでの動作確認で、通常の点訳機能は問題なく動作することが確認できています。</p>
<p>なお、外部周辺機器への出力に関しては、こちらで実機での動作確認ができているのは、今のところ、点字プリンタ「ET」のみです。</p>

<h2 class="attention">ibukiTen版のユーザ辞書のibukiTenC版への更新について</h2>
<p>ibukiTen0.56以前のユーザ辞書をibukiTenCで使う場合には、次の手順で辞書の再読込をしてください。この作業を行わないと旧ユーザ辞書は反映されません。</p>
<p>※旧ユーザ辞書を使わない場合はこの作業は不要です。</p>

<hr>

<ol>
	<li>IbukiTenのユーザ辞書フォルダにあるuserdic.txtを、ibukiTenCのユーザ辞書フォルダにコピーする<br>IbukiTen　C:¥Program Files¥IBUKI-TEN¥userdic¥<br>ibuiiTenC　C:¥Program Files¥ibukiTenC¥userdic¥</li>
	<li>ibukiTenCを起動する</li>
	<li>辞書登録ボタンを押し、ユーザ辞書ダイアログを表示する</li>
	<li>メニューから「ファイル-&gt;開く」を選択し、先ほどコピーしたファイルを読み込む</li>
	<li>メニューから「ツール-&gt;辞書更新」を選択する</li>
</ol>
</div>

<!-- ::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: -->
<h1>リンク</h1>
<ul>
	<li><a href="http://www.ikd.info.gifu-u.ac.jp/ibukiC/">ibukiCのページ</a></li>
	<li><a href="http://www.ikd.info.gifu-u.ac.jp/IBUKI-TEN/">旧IBUKI-TENのページ</a></li>
	<li><a href="http://www.ikd.info.gifu-u.ac.jp/">池田研究室</a></li>
</ul>

</div><!--primary_and_secondary-column'sEND-->

</div><!--all-columns'sEND-->


<!--■フッター-->
<div id="footer">
&copy;岐阜大学(池田研究室)
</div><!--footer'sEND-->


</div><!--container'sEND-->

</body> 
</html>

<!--
/* サイト構築・変更用の覚え書き */

html文法チェック
http://htmllint.itc.keio.ac.jp/htmllint/htmllint.html

スタイルシートリファレンス
http://www.htmq.com/style/index.shtml

-->

