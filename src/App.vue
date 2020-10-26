<template>
  <div id="app">
    <CommonHeader></CommonHeader>
    <main>
    <div class="main-img">
      <img src="./assets/eyecatch.jpg">
      <h1 class="main-title">機械ではできない仕事を</h1>
      <div class="news-box">
        <div class="news-title">
          <p>2020/10/10</p>
          <h6>ニュースタイトルがここに入ります。3月の決算報告書</h6>
        </div>
        <p class="news-tug">news</p>
      </div>
    </div>

    <div class="mission">
      <div class="mission-top">
        <div class="mission-left">
          <h3>お客様のために進化する成長企業であり続ける</h3>
          <p>顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。</p>
          <p class="mission-btn">ミッション詳細
          </p>
        </div>
        <div class="mission-right">
        <img src="./assets/mission-img.jpg">
        </div>
      </div>
    </div>

    <div class="service">
      <div class="service-title">service</div>
      <div class="service-top">
        <img src="./assets/service2.jpg">
        <div class="service-top-box">
          <h3>web制作事業</h3>
          <p class="servise-subtxt">コーチングのミッション</p>
          <p class="service-text">ユーザーが求めるものを分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります</p>
          <h6 class="service-btn">サービス詳細</h6>
        </div>
      </div>

      <div class="service-bottom">
        <img src="./assets/service1.jpg">
        <div class="service-bottom-box">
          <h3>web制作事業</h3>
          <p class="servise-subtxt">コーチングのミッション</p>
          <p class="service-text">ユーザーが求めるものを分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります</p>
          <h6 class="service-btn">サービス詳細</h6>
        </div>
      </div>
    </div>
    <div class="infomation">
      <div class="infomation-top">
        <div class="company">
          <img src="./assets/company.jpeg">
          <div class="company-txt">
           <h4>company</h4>
           <p>会社概要</p>
          </div>
        </div>
        <div class="recruit">
          <img src="./assets/recruit.jpg">
          <div class="recruit-txt">
           <h4>recruit</h4>
           <p>採用情報</p>
          </div>
        </div>
      </div>
      <div class="question">
        <h3>FAQ</h3>
        <p>良くある質問</p>
      </div>
    </div>

    <div class="contact">
      <img src="./assets/contact-bg.jpg">
      <div class="contact-txt">
      <h3>contact</h3>
      <h5>お問い合わせ</h5>
      <h1>お気軽にお問い合わせください。</h1>
      <h6>資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事の連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。</h6>
      <p>お問い合わせへ</p>
      </div>
    </div>
    </main>
    <CommonFooter></CommonFooter>
  </div>
</template>

<script>
import CommonHeader from "./components/CommonHeader.vue";
import CommonFooter from "./components/CommonFooter.vue";
export default{
  components:{
    CommonHeader,
    CommonFooter
  }
};
</script>

<style scoped>
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
 /* ここまでがリセットCSS */

 /* ここからが共通のCSS */

.section-title {
  font-size: 30px;
  font-weight: bold;
  margin: 30px 0;
  text-align: center;
}

img {
  display: block;
  width: 100%;
}

.wrap {
  width: 80%;
  margin: 0 auto 50px;
}

.flex {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.between {
  justify-content: space-between;
}

.around {
  justify-content: space-around;
}

.main-img {
  position: relative;
}

.main-title {
  color: white;
  font-size: 35px;
  font-weight: bold;
  position: absolute;
  top: 50%;
  left: 60px;
}

.news-box {
  display: flex;
  position: absolute;
  top: 100%;
  left: 100%;
  transform: translate(-100%, -100%);
  height: 35px;
  margin: 0 0 0 auto;
}

.news-title {
  background-color: white;
  width: 500px;
}

.news-title p,
h6 {
  font-size: 10px;
  font-weight: normal;
}

.news-title h6 {
  margin-left: 10px;
  margin-top: 5px;
}

.news-tug {
  background-color: black;
  color: white;
  font-size: 10px;
  line-height: 35px;
  width: 80px;
  text-align: center;
}

.mission {
  background-color: white;
  height: 500px;
}

.mission-top {
  background-color: black;
  height: 400px;
  position: relative;
}

.mission-left {
  color: white;
  width: 50%;
  position: absolute;
  z-index: 20;
  top:40%;
  left: 10%;
  transform: translateY(-40%);
}

.mission-left h3 {
  font-size: 20px;
  margin-bottom: 5px;
}

.mission-left p {
  margin-top: 15px;
  font-size: 12px;
}

.mission-btn {
  width: 120px;
  height: 25px;
  background-color: white;
  color: #000;
  border: #000;
  text-align: center;
  line-height: 25px;
  cursor: pointer;
}

.mission-right {
  width: 500px;
  height: 350px;
  position: absolute;
  top: 30%;
  left: 50%;
  z-index: 10;
}
.mission-right img {
  width: 100%;
  height: 100%;
}

.service {
  background-color: #cccccc;
  height: 100%;
}

.service-title {
  font-weight: bold;
  text-align: center;
  margin-top: 5px;
  margin-bottom: 5px;
  font-size: 1.2rem;
}

.service-top {
  display: flex;
  position: relative;
}

.service-top img {
  width: 50%;
  height: auto;
  margin: 10px 0 0 auto;
}

.service-top-box {
  background-color: white;
  width: 450px;
  height: 300px;
  position: absolute;
  top: 20%;
  left: 25%;
}

.service h3 {
  font-weight: bold;
  margin-top: 70px;
  margin-left: 35px;
}
.service p {
  font-size: 12px;
  margin-top: 10px;
  margin-left: 35px;
  margin-right: 35px;
}

.service-btn {
  border: solid 1px black;
  text-align: center;
  line-height: 20px;
  width: 100px;
  height: 20px;
  cursor: pointer;
  margin: 10px 35px 0 auto;
}
.service-bottom {
  display: flex;
  position: relative;
  margin-top: 100px;
}
.service-bottom-box {
  background-color: white;
  width: 450px;
  height: 300px;
  position: absolute;
  top: 20%;
  left: 40%;
}

.service-bottom img {
  width: 50%;
  height: auto;
  margin: 10px auto 0 0;
}

.infomation {
  background-color: white;
  color: white;
  height: auto;
  margin-bottom: 50px;
}

.infomation-top {
  width: 80%;
  height: 150px;
  display: flex;
  margin: 0 auto;
  justify-content: space-between;
  margin-top: 50px;
}

.company {
  display: flex;
  width: 48%;
  position: relative;
}

.company-txt {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.recruit {
  display: flex;
  width: 48%;
  position: relative;
}

.recruit-txt {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.question {
  width: 70%;
  height: 100px;
  background-color: black;
  margin: 50px auto;
  display: flex;
  line-height: 100px;
  position: relative;
}

.question h3 {
  margin-left: 10px;
}
.question p {
  font-size: 10px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.contact {
  position: relative;
}

.contact-txt {
  text-align: center;
  color: white;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.contact h3 {
  font-size: 20px;
}

.contact h5 {
  font-size: 15px;
  font-weight: normal;
}

.contact h1 {
  font-size: 24px;
  margin: 20px auto;
}

.contact h6 {
  font-size: 10px;
  margin: 20px auto;
  width: auto;
}

.contact p {
  font-size: 10px;
  border: solid 1px white;
  cursor: pointer;
  width: 100px;
  height: 20px;
  line-height: 20px;
  margin: 0 auto;
}
@media screen and (max-width:768px){
  .news-box{
    width: 100%;
  }

  .mission{
    height: 300px;
  }

  .mission-top{
    height: 250px;
  }

  .mission-left{
    width: 80%;
    margin: 0 auto;
    padding-top: 35%;
    position: static;
  }

  .mission-right{
    width: 30%;
    height: auto;
    position: absolute;
    top:80%;
    left: 65%;
  }

  .service{
    height: 100%;
  }

  .service-top{
    flex-wrap: wrap;
  }

  .service-bottom{
    flex-wrap: wrap;
  }

  .service img{
    width: 80%;
    margin: 0 auto;
  }

  .service-top-box{
    width: 80%;
    height: 100%;
    position: static;
    margin: 0 auto;
    padding-bottom: 50px;

  }

   .service-bottom-box{
    width: 80%;
    height: 100%;
    position: static;
    margin: 0 auto;
    margin-bottom: 20px;
    padding-bottom: 50px;
  }

  .infomation-top{
    width: 100%;
    height: 100%;
   display: block;
  }
  .company{
    width: 100%;
  }
  .recruit{
    width: 100%;
  }

  .question{
    width: 100%;
  }

  .contact-txt{
    width: 80%;
  }
}
</style>
