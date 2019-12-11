<template>
  <div id="app">
    <v-content>
      <div style="text-align: center">
        <h1 class="headline">Jobs & Bewerber</h1>
        <h4>
          Bewerbermanagement System. Lebenslauf Datenbank. Anzeigen Management.
          <div class="subclaim">
            Dezentral. Fokus auf Privatsphäre. Free and Open Source
          </div>
        </h4>
      </div>
      <section style="background: #3787D0; margin-top: 35px;">
        <div class="bannerContent">
          <v-flex xs12 xl12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="orange--text text--lighten-2"
                        >mdi-monitor</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <h2>Demo</h2>
                    </v-card-title>
                    <v-card-text>
                      <a href="/test"
                        >Stellenanzeige veröffentlichen. Auf die Anzeige
                        bewerben. Und dann die Bewerbung bearbeiten.</a
                      >
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="orange--text text--lighten-2"
                        >mdi-download</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <h2>Download</h2>
                    </v-card-title>
                    <v-card-text>
                      Einfach installieren und nutzen. Download bei Github
                      <br />
                      <br />
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="orange--text text--lighten-2"
                        >mdi-web</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <h2>
                        FAQ
                      </h2>
                    </v-card-title>
                    <v-card-text>
                      Status? Wer steht dahinter? Wo geht die Reise hin?
                      <br />
                      <br />
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="orange--text text--lighten-2"
                        >mdi-flower</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <h2>
                        Mitmachen
                      </h2>
                    </v-card-title>
                    <v-card-text>
                      Es fehlt noch viel. Am wichtigsten ist jetzt Dein
                      Feedback. Einfach per Mail an contact@yawik.org
                    </v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </div>
      </section>
      <section>
        <div class="bannerContentText">
          <v-layout column wrap class="my-12">
            <div class="text-titel">
              Let’s create a modern Frontend for YAWIK
            </div>
            <span>by YAWIK on 8. December 2019 • 0 Comments</span>
            <div class="text-content">
              Das Layout von YAWIK kann angepasst werden. Aber serverseitige
              Anpassungen des Layouts sind im Vergleich zu clientseitigen zu
              aufwendig. Wir empfehlen die Generierung des Layouts mit einem
              modernen Component Framework. Wir haben gezeigt, wie man in Quasar
              die Jobsuche einbaut. Wir haben gezeigt wie man ein
              Eingabeformular für jobs gestalten kann. Wir haben gezeigt, wie
              ein Bewerbungsformular aussehen könnte
            </div>
            <div class="text-titel">
              YAWIK Widget per VUE
            </div>
            <span>by YAWIK on 31. October 2019 • 0 Comments</span>
            <div class="text-content">
              ein Bereich für eine Jobsuche im Corporate Design ist für viele
              Unternehmen wichtig. Wie schön wäre es, wenn man einen solchen
              Bereich einfach per Widget in eine Homepage einbetten könnte. Und
              es geht.
            </div>
            <div class="text-titel">Update Yawik via Composer</div>
            <span>by YAWIK on 23. November 2018 • 0 Comments</span>
            <div class="text-content">
              wir kommen der Sache näher. Wir haben gerade die PHP7 Version von
              unserem Demo per Composer aktualisiert. Das ist einfach cool …
              Aber bitte nicht als “root” nachmachen. Das macht man
              normalerweise nicht. Und es führt am Ende zum Problem, dass die
              assets per npm nicht korrekt verteilt werden.
            </div>
            <div class="text-titel">YAWIK läuft jetzt mit PHP7</div>
            <span>by YAWIK on 12. October 2018 • 0 Comments</span>
            <div class="text-content">
              Es gibt jetzt 2 Demos. Das bekannte Demo unter
              https://yawik.org/demo/ läuft mit wie immer mit der letzten
              Version aus dem develop Branch mit php 5.6. Unter
              https://php7.yawik.org/ läuft die letzte Version mit php 7.2. Die
              automatisierten Tests laufen jetzt auf Travis für die Versionen
              5.6, 7.0, 7.1 und 7.2.
            </div>
            <div class="text-titel">YAWIK 0.31.1 wurde veröffentlicht</div>
            <span>by YAWIK on 11. October 2018 • 0 Comments</span>
            <div class="text-content">
              wir hatten ganz vergessen zu erwähnen, dass es die Version 0.31.1
              gibt. Die Version bringt Firmenprofile und diverse Details. Das
              wichtigste ist die Möglichkeit der Zusammenarbeit mit mongo 3.6.
            </div>
            <div class="text-titel">Unser Demo verwendet jetzt ZF3</div>
            <span>by YAWIK on 29. September 2017 • 0 Comments</span>
            <div class="text-content">
              Wir haben es geschafft. Unser Demo und die Module Orders,
              CompanyRegistration, Solr und JobsByMail laufen jetzt unter ZF3.
              Die Aktualisierung hat länger gedauert, als wir es uns erwünscht
              hatten, aber es musste sein. Vielen Dank an die Entwickler und
              Ihre Geduld. Jetzt können wir uns wieder um die Umsetzung neuer
              Funktioen kümmern. Unser Fokus liegt derzeit auf der Eingabe und…
            </div>
            <div class="text-titel">YAWIK on ZF3 is coming</div>
            <span>by YAWIK on 17. July 2017 • 0 Comments</span>
            <div class="text-content">
              Unser Demo ist jetzt auch unter ZF3 erreichbar. Das Upgrade war
              aufwendiger, als erwartet. Testet die Funktionen und sendet Bug
              Reports. Alle externen Module (Xing, CompanyRegistration, Orders,
              etc) sind noch nicht migriert. Das wird aber im Vergleich zur
              bisherigen Migration eine Kleinigkeit.
            </div>
            <div class="text-titel">YAWIK 0.29.2 wurde veröffentlicht</div>
            <span>by YAWIK on 15. June 2017 • 0 Comments</span>
            <div class="text-content">
              Wer unsere Release Notes verfolgt, wird es bereits wissen. Aber
              weil der eine oder andere Personaler sich selten auf Github
              bewegt, fasse ich die wesentlichen Änderungen seit 0.26 zusammen.
              Und weil sich die Neuerungen in unseren Release Notes häufig
              technisch klingen, versuche ich die 3 wichtigsten Punkte zu
              übersetzen. “Facet Search” (seit 0.27) ist so ein Highlight,
              Gemeint ist hierbei die…
            </div>
            <div class="text-titel">YAWIK hat ein neues Forum</div>
            <span>by YAWIK on 14. May 2017 • 0 Comments</span>
            <div class="text-content">
              Wir haben ein neues Forum. Open Source und das Personalwesen haben
              auf den ersten Blick wenig Berührungspunkte. Aber eigentlich ist
              es genau anders. Open Source sollte ein Vorbild (nicht nur) für
              das Personalwesen sein. Ein Beispiel: Im Personalwesen gibt es den
              Bereich “interne Kommunikation”. Also das Thema, wie man
              Mitarbeiterbindung durch eine Verbesserung der Kommunikation
              zwischen Mitarbeitern erhöht. Es geht…
            </div>
            <div class="text-titel">
              Yawik.org und Yawik.com – Was ist der Unterschied?
            </div>
            <span>by Tilman Weigel on 17. January 2017 • 0 Comments</span>
            <div class="text-content" style="margin-bottom: 0px;">
              Unter Yawik.org finden sich alle wichtigen Informationen zur
              freien Bewerbermanagement- und Personalrekrutierungs-Software
              Yawik. Was aber ist Yawik.com? Und was haben beide miteinander zu
              tun? Um es vorwegzunehmen, beide haben etwas miteinander zu tun,
              bieten aber unterschiedliche Angebote.
            </div>
          </v-layout>
        </div>
        <div class="btnMargin">
          <v-col class="text-center" cols="12" sm="4" lg="12">
            <v-btn
              class="mt-12"
              color="#5498d7"
              depressed
              dark
              large
              href="/pre-made-themes"
            >
              Read more
            </v-btn>
          </v-col>
        </div>
      </section>
    </v-content>
  </div>
</template>
<style scoped>
.v-application {
  font-family: Lato;
  line-height: 1.5;
  font-size: 20px;
}
.v-application .headline {
  font-size: 4rem !important;
  font-weight: 300;
  line-height: 3.5rem;
  letter-spacing: normal !important;
  font-family: Lato, sans-serif !important;
  color: #555;
}
.v-application h2 {
  font-size: 2.5rem !important;
  font-weight: 300;
  line-height: 2.5rem;
  letter-spacing: normal !important;
  font-family: Lato, sans-serif !important;
  color: #fff;
}
.v-application h4 {
  font-size: 1.5rem !important;
  font-weight: 300;
  line-height: 2rem;
  letter-spacing: normal !important;
  font-family: Lato, sans-serif !important;
  margin-top: 35px;
}
.v-card__text {
  color: #fff !important;
  font-family: Lato, sans-serif !important;
}
.text-content {
  color: #555 !important;
  font-family: Lato, sans-serif !important;
  font-size: 1.2rem;
  font-weight: 300;
  margin-bottom: 40px;
}
.text-titel {
  font-size: 3rem;
  line-height: 3rem;
  font-weight: 300;
  font-family: Lato, sans-serif !important;
  color: #555 !important;
  margin-bottom: 10px;
}
.container {
  padding: 0 !important;
  max-width: 100% !important;
  color: #555 !important;
}
.bannerContent {
  width: 80%;
  margin: 0 auto;
  color: #555 !important;
}
.bannerContentText {
  width: 50%;
  margin: 0 auto;
}
.bannerContentText span {
  font-size: 1rem;
  color: #777;
  margin-bottom: 15px;
}
.btnMargin {
  margin-top: -30px;
}
.mt-12 {
  font-family: Lato, sans-serif !important;
}
.v-icon {
  font-size: 58px !important;
}
@media (min-width: 1264px) {
  .container {
    max-width: 100% !important;
  }
}
@media (min-width: 1904px) {
  .container {
    max-width: 100% !important;
  }
}
@media (min-width: 960px) {
  .container {
    max-width: 100% !important;
  }
}
@media (max-width: 480px) {
  .bannerContentText {
    width: 92%;
  }
}
</style>
