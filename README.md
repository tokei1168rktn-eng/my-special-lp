<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="robots" content="noindex">
<title>AI×SNSスタータープログラム 0→100完全攻略セミナー お申し込みページ</title>
<style>
/* =========================================
RESET & BASE
========================================= */
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
body{
font-family:-apple-system,BlinkMacSystemFont,"Hiragino Sans","Noto Sans JP",sans-serif;
background:#fff;color:#111;line-height:1.7;
}
.page{max-width:760px;margin:0 auto;}
img{width:100%;display:block;}

/* =========================================
共通ユーティリティ
========================================= */
.text-pink{color:#ff0088;}
.text-magenta{color:#e91e8c;}
.text-purple{color:#9933cc;}
.text-yellow{color:#ffcc00;}
.text-white{color:#fff;}
.text-center{text-align:center;}
.bold{font-weight:700;}

/* =========================================
セクション共通
========================================= */
.sec{width:100%;padding:0;}
.sec-dark{background:linear-gradient(180deg,#0d0020 0%,#050010 100%);}
.sec-black{background:#000;}
.sec-white{background:#fff;}
.sec-light{background:#f9f0ff;}

/* =========================================
フォームセクション
========================================= */
.form-sec{background:#000;padding:20px 20px 14px;text-align:center;}
.btn-wrap{position:relative;overflow:hidden;border-radius:8px;display:block;max-width:480px;margin:0 auto;}
.btn-cta{
width:100%;padding:18px 20px;
font-size:clamp(16px,3vw,21px);font-weight:900;
color:#fff;letter-spacing:.05em;
background:linear-gradient(135deg,#cc00ff 0%,#ff0077 50%,#ff6600 100%);
border:none;border-radius:8px;cursor:pointer;
position:relative;overflow:hidden;
box-shadow:0 4px 24px rgba(255,0,136,.5);
transition:transform .1s,box-shadow .2s;
display:block;text-align:center;
text-decoration:none;
}
.btn-cta:hover{transform:translateY(-2px);box-shadow:0 6px 32px rgba(255,0,136,.7);}
.btn-wrap::after{
content:"";position:absolute;top:-50%;left:-75%;
width:50%;height:200%;
background:linear-gradient(to right,rgba(255,255,255,0) 0%,rgba(255,255,255,.45) 50%,rgba(255,255,255,0) 100%);
transform:skewX(-20deg);animation:shiny 2.5s infinite;
}
@keyframes shiny{
0%{left:-75%;opacity:0;}10%{opacity:1;}
50%{left:125%;opacity:1;}51%{opacity:0;}100%{left:125%;opacity:0;}
}
.form-note{color:#fff;font-size:12px;margin-top:10px;opacity:.85;}

/* =========================================
ヒーロー（セクション1）
========================================= */
.hero{
background:linear-gradient(160deg,#1a0040 0%,#0a0025 30%,#020010 60%,#000000 100%);
padding:40px 20px 30px;text-align:center;position:relative;overflow:hidden;
}
.hero::before{
content:"";position:absolute;top:0;left:50%;transform:translateX(-50%);
width:600px;height:600px;
background:radial-gradient(ellipse,rgba(153,0,255,.15) 0%,transparent 70%);
pointer-events:none;
}
.hero-year{
font-size:clamp(42px,8vw,72px);font-weight:900;
background:linear-gradient(90deg,#8844ff,#cc44ff,#ff88ff);
-webkit-background-clip:text;-webkit-text-fill-color:transparent;
letter-spacing:.2em;
}
.hero-sub1{
font-size:clamp(14px,2.5vw,20px);color:#cc88ff;
letter-spacing:.15em;margin-bottom:16px;
}
.hero-catch{
font-size:clamp(22px,4.5vw,38px);font-weight:900;color:#fff;
line-height:1.4;margin-bottom:4px;
}
.hero-catch .num{color:#ff0088;font-size:1.2em;}
.hero-catch2{
color: #fff;
font-size:clamp(18px,3.5vw,30px);font-weight:900;line-height:1.5;
margin-bottom:20px;
}
.hero-catch2 .pink{color:#ff0088;}
.hero-catch2 .ai{
background:linear-gradient(90deg,#ff44cc,#ff9900);
-webkit-background-clip:text;-webkit-text-fill-color:transparent;
}

/* タグバッジ群 */
.tags{display:flex;flex-wrap:wrap;gap:6px;justify-content:center;margin:18px 0;}
.tag{
border:1px solid #6644aa;color:#ccaaff;
font-size:clamp(10px,1.8vw,13px);padding:4px 10px;border-radius:4px;
}

/* AI大文字タイトル */
.ai-title{margin:20px 0 6px;}
.ai-big{
font-size:clamp(70px,14vw,120px);font-weight:900;
line-height:1;
background:linear-gradient(135deg,#cc00ff,#ff0088);
-webkit-background-clip:text;-webkit-text-fill-color:transparent;
letter-spacing:-.02em;
}
.ai-driven{
font-size:clamp(18px,3.5vw,30px);color:#fff;font-weight:700;
letter-spacing:.08em;
}
.content-biz{
font-size:clamp(22px,4.5vw,40px);font-weight:900;color:#fff;
letter-spacing:.05em;
}

/* 0→100バナー */
.zero100{
background:linear-gradient(135deg,#2200aa,#6600ff,#cc00ff);
border-radius:12px;padding:18px 20px;margin:20px 0;
}
.zero100 .num{font-size:clamp(36px,7vw,60px);font-weight:900;color:#fff;}
.zero100 .num .pink{color:#ff44cc;}
.zero100 .label{font-size:clamp(16px,3vw,26px);color:#fff;font-weight:700;}

/* バッジ */
.badge-yellow{
display:inline-block;background:#ffcc00;color:#000;
font-weight:900;font-size:clamp(11px,2vw,14px);
padding:6px 14px;border-radius:20px;margin:8px auto;
}

/* 説明テキスト */
.hero-desc{color:#ccc;font-size:clamp(13px,2vw,16px);line-height:1.8;margin:14px 0;}
.hero-desc .accent{color:#ff0088;font-weight:700;}

/* 開催日程 */
.schedule-box{
background:rgba(255,255,255,.07);border:1px solid rgba(255,255,255,.15);
border-radius:10px;padding:18px 20px;margin:20px 0;
}
.schedule-title{color:#ffcc00;font-size:clamp(14px,2.5vw,18px);font-weight:700;margin-bottom:10px;}
.schedule-dates{color:#fff;font-size:clamp(14px,2.2vw,17px);font-weight:700;line-height:1.6;}

/* =========================================
セクション2：お悩み
========================================= */
.trouble{background:#fff;padding:40px 24px;}
.sec-title{
font-size:clamp(24px,5vw,40px);font-weight:900;
text-align:center;line-height:1.4;margin-bottom:28px;
}
.sec-title .pink{color:#ff0088;}
.checklist{list-style:none;display:flex;flex-direction:column;gap:14px;}
.checklist li{
display:flex;align-items:flex-start;gap:12px;
background:#f8f0ff;border-left:4px solid #cc00ff;
border-radius:0 8px 8px 0;padding:14px 16px;
font-size:clamp(13px,2.2vw,16px);line-height:1.7;
}
.checklist li .icon{
width:24px;height:24px;min-width:24px;
background:#4466ff;border-radius:50%;
display:flex;align-items:center;justify-content:center;
color:#fff;font-size:14px;font-weight:700;margin-top:2px;
}
.checklist li .hl{color:#ff0088;font-weight:700;}

/* 解決バナー */
.solve-banner{
background:linear-gradient(135deg,#1100aa,#3300cc);
color:#fff;text-align:center;padding:20px;border-radius:10px;margin-top:24px;
}
.solve-banner .main{font-size:clamp(16px,3vw,22px);font-weight:900;line-height:1.6;}
.solve-banner .hl{color:#ffcc00;}

/* =========================================
セクション3：このセミナーで手に入ること
========================================= */
.get-sec{
background:linear-gradient(180deg,#05001a 0%,#0a0030 100%);
padding:40px 24px;
}
.get-sec .sec-title{color:#fff;}
.get-sec .sec-title .sub{color:#cc88ff;font-size:.6em;display:block;margin-bottom:6px;}
.card-list{display:flex;flex-direction:column;gap:16px;margin-top:24px;}
.card{
display:flex;gap:0;border-radius:10px;overflow:hidden;
background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);
}
.card-num{
min-width:54px;background:linear-gradient(180deg,#cc00ff,#ff0088);
display:flex;align-items:center;justify-content:center;
font-size:clamp(18px,3vw,26px);font-weight:900;color:#fff;
padding:12px 6px;letter-spacing:-.02em;
}
.card-body{padding:14px 16px;flex:1;}
.card-body .card-title{
color:#ff88cc;font-size:clamp(13px,2vw,15px);font-weight:700;
margin-bottom:4px;
}
.card-body .card-text{color:#eee;font-size:clamp(12px,2vw,14px);line-height:1.7;}

/* =========================================
セクション4：10大特典
========================================= */
.tokuten{
background:linear-gradient(160deg,#220055,#440088,#cc0077);
padding:40px 24px;
}
.tokuten-title{text-align:center;margin-bottom:8px;}
.tokuten-title .pre{color:#ffcc88;font-size:clamp(14px,2.5vw,18px);font-weight:700;}
.tokuten-title .main{
font-size:clamp(36px,7vw,64px);font-weight:900;
background:linear-gradient(90deg,#ffcc00,#ffaa00);
-webkit-background-clip:text;-webkit-text-fill-color:transparent;
line-height:1.1;
}
.tokuten-title .sub{color:#fff;font-size:clamp(13px,2vw,16px);margin-top:8px;}
.tokuten-list{display:flex;flex-direction:column;gap:12px;margin-top:24px;}
.tokuten-item{
background:rgba(0,0,0,.3);border:1px solid rgba(255,255,255,.15);
border-radius:10px;padding:14px 16px;display:flex;align-items:flex-start;gap:14px;
}
.tokuten-num{
min-width:44px;height:44px;background:linear-gradient(135deg,#ffcc00,#ff8800);
border-radius:50%;display:flex;align-items:center;justify-content:center;
font-size:14px;font-weight:900;color:#000;
}
.tokuten-body .t-title{color:#fff;font-weight:700;font-size:clamp(14px,2.2vw,16px);line-height:1.5;}
.tokuten-body .t-sub{color:#ffccee;font-size:clamp(11px,1.8vw,13px);margin-top:3px;}

/* =========================================
セクション5：おすすめ対象
========================================= */
.target{background:#fff;padding:40px 24px;}
.target .sec-title .sub{font-size:.65em;color:#9933cc;display:block;}
.target .checklist li{background:#fff5ff;border-left-color:#ff0088;}
.target .checklist li .hl{background:#ffcc00;color:#000;padding:0 4px;border-radius:2px;}

/* =========================================
セクション6：実績
========================================= */
.jisseki{
background:linear-gradient(180deg,#0a001f,#0d0030);
padding:40px 24px;
}
.jisseki .sec-title{color:#fff;}
.jisseki-sub{color:#ccaaff;text-align:center;font-size:clamp(13px,2vw,16px);margin-bottom:24px;}
.jisseki-list{display:flex;flex-direction:column;gap:14px;}
.jisseki-item{
background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.1);
border-radius:8px;padding:16px 18px;
}
.jisseki-item .j-num{
font-size:clamp(24px,4vw,36px);font-weight:900;
color:#ff0088;line-height:1.1;
}
.jisseki-item .j-text{color:#eee;font-size:clamp(13px,2vw,15px);line-height:1.7;}
.jisseki-note{
background:#1a0033;border:2px solid #6600cc;border-radius:10px;
padding:18px;margin-top:20px;color:#fff;
font-size:clamp(13px,2vw,15px);line-height:1.8;text-align:center;
}

/* =========================================
セクション7：受講生の声（サムネグリッド）
========================================= */
.voice{background:#0a0010;padding:40px 24px;}
.voice .sec-title{color:#fff;}
.voice-grid{
display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:20px;
}
.voice-card{
background:linear-gradient(135deg,#1a0033,#330066);
border:1px solid rgba(255,100,200,.3);border-radius:8px;
padding:12px;font-size:clamp(10px,1.6vw,12px);
color:#fff;line-height:1.5;
}
.voice-card .vc-result{
color:#ff44cc;font-weight:700;font-size:clamp(11px,1.8vw,13px);
border-bottom:1px solid rgba(255,100,200,.3);padding-bottom:6px;margin-bottom:6px;
}
.voice-card .vc-detail{color:#ddaaff;font-size:clamp(9px,1.4vw,11px);}

/* =========================================
セクション12：Q&A
========================================= */
.qna{background:#f9f9f9;padding:60px 24px;}
.qna .sec-title{text-align:center;margin-bottom:40px;color:#111;}
.qna .sec-title .en{font-size:.6em;letter-spacing:.2em;color:#9933cc;display:block;margin-bottom:8px;}
.qa-list{display:flex;flex-direction:column;gap:24px;max-width:680px;margin:0 auto;}
.qa-q{
display:flex;align-items:flex-start;gap:12px;margin-bottom:10px;
}
.qa-q .q-badge{
min-width:36px;height:36px;background:linear-gradient(135deg,#440099,#7700cc);
border-radius:50%;display:flex;align-items:center;justify-content:center;
font-weight:900;color:#ff88cc;font-size:16px;
}
.qa-q .q-text{font-size:clamp(14px,2.2vw,16px);font-weight:700;color:#111;padding-top:6px;line-height:1.5;}
.qa-a{
background:#fff;border:1px solid #eee;border-left:4px solid #cc00ff;border-radius:0 8px 8px 0;
padding:18px 20px;margin-left:48px;
font-size:clamp(13px,2vw,15px);color:#444;line-height:1.8;
box-shadow:0 2px 8px rgba(0,0,0,.05);
}

/* =========================================
最終登録案内
========================================= */
.final-reg{background:#fff;padding:60px 24px;text-align:center;border-top:1px solid #eee;}
.final-reg .msg{
font-size:clamp(18px,3vw,24px);font-weight:900;line-height:1.6;
color:#111;margin-bottom:30px;
}
.final-reg .pink{color:#ff0088;}

/* =========================================
フッター
========================================= */
.footer{
background:linear-gradient(135deg,#1100aa,#6600cc,#cc0077);
color:#fff;text-align:center;padding:28px 20px;
font-size:clamp(11px,1.8vw,13px);line-height:2;
}
.footer a{color:#ffddee;text-decoration:none;}
.footer a:hover{text-decoration:underline;}

/* =========================================
レスポンシブ
========================================= */
@media(max-width:576px){
.voice-grid{grid-template-columns:repeat(2,1fr);}
.btn-cta{font-size:15px;padding:15px;}
.form-sec{padding:14px 12px 10px;}
.qa-a{margin-left:0;margin-top:10px;}
}
</style>
</head>
<body>
<div class="page">

<section class="sec hero">
<div class="hero-year">２０２６年</div>
<div class="hero-sub1">AI × SNSマーケティング最新版</div>
<div class="hero-catch">個人で年収<span class="num">1400万</span>を達成した</div>
<div class="hero-catch2">
<span class="pink">すすむ式</span>SNSマーケティングを<span class="ai">AI×SNS</span>で完全再現!
</div>

<div class="tags">
<span class="tag">コンセプト設計</span><span class="tag">商品作成</span>
<span class="tag">SNS運用</span><span class="tag">無料相談</span>
<span class="tag">モニター販売</span><span class="tag">講座作成</span>
<span class="tag">LINE配信</span><span class="tag">ファネル構築</span>
<span class="tag">リストマーケ</span><span class="tag">LIVEセミナー</span>
<span class="tag">プロダクトローンチ</span><span class="tag">エバーグリーンローンチ</span>
<span class="tag">オートウェビナー</span><span class="tag">コミュニティ運営</span>
<span class="tag">顧客サポート</span><span class="tag">クライアントワーク</span>
<span class="tag">AI組織化</span>
</div>

<div class="ai-title">
<div class="ai-big">AI<span style="font-size:.75em;background:linear-gradient(135deg,#fff,#ddd);-webkit-background-clip:text;-webkit-text-fill-color:transparent;">×SNS</span></div>
<div style="font-size:clamp(9px,1.2vw,11px);color:#9977cc;letter-spacing:.2em;margin:-4px 0 4px;">AI-Driven Starter Program : The Complete 0-to-100 Mastery Seminar</div>
<div class="content-biz" style="background:linear-gradient(90deg,#fff,#eee);-webkit-background-clip:text;-webkit-text-fill-color:transparent;">動画マーケティング</div>
</div>

<div class="zero100">
<div class="num">0<span style="font-size:.7em;">»</span><span class="pink">100</span> <span style="color:#fff;font-size:.8em;font-weight:900;">完全攻略</span></div>
<div class="label">AI×SNSスタータープログラム 0»100完全攻略セミナー</div>
</div>

<div class="badge-yellow">顔出しなし。ショート動画だけで集客を最大化させ、累計1400万を達成</div>

<div class="hero-desc">
最新マーケの全領域を<span class="accent">最安値運用＆最大クオリティ担保</span>の<br>
AI×SNSで実行する<span class="accent">「AI効率化完全ロードマップ」</span>を徹底解説します
</div>

<div class="schedule-box">
<div class="schedule-title">●開催スケジュール●</div>
<div class="schedule-dates">
催スケジュール及び時間の詳細はお申込みフォームよりご確認ください。
</div>
</div>
</section>

<section class="form-sec">
<div class="btn-wrap">
<a href="https://liff.line.me/2006550850-PcLDeNNe?unique_key=RFrkt9&ts=1776055651" class="btn-cta">今すぐ無料で手に入れる</a>
</div>
<p class="form-note">※予約フォームへお申し込み後、専用公式ラインへご案内をお送りさせていただきます</p>
</section>

<section class="sec trouble">
<div class="sec-title">こんな <span class="pink">お悩み</span><br>ありませんか？</div>
<ul class="checklist">
<li><div class="icon">✓</div><div>AIを触ってはいるけど<span class="hl">「結局どれをどう使えば売上が増えるの？」</span>という状態で止まっている</div></li>
<li><div class="icon">✓</div><div>AIに指示しても「薄い」「ズレる」<span class="hl">「それっぽいけど使えない」</span>の繰り返しで、結局自分で書き直している</div></li>
<li><div class="icon">✓</div><div><span class="hl">SNSやAIを使って「どう集客すればいいかわからない」、毎日忙しすぎて作業時間を十分に確保できない</span></div></li>
<li><div class="icon">✓</div><div>ローンチ・導線・オファー作りが複雑すぎて、<span class="hl">毎回やり切れずに中途半端で終わる</span></div></li>
<li><div class="icon">✓</div><div>成果に直結しないAIツールや教材に<span class="hl">間違った課金をしてしまった経験がある</span></div></li>
<li><div class="icon">✓</div><div>AIの進化についていけず<span class="hl">「何から手をつけていいかわからない」</span>と焦りだけが募っている</div></li>
<li><div class="icon">✓</div><div><span class="hl">ショート動画の台本、LP台本、セミナー資料…"書くべきコンテンツ"が多すぎて手が止まっている</span></div></li>
</ul>
<div class="solve-banner">
<div class="main">一つでも当てはまった方は、<br>今回のセミナーで<span class="hl">全て解決します！</span></div>
</div>
</section>

<section class="form-sec">
<div class="btn-wrap">
<a href="https://liff.line.me/2006550850-PcLDeNNe?unique_key=RFrkt9&ts=1776055651" class="btn-cta">今すぐ無料で手に入れる</a>
</div>
<p class="form-note">※枠が埋まり次第募集終了となります</p>
</section>

<section class="sec get-sec">
<div class="sec-title">
<span class="sub">AI×SNSスタータープログラム 0»100完全攻略セミナー</span>
このセミナーで<br><span style="color:#ff44cc;">手に入ること</span>
</div>
<div class="card-list">
<div class="card">
<div class="card-num">01</div>
<div class="card-body">
<div class="card-title">16時間かかっていた台本作成がたった2時間に</div>
<div class="card-text">自動でAIにコンテンツを作らせる方法</div>
</div>
</div>
<div class="card">
<div class="card-num">02</div>
<div class="card-body">
<div class="card-title">ショート動画の台本、LPの台本、SNS投稿からスタータープログラムの</div>
<div class="card-text">タスク50個以上をAIで一掃する完全ロードマップ</div>
</div>
</div>
<div class="card">
<div class="card-num">03</div>
<div class="card-body">
<div class="card-title">全集客媒体を同時に攻略し</div>
<div class="card-text">SNS全媒体で総フォロワー20万人を達成したAI運用法</div>
</div>
</div>
<div class="card">
<div class="card-num">04</div>
<div class="card-body">
<div class="card-title">累計8個以上の万垢を達成した</div>
<div class="card-text">会社員でも再現できた最先端のAI×SNS戦略の裏側</div>
</div>
</div>
<div class="card">
<div class="card-num">05</div>
<div class="card-body">
<div class="card-title">毎日投稿不要でも売上に直結する</div>
<div class="card-text">半自動化でマネタイズを再現する導線構築</div>
</div>
</div>
<div class="card">
<div class="card-num">06</div>
<div class="card-body">
<div class="card-title">外注ゼロ・プログラミング不要で</div>
<div class="card-text">自分の事業専用のオリジナルAIを構築する方法</div>
</div>
</div>
<div class="card">
<div class="card-num">07</div>
<div class="card-body">
<div class="card-title">2026年AI時代に最適な</div>
<div class="card-text">効率化重視のAI活用術を再現し、売上を最速で伸ばすメソッド</div>
</div>
</div>
</div>
</section>

<section class="form-sec">
<div class="btn-wrap">
<a href="https://liff.line.me/2006550850-PcLDeNNe?unique_key=RFrkt9&ts=1776055651" class="btn-cta">今すぐ無料で手に入れる</a>
</div>
<p class="form-note">※枠が埋まり次第募集終了となります</p>
</section>

<section class="sec tokuten">
<div class="tokuten-title">
<div class="pre">セミナー参加者限定 超有料級</div>
<div class="main">10大特典</div>
<div class="sub">セミナー参加者全員に以下の特典を全て無料でプレゼントします</div>
</div>
<div class="tokuten-list">
<div class="tokuten-item">
<div class="tokuten-num">01</div>
<div class="tokuten-body">
<div class="t-title">最先端のSNS × マネタイズ完全ガイド</div>
<div class="t-sub">副業をスマートに両立し、会社員としてのキャリアを守りながら収益化する全手法</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">02</div>
<div class="tokuten-body">
<div class="t-title">AI最強活用術30選</div>
<div class="t-sub">忙しい毎日でも即戦力。月7桁の成果を支える「AIの賢い使いこなし方」の決定版</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">03</div>
<div class="tokuten-body">
<div class="t-title">作業時間を10分の1にする最強プロンプト10選</div>
<div class="t-sub">魔法のような効率化を実現。プロンプトの設計図を紐解き、自由な時間を生み出す技術</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">04</div>
<div class="tokuten-body">
<div class="t-title">最強おすすめAIツール11選</div>
<div class="t-sub">センスや経験は不要。未経験からでも一瞬でプロ級のクオリティを再現する厳選ツール</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">05</div>
<div class="tokuten-body">
<div class="t-title">最短最速マネタイズ 5つのステップ</div>
<div class="t-sub">【再現性抜群】迷いをゼロに。初心者が最短ルートで初収益を掴むためのロードマップ</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">06</div>
<div class="tokuten-body">
<div class="t-title">0⇒1達成「5つのステップ」の全貌</div>
<div class="t-sub">ビジネスの基礎から収益化の核心まで。着実に成果を積み上げるための思考法を全公開</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">07</div>
<div class="tokuten-body">
<div class="t-title">0→10万稼ぐマネタイズ戦略（電子書籍）</div>
<div class="t-sub">【再現性重視】堅実に10万円の壁を突破する。大人のための現実的な収益化バイブル</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">08</div>
<div class="tokuten-body">
<div class="t-title">800万再生を叩き出した台本テンプレ</div>
<div class="t-sub">バズる裏側にはロジックがある。人の心を動かし、ファンを増やす動画台本の設計図</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">09</div>
<div class="tokuten-body">
<div class="t-title">マネタイズおすすめ素材素材サイト17選</div>
<div class="t-sub">【完全保存版】デザインで迷わない。収益化を加速させる高品質な素材サイトを厳選</div>
</div>
</div>
<div class="tokuten-item">
<div class="tokuten-num">10</div>
<div class="tokuten-body">
<div class="t-title">マネタイズ全体像 3.0</div>
<div class="t-sub">点と線がつながる。収益発生までの全プロセスを俯瞰して理解する戦略的全体マップ</div>
</div>
</div>
</div>
</section>

<section class="form-sec">
<div class="btn-wrap">
<a href="https://liff.line.me/2006550850-PcLDeNNe?unique_key=RFrkt9&ts=1776055651" class="btn-cta">今すぐ無料で手に入れる</a>
</div>
<p class="form-note">※枠が埋まり次第募集終了となります</p>
</section>

<section class="sec target">
<div class="sec-title">
<span class="sub">AI×SNSスタータープログラム 0»100完全攻略セミナー</span><br>
このような方に<br><span class="pink">おすすめです</span>
</div>
<ul class="checklist">
<li>
<div class="icon">✓</div>
<div><span class="hl">完全初心者からでもAIとSNSを使って0→100を最速で駆け抜けたい方</span></div>
</li>
<li>
<div class="icon">✓</div>
<div>スタータープログラムやWEBマーケティング実務に<span class="hl">AIを導入して業務時間を圧倒的に短縮したい方</span></div>
</li>
<li>
<div class="icon">✓</div>
<div>AIを使って<span class="hl">市場価値を高めたい方</span></div>
</li>
<li>
<div class="icon">✓</div>
<div><span class="hl">会社に依存せず、個人で新たな収入源を作れる人材になりたい方</span></div>
</li>
<li>
<div class="icon">✓</div>
<div>AIに興味はあるけど、<span class="hl">具体的にどう活用すれば良いかわからない方</span></div>
</li>
<li>
<div class="icon">✓</div>
<div>自分・自社のサービスコンセプトにAIを付与して<span class="hl">2026年以降も勝ち続けたい方</span></div>
</li>
<li>
<div class="icon">✓</div>
<div>AI業界で正しくすぐに<span class="hl">実務で活用できるAIリテラシーを身につけたい方</span></div>
</li>
</ul>
</section>

<section class="form-sec">
<div class="btn-wrap">
<a href="https://liff.line.me/2006550850-PcLDeNNe?unique_key=RFrkt9&ts=1776055651" class="btn-cta">今すぐ無料で手に入れる</a>
</div>
<p class="form-note">※枠が埋まり次第募集終了となります</p>
</section>

<section class="sec jisseki">
<div class="sec-title" style="color:#fff;">
すすむ式AI×SNS<br>最先端のマーケティングの<span style="color:#ffcc00;">実績</span>
</div>
<div class="jisseki-sub">実際にAIを活用して実現した成果の一部をお見せします。</div>
<div class="jisseki-list">
<div class="jisseki-item">
<div class="j-num">総フォロワー20万突破</div>
<div class="j-text">顔出しナシでも、全SNS媒体を最速で攻略</div>
</div>
<div class="jisseki-item">
<div class="j-num">年収1,400万達成</div>
<div class="j-text">副業収入で7桁突破。元浪費家から資産2000万へ</div>
</div>
<div class="jisseki-item">
<div class="j-num">万垢を8つ以上再現</div>
<div class="j-text">フォロワー1万人以上のアカウントを仕組みで量産</div>
</div>
<div class="jisseki-item">
<div class="j-num">累計1億再生突破</div>
<div class="j-text">ショート動画で1446万再生のバズなど連発</div>
</div>
<div class="jisseki-item">
<div class="j-num">4か月で全SNSで収益化</div>
<div class="j-text">正しい導線設計による最速マネタイズの再現</div>
</div>
<div class="jisseki-item">
<div class="j-num">個別相談200名越え</div>
<div class="j-text">多くの初心者を直接サポートし、成果へ導く</div>
</div>
</div>
<div class="jisseki-note">
これは全て、今回のセミナーで解説する<br>
<strong style="color:#ff88cc;">すすむ式AI×SNSマーケティングの手法</strong>で実現しています。
</div>
</section>

<section class="sec voice">
<div class="sec-title" style="color:#fff;margin-bottom:8px;">受講生の<span style="color:#ff44cc;">実績・声</span></div>
<div class="voice-grid">
<div class="voice-card"><div class="vc-result">12時間かかっていたセミナーのスライド資料作成が、構成からデザインまで2時間で完了</div></div>
<div class="voice-card"><div class="vc-result">ショート動画の台本30本を1日で一気に作成。初心者でもプロ並みの「刺さる構成」を再現</div></div>
<div class="voice-card"><div class="vc-result">苦手なエクセル関数やマクロ構築をAIで自動化。週5時間のデータ集計作業をわずか15分に短縮</div></div>
<div class="voice-card"><div class="vc-result">「何を書けばいいか」悩む時間が消失。1ヶ月分のSNS投稿アイデアをAIと15分の対話で解消</div></div>
<div class="voice-card"><div class="vc-result">ブログ20記事がたった2時間 Notion×AIで全自動化</div></div>
<div class="voice-card"><div class="vc-result">デザイン経験ゼロの会社員が、AIを活用して「売れるLP（告知ページ）」を2日で制作</div></div>
<div class="voice-card"><div class="vc-result">競合リサーチとターゲット分析が10倍速に。ランチタイムの合間に商品設計の骨子が完成</div></div>
<div class="voice-card"><div class="vc-result">AIによる文章添削で成約率が1.8倍に。強引なセールスなしで商品が売れる導線を構築</div></div>
<div class="voice-card"><div class="vc-result">本業のメール作成や報告書をAIで効率化。浮いた時間を副業のSNS運用に充てて月収プラス10万</div></div>
<div class="voice-card"><div class="vc-result">「デザイナー思考プロンプト」により、クリック率が2倍に跳ね上がるサムネイルを量産</div></div>
<div class="voice-card"><div class="vc-result">AIを「壁打ち相手」にしてコンセプトを磨き、運用開始2ヶ月で高単価案件の成約を達成</div></div>
<div class="voice-card"><div class="vc-result">インフルエンサー総フォロワー10万人 SNS投稿台本フルAI化！</div></div>
<div class="voice-card"><div class="vc-result">「AI×SNS」の型を導入し、残業続きの生活から「夜2時間の副業タイム」を捻出することに成功</div></div>
<div class="voice-card"><div class="vc-result">2000文字記事を音声入力だけで量産</div></div>
<div class="voice-card"><div class="vc-result">メルマガ30本たった2日で完成 99万円×3件成約</div></div>
<div class="voice-card"><div class="vc-result">経理作業 月18時間→1時間に</div></div>
<div class="voice-card"><div class="vc-result">受講たった1ヶ月でローンチ準備が20分の1に</div></div>
</div>
</section>

<section class="sec qna">
<div class="sec-title">
<span class="en">QUESTION & ANSWER</span>
よくある質問
</div>
<div class="qa-list">
<div class="qa-item">
<div class="qa-q"><div class="q-badge">Q</div><div class="q-text">開催日程を教えてください</div></div>
<div class="qa-a">詳しい開催スケジュールは、お申し込み後の専用公式LINEにてご案内しております。</div>
</div>
<div class="qa-item">
<div class="qa-q"><div class="q-badge">Q</div><div class="q-text">セミナーのアーカイブはありますか？</div></div>
<div class="qa-a">アーカイブの配信予定はありません。ライブセミナーのいずれかの日程にご参加ください。</div>
</div>
<div class="qa-item">
<div class="qa-q"><div class="q-badge">Q</div><div class="q-text">無料ですか？</div></div>
<div class="qa-a">はい、セミナー参加は完全無料です。お申し込み後に公式LINEへ登録するだけで参加できます。</div>
</div>
<div class="qa-item">
<div class="qa-q"><div class="q-badge">Q</div><div class="q-text">AI初心者でも大丈夫ですか？</div></div>
<div class="qa-a">はい、安心してください。本セミナーは「AI未経験者が1週間で導入完了できる」という次元に落とし込んだ内容です。難しい専門知識は不要で、AI完全初心者からでも40日で838万円の売上を達成した受講生もいます。</div>
</div>
<div class="qa-item">
<div class="qa-q"><div class="q-badge">Q</div><div class="q-text">スタータープログラム未経験でも参加できますか？</div></div>
<div class="qa-a">もちろんです。セミナーではゼロから億を目指す完全ロードマップを解説します。商品設計から集客・販売・運営まで、全工程をAIで解決する方法を0→100で体系的にお伝えするので、これから始める方にも最適な内容です。</div>
</div>
<div class="qa-item">
<div class="qa-q"><div class="q-badge">Q</div><div class="q-text">内容は特定の仕事・職種でも使えますか？</div></div>
<div class="qa-a">はい、ご活用いただけます。「AIでコンテンツを作る・集客業務を自動化する・SNS業務を効率化する」というノウハウは、コーチ・コンサル・治療ビジネスなどWEB販売事業やSNS普及が必要なあらゆるビジネスに応用可能です。</div>
</div>
<div class="qa-item">
<div class="qa-q"><div class="q-badge">Q</div><div class="q-text">商品・サービスを持っていないクライアントワーカー/裏方ですが大丈夫ですか？</div></div>
<div class="qa-a">もちろん大丈夫です。セミナーで解説するAIを活用したコンテンツ制作・SNS運用・マーケ領域の習熟スキルは、そのままクライアントへの提供サービスとして活用でき、高単価クライアントワークにもつながります。</div>
</div>
</div>
</section>

<section class="sec final-reg">
<div class="msg">
お申込みフォームへ登録後、<br>
<span class="pink">専用公式ラインへ<br>ご案内</span>をお送りさせていただきます。
</div>

<section class="form-sec" style="border-radius:12px; max-width:500px; margin:0 auto;">
<div class="btn-wrap">
<a href="https://liff.line.me/2006550850-PcLDeNNe?unique_key=RFrkt9&ts=1776055651" class="btn-cta">今すぐ無料で手に入れる</a>
</div>
<p class="form-note">※枠が埋まり次第募集終了となります</p>
</section>
</section>

<footer class="footer">
© 2026 すすむ AI×SNSスタータープログラム
</footer>

</div>
</body>
</html>
