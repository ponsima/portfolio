<template>
  <v-app>
    <section id="contact">
      <div class="wrapper">
        <div class="title-block">
          <h1 class="font-weight-light display-3">Accounts</h1>
        </div>
        <div class="contact-wrapper">
          <div class="contact-list">
            <ul>
              <li>
                <a href="https://github.com/ponsima" class="display-1 font-weight-regular">GitHub</a>
              </li>

              <li>
                <a href="https://qiita.com/ponsima" class="display-1 font-weight-regular">Qiita</a>
              </li>

              <li>
                <a
                  href="https://www.wantedly.com/users/103275557"
                  class="display-1 font-weight-regular"
                >Wantedly</a>
              </li>
              <p class="text">
                &emsp;ご連絡の際は、下記のメールアドレスをクリックし
                「御社名」「お名前」「メールアドレス」「内容」を添えて送信ください。
              </p>
              <a href="mailto:masato.cloudInfra@gmail.com">
                <v-icon large>mail</v-icon>
                <span class="mail font-weight-medium">masato.cloudInfra@gmail.com</span>
              </a>
            </ul>
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

section .text {
  margin-top: 3em;
  line-height: 1.5em;
}

section .mail {
  padding-left: 0.5em;
  font-size: 1.5em;
}

section .wrapper > .contact-wrapper > .contact-list > ul > a {
  text-decoration: none;
  text-align: center;
}

#contact .contact-list {
  padding: 10px 0;
}

#contact .contact-list ul {
  width: 45%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-self: center;
  font-size: 18px;
}

#contact .contact-list li {
  text-align: center;
  line-height: 3.5em;
}

#contact .contact-list li a {
  color: #0095eb;
}

#contact .contact-list li img {
  width: 60px;
  margin: 0 auto 5px;
}

.mail {
  color: #0095eb;
}

@media screen and (max-width: 767px) {
  section .wrapper {
    padding: 80px 10px;
  }

  section .title-block {
    text-align: center;
    margin-bottom: 30px;
  }

  section .text {
    font-size: 14px;
  }

  section .mail {
    padding-left: 0.5em;
    font-size: 1em;
  }

  #contact .contact-list ul {
    margin-top: 1.25em;
    width: 100%;
  }

  #contact .contact-list li {
    flex-basis: 30%;
    text-align: center;
    margin: 0 auto;
  }

  #contact .contact-list li img {
    width: 30px;
  }

  #contact .contact-list-desc {
    font-size: 12px;
  }
}
</style>