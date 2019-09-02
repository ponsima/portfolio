<template>
  <v-app>
    <section id="profile">
      <div class="wrapper">
        <div class="title-block">
          <h1 class="font-weight-light display-3">Profile</h1>
        </div>
        <div class="two-column-wrapper">
          <div class="two-column-image">
            <img src="~/assets/masato.png" alt="profile_image" />
            <p class="section-desc font-weight-light headline">Shimada Masato</p>
          </div>
          <div class="two-column-desc">
            <div class="font-weight-thin headline">プロフィール</div>
            <p class="text">
              &emsp;はじめまして。HAL東京 IT学部 高度情報学科を専攻している4年制3年の島田 雅人と申します。(21卒予定)
              <br />&emsp;将来はインフラエンジニアを志望しており、サーバやネットワーク、クラウドからオンプレミスまでレイヤを問わず対応できることを目標とし、日々勉強しています。
              <br />&emsp;自分の知見を広めるため、勉強会にも積極的に参加し、最近では『AWSでWebサービスのインフラとネットワーク構築技術』,『FirebaseでTODOリストの実装』,『Wireshark&パケット解析』など様々な勉強会に出席しています。
            </p>
            <h2 class="font-weight-thin headline">受賞歴</h2>
            <p class="body-1 font-weight-thin">2018</p>
            <p>&emsp;進級制作展「HAL EVENT WEEK 2018」意欲賞</p>
            <p>&emsp;１ヵ年精勤賞</p>
            <p></p>
            <p class="body-1 font-weight-thin">2019</p>
            <p>&emsp;進級制作展「HAL EVENT WEEK 2019」銅賞</p>
            <p>&emsp;１ヵ年皆勤賞</p>
          </div>
        </div>
      </div>
    </section>
  </v-app>
</template>


<style scoped>
* {
  color: #333;
}

section .wrapper {
  padding: 80px 10px;
}

section .title-block {
  text-align: center;
  margin-bottom: 30px;
}

section .display-3 {
  font-weight: BLACK;
}

section .headline {
  text-align: center;
  padding-bottom: 0.5em;
}

section .section-desc {
  margin-top: 30px;
  text-align: center;
}

section .text {
  margin-bottom: 7vh;
  line-height: 1.75em;
  padding-left: 1em;
}

.two-column-wrapper {
  width: 80%;
  margin: 0 auto;
  padding: 20px 0;
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
}

.two-column-image {
  width: 33%;
}

.two-column-image img {
  margin: 0 auto;
}

.two-column-desc {
  width: 62%;
}

#profile {
  margin-bottom: 80px;
}

#profile .two-column-image {
  width: 33%;
}

#profile .two-column-desc {
  width: 62%;
}

@media screen and (max-width: 767px) {
  section .section-desc {
    font-size: 25px;
  }

  section .wrapper {
    padding: 80px 10px;
  }

  section .title-block {
    text-align: center;
    margin-bottom: 30px;
  }

  section .title {
    letter-spacing: 0.2em;
    display: inline-block;
    font-size: 36px;
    line-height: 1;
    margin-bottom: 10px;
    color: #222;
  }

  #profile .two-column-wrapper {
    width: 100%;
    flex-wrap: wrap;
  }

  #profile .two-column-image {
    width: 50%;
    margin: 0 auto 20px;
  }

  #profile .two-column-desc {
    width: 100%;
  }
}
</style>


