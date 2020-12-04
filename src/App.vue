<template>
  <v-app class="ma-0 pa-0 pb-0 mb-0">
    <v-main>
      <v-img
        src="@/assets/background.png"
        alt="Background Image"
        height="100vh"
      >
        <v-app-bar flat background color="transparent">
          <v-img
            alt="PaveWay Technologies Logo"
            class="mr-1 mt-2"
            contain
            src="@/assets/pavewaylogo.png"
            transition="scale-transition"
            height="70"
            width="70"
            position="end"
          >
          </v-img>
            <!-- <div class="blue--text" align end>
              Presents
            </div> -->

          <v-spacer></v-spacer>

          <v-dialog v-model="dialog" width="500">
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                class="blue--text darken"
                href="#"
                text
                v-bind="attrs"
                v-on="on"
              >
                <span class="mr-1 darken">About</span>
                <v-icon></v-icon>
              </v-btn>
            </template>
            <v-card>
              <v-card-title class="headline blue lighten-2">
                About Us
              </v-card-title>

              <v-card-text>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </v-card-text>

              <v-divider></v-divider>

              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn color="blue" text @click="dialog = false">
                  close
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-dialog>
          <v-dialog v-model="dialog" width="500">
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                class="blue--text darken"
                href="#"
                text
                v-bind="attrs"
                v-on="on"
              >
                <span class="mr-1 darken">Mission</span>
                <v-icon></v-icon>
              </v-btn>
            </template>
            <v-card>
              <v-card-title class="headline blue lighten-2">
                The Mission
              </v-card-title>

              <v-card-text>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </v-card-text>

              <v-divider></v-divider>

              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn color="blue" text @click="dialog = false">
                  Close
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-dialog>
          <v-dialog v-model="dialog" width="500">
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                class="blue--text darken"
                href="#"
                text
                v-bind="attrs"
                v-on="on"
              >
                <span class="mr-1 darken">Vission</span>
                <v-icon></v-icon>
              </v-btn>
            </template>
            <v-card>
              <v-card-title class="headline blue lighten-2">
                The Code Storm Vision
              </v-card-title>

              <v-card-text>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </v-card-text>

              <v-divider></v-divider>

              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn color="blue" text @click="dialog = false">
                  Close
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-dialog>
        </v-app-bar>
      </v-img>
    </v-main>
    <v-footer>
          <flip-countdown deadline="2021-01-10 00:00:00"></flip-countdown>
    </v-footer>
  </v-app>
</template>

<script>
import FlipCountdown from "vue2-flip-countdown";

export default {
  components: { FlipCountdown },
};
</script>
