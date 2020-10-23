<template>
<div id="app">
  <CommonHeader></CommonHeader>
  <main>
    <div id="eyecatch">
      <div class="eyecatch-title">
        <p>機会ではできない仕事を</p>
      </div>       
      <div class="side-content">
        <div class="side-content-text">
          <p class="date">2019/01/01</p>
          <p class="notice">ニュースタイルがここに入ります。3月の決済報告書</p>
        </div>        
      </div>
      <div class="side-news">
        <p>news</p>
      </div>        
    </div>

    <div id="about" class="wrap">
      <div class="about-img">
        <img src="./assets/img/mission-img.jpg">
      </div>
      <div class="about-content">
        <h2>お客様のために進化する成長企業であり続ける</h2>
        <p>顧客サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。</p>
        <a href="#" class="button">ミッション詳細</a>
      </div>     
    </div>
    
    <div id="service" class="wrap">
      <h2 class="section-title">service</h2>
      <div class="top">
        <div class="top-img">
          <img src="./assets/img/service2.jpg">
        </div>
        <div class="right-button">
            <a href="#" class="button">サービス詳細</a>
        </div>
      </div>

      <div class="bottom">
        <div class="bottom-img">
          <img src="./assets/img/service1.jpg">
        </div>
        <div class="bottom-content">
          <h3>web制作事業</h3>
          <p>コーチングのミッション</p>
          <p>ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、プライダル、飲食店まで多種多様な業種の制作実績があります。</p>
          <div class="right-button">
            <a href="#" class="button">サービス詳細</a>
          </div>
        </div>
      </div>
    </div>

    <div id="company">
      <div class="flex between">
        <div class="left">
          <div class="company-content">
            <h2 class="section-title">company</h2>
            <p>会社概要</p>
          </div>
        </div>

        <div class="right">
          <div class="company-content">
            <h2 class="section-title">result</h2>
            <p>採用情報</p>
          </div>
        </div>
      </div>

      <div class="faq">
        <div class="company-bottom">
          <h2 class="section-title">FAQ</h2>
          <p>良くある質問</p>
        </div>
      </div>
    </div>
      
    <div id="contact">
      <div class="contact-content">
        <h2 class="section-title">contact</h2>
        <p>お問い合わせ</p>
        <div class="large"><p>お気軽にお問い合わせください。</p></div>
        <div class="small"><p>資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事の連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。</p></div>
        <a href="#" class="button">お問い合わせへ</a>
      </div>
    </div>
  </main>
  <CommonFooter></CommonFooter>
</div>
</template>

<script>
import CommonHeader from "./components/CommonHeader.vue";
import CommonFooter from "./components/CommonFooter.vue";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>

<style>
/* リセットcss */
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}

/* 共通のスタイル */

.section-title {
  font-size: 1.4rem;
  font-weight: bold;
  text-align: center;
  font-family:  A-OTF 太ゴB101 Pr6N;
  margin: 0;
  padding: 30px 0;
}

img {
  display: block;
  width: 100%;
}

.flex {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.between {
  justify-content: space-between;
}

.wrap {
  width: 100%;
  margin: 0 auto 50px;
}

.button {
  display: inline-block;
  font-size: 1rem;
  text-decoration: none;
  cursor: pointer;
  transition: 0.4s ease;
  border-radius: 3px;
  padding: 10px 15px;
}

.content-title {
  font-weight: bold;
}

html {
  height: 100%;
}

body {
  height: 100%;
}
/* eyecatch */

#eyecatch {
  height: 600px;
  background: url(./assets/img/eyecatch.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
  width: 100%;
}

.eyecatch-title p {
  position: absolute;
  top: 50%;
  left: 8%;
  font-size: 30px;
  font-weight: bold;
  color: #f2f2f2;
  line-height: 1;
}



.side-content  {
  position: absolute;
  bottom: 0;
  right: 0;
  background-color: #ffffff;
  color: #000;
  padding: 0 300px 16px 0;
}

.side-news  {
  position: absolute;
  color: #f2f2f2;
  background-color: #000;
  padding: 16px 30px;
  bottom: 0;
  right: 0;
}

/* about */
#about {
  height: 400px;
  background-color: #000;
  position: relative;
}


.about-img {
  width: 30%;
  position: relative;
  left: 55%;
  top: 30%;

}

.about-content {
  position: absolute;
  top: 40%;
  left: 15%;
  width: 60%;
}

#about h2, 
#about p {
  color: #f2f2f2;
  margin-bottom: 16px;
}

#about .button {
  color: #000;
  background-color: #fff;
}



/* service */

#service {
  background-color: #e7e7e7;
  position: relative;
  height: 1200px;
  padding: 0;
}

.top-img {
  margin: 0;
  width: 45%;
  position: absolute;
  transform: translatey(-50%);
  top: 25%;
  right: 0;
}

.top-content {
  align-content: center;
  padding: 50px;
  position: absolute;
  transform: translate(-50%, -50%);
  top: 25%;
  left: 45%;
  background-color: #ffffff;
  width: 30%;
}

.top-content p {
  padding: 16px 0;
}

.right-button {
  display: flex;
  justify-content: flex-end;
}

.top-content .button {
  color: #000;
  background-color: #fff;
  border: #000 1px solid;
  
}

.bottom-img {
  margin: 0;
  width: 45%;
  position: absolute;
  transform: translatey(-50%);
  top: 75%;
  left: 0;
}

.bottom-content {
  align-content: center;
  padding: 50px;
  position: absolute;
  transform: translatey(-50%);
  top: 75%;
  right: 25%;
  background-color: #fff;
  width: 30%;
}

.bottom-content p {
  padding: 16px 0;
}

.bottom-content {
  background-color: #fff;
}

.bottom-content .button {
  color: #000;
  background-color: #fff;
  border: #000 1px solid;
  
}

/* company */

#company {
  height: 600px;
  width: 100%;
  background-color: #fff;
}

.left {
  width: 45%;
  height: 250px;
  background-image: url(./assets/img/company.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
}

.left h2,
.left p{
  color: #fff;
}
.left p {
  text-align: center;
}

.right {
  width: 45%;
  height: 250px;
  background-image: url(./assets/img/recruit.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
}

.right h2,
.right p {
  color: #fff;
}




.company-content {
  position: absolute;
  transform: translate(-50%, -50%);
  left: 50%;
  top: 50%;
}

.faq {
  display: flex;
  justify-content: center;
  padding: 60px;
}
.company-bottom {
  background-color: #000;
  margin-top: 50px;
  height: 100px;
  padding: 0;
  width: 60%;
  position: relative;
}

.company-bottom h2,
.company-bottom p{
  color: #fff;
}

.company-bottom h2 {
  text-align: left;
  margin: 0;
  padding: 0;
  position: absolute;
  transform: translatey(-50%);
  top: 50%;
  left: 5%;
}

.company-bottom p {
  position: absolute;
  transform: translate(-50%, -50%);
  top: 50%;
  left: 50%;
}

#contact {
  background-image: url(./assets/img/contact-bg.jpg);
  background-size: cover;
  height: 400px;
  width: 100%;
  position: relative;
}

.contact-content {
  color: #fff;
  text-align: center;
  position: absolute;
  transform: translate(-50%, -50%);
  top: 50%;
  left: 50%;
}

.contact-content p {
  margin-bottom: 30px;
}

#contact .large {
  font-size: 1.6rem;
}

.contact-content h2 {
  margin-bottom: 10px;
  padding: 0;
}

#contact .button {
  color: #fff;
  border: #ffffff 1px solid;
}

</style>


