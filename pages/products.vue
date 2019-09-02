<template>
  <v-app>
    <section id="feature">
      <div class="wrapper">
        <div class="title-block">
          <h1 class="font-weight-light display-3">Products</h1>
        </div>
        <div class="two-column-wrapper">
          <div class="two-column-image">
            <img src="~/assets/product/s_flovis(2).png" alt />
          </div>
          <div class="two-column-desc">
            <p>
              作品タイトル：
              <span class="title font-weight-light">FLOVIS</span>
            </p>
            <p>概要：花束販売ECサイト</p>
            <p>担当：チームリーダ, コーディング</p>
            <p>制作期間：約4~5ヶ月</p>
            <p>使用言語・技術：</p>
            <p class="text">HTML, CSS, PHP(Laravel), JS(jQuery), MySQL, Docker</p>
            <p>『FLOVIS』とは：</p>
            <p class="text">『花束を買いたいけど恥ずかしい、、、』や『花屋に行く時間がない！！』というような悩みを解決できる花束販売ECサイトです。</p>
            <p>こだわったポイント：</p>
            <ul>
              <li>
                <p>直感的でわかりやすい操作性</p>
              </li>
              <li>
                <p>ビジュアル重視できれいなレイアウト</p>
              </li>
            </ul>
          </div>
        </div>

        <div class="two-column-wrapper">
          <div class="two-column-image">
            <img src="~/assets/product/portfoliosite_toppage.png" alt />
          </div>
          <div class="two-column-desc">
            <p>
              作品タイトル：
              <span class="title font-weight-light">MyPortfolio</span>
            </p>
            <p>制作期間：約1ヵ月</p>
            <p>使用言語・技術：</p>
            <p class="text">HTML, CSS, Nuxt.js, Vuetify, Docker</p>
            <p>概要：</p>
            <p class="text">
              今後の就職活動に活かせると思い、ポートフォリオサイトを作成しました。
              <br />
              <br />
              <span
                class="font-weight-light body-1"
              >フロントはNuxt.jsでSPAやPWAに対応しています。スマホでご覧の方はぜひ「ホーム画面に追加」をお試しください。</span>
              <br />
              <br />
              <span
                class="font-weight-light"
              >デザインはVuetifyを使いマテリアルデザインで仕上げました。デザインが苦手な僕でも使いやすくて気に入っています。</span>
              <br />
              <br />
              <span
                class="font-weight-light"
              >デプロイ環境はGCPのCloud Runを使いました。実際にDockerfileを書きコンテナ化してデプロイしました。</span>
            </p>
          </div>
        </div>
      </div>
    </section>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: "FLOVIS",
      outline: "花販売ECサイト",
      charge: "チームリーダ, コーディング",
      month: "3〜4ヶ月"
    };
  }
};
</script>

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

section > .wrapper > .two-column-wrapper > .two-column-desc > ul > li {
  list-style: disc;
}

section > .wrapper > .two-column-wrapper > .two-column-desc > ul {
  margin-left: 1.5em;
}

p {
  line-height: 1.75em;
}

section .text {
  padding-left: 1.5em;
}

section .desc {
  text-align: center;
}

.two-column-wrapper {
  width: 80%;
  margin: 0 auto 7.5vh auto;
  padding: 20px 0;
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
}

.two-column-image {
  width: 33%;
}

.two-column-image img {
  border: 1px #000 solid;
  margin: 0 auto;
}

.two-column-desc {
  width: 62%;
}

.detail {
  font-size: 16px;
}

#feature .two-column-image {
  width: 48%;
}

#feature .two-column-desc {
  width: 48%;
}

@media screen and (max-width: 767px) {
  section .wrapper {
    padding: 80px 15px;
  }

  section .section-title-block {
    margin-bottom: 10px;
  }

  section .section-title {
    font-size: 32px;
  }

  #feature .two-column-wrapper {
    width: 100%;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  #feature .two-column-image {
    width: 90%;
    margin: 0 auto 20px;
  }

  #feature .two-column-desc {
    width: 100%;
  }
}
</style>

