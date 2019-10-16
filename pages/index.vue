<template>
  <div>
    <header id="header">
      <h1 class="logo">
        <span class="logo-name">Shimada Masato</span>
        <span class="logo-title">MyPortfolio</span>
        <span class="logo-desc">インフラエンジニア シマダマサト</span>
      </h1>
    </header>
  </div>
</template> 

<style>
/* CSS Document */

*,
*:before,
*:after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "ヒラギノ角ゴ Pro W3", "Hiragino Kaku Gothic Pro",
    "游ゴシック Medium", "Yu Gothic Medium", "游ゴシック体", YuGothic,
    "メイリオ", Meiryo, Osaka, "ＭＳ Ｐゴシック", "MS PGothic", sans-serif;
  color: #222;
  font-size: 15px;
  line-height: 1.8;
  letter-spacing: 0.8px;
  animation: fadeIn 2s ease 0s 1 normal;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

img,
video,
object {
  max-width: 100%;
  height: auto;
  border: none;
  vertical-align: bottom;
  display: block;
}

ul,
li {
  list-style: none;
}

/*--------------------------------
　メイン画面
---------------------------------*/

#header {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 550px;
  margin-top: 50px;
}

#header .logo {
  display: block;
}

#header .logo-name {
  display: block;
  font-family: cursive;
  font-size: 32px;
  line-height: 1;
  text-align: center;
  color: #757575;
  margin-bottom: 5px;
}

#header .logo-title {
  font-family: serif;
  font-size: 80px;
  font-weight: normal;
  color: #222;
  line-height: 1;
  letter-spacing: 0.1em;
}

#header .logo-desc {
  font-family: "ヒラギノ明朝 Pro", "Hiragino Mincho Pro", "游明朝体",
    "Yu Mincho", YuMincho, "MS P明朝", "MS PMincho", serif;
  display: block;
  font-size: 18px;
  letter-spacing: 0.2em;
  text-align: center;
  margin-top: 10px;
}

#footer .footer-link ul {
  font-family: "Cormorant Garamond", serif;
  letter-spacing: 0.1em;
  text-transform: lowercase;
  margin-bottom: 30px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

#footer .footer-link li {
  font-size: 12px;
  padding: 0 20px;
}

#footer .footer-link li a {
  color: #fff;
  font-weight: bold;
}

#footer .copyright {
  font-size: 10px;
  color: #8c8c8c;
  text-align: center;
}

/*media Queries 767
----------------------------------------------------*/

@media screen and (max-width: 767px) {
  body {
    font-size: 13px;
    line-height: 1.7;
  }

  #header {
    height: 60vh;
  }

  #header .logo-title {
    font-size: 40px;
  }

  #header .logo-name {
    font-size: 16px;
  }

  #header .logo-desc {
    font-size: 10px;
  }
}
</style>