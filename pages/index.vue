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
      <section>
        <v-parallax src="assets/hero.jpeg" height="600">
          <v-layout column align-center justify-center class="white--text">
            <img src="assets/vuetify.png" alt="Vuetify.js" height="200" />
            <h1 class="white--text mb-2 display-1 text-center">
              Parallax Template
            </h1>
            <div class="subheading mb-4 text-center">Powered by Vuetify</div>
            <v-btn
              class="mt-12"
              color="blue lighten-2"
              dark
              large
              href="/pre-made-themes"
            >
              Get Started
            </v-btn>
          </v-layout>
        </v-parallax>
      </section>
      <section>
        <v-layout column wrap class="my-12" align-center>
          <v-flex xs12 sm4 class="my-4">
            <div class="text-center">
              <h2 class="headline">The best way to start developing</h2>
              <span class="subheading">
                Cras facilisis mi vitae nunc
              </span>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="blue--text text--lighten-2"
                        >mdi-palette</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-center">Demo</div>
                    </v-card-title>
                    <v-card-text>
                      Stellenanzeige veröffentlichen. Auf die Anzeige bewerben.
                      Und dann die Bewerbung bearbeiten.
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="blue--text text--lighten-2"
                        >mdi-flash</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">Download</div>
                    </v-card-title>
                    <v-card-text>
                      Einfach installieren und nutzen. Download bei Github
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="blue--text text--lighten-2"
                        >mdi-wrench</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-center">
                        FAQ
                      </div>
                    </v-card-title>
                    <v-card-text>
                      Status? Wer steht dahinter? Wo geht die Reise hin?
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md3>
                  <v-card flat class="transparent">
                    <v-card-text class="text-center">
                      <v-icon x-large class="blue--text text--lighten-2"
                        >mdi-wrench</v-icon
                      >
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-center">
                        Mitmachen
                      </div>
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
        </v-layout>
      </section>
      <section>
        <v-parallax src="assets/section.jpg" height="380">
          <v-layout column align-center justify-center>
            <div class="headline white--text mb-4 text-center">
              Web development has never been easier
            </div>
            <em>Kick-start your application today</em>
            <v-btn
              class="mt-12"
              color="blue lighten-2"
              dark
              large
              href="/pre-made-themes"
            >
              Get Started
            </v-btn>
          </v-layout>
        </v-parallax>
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
  font-size: 3.5rem !important;
  font-weight: 300;
  line-height: 3.5rem;
  letter-spacing: normal !important;
  font-family: Lato, sans-serif !important;
  color: #555;
}
.v-application h4 {
  font-size: 1.5rem !important;
  font-weight: 300;
  line-height: 2rem;
  letter-spacing: normal !important;
  font-family: Lato, sans-serif !important;
  margin-top: 35px;
}
.subclaim {
}
</style>
