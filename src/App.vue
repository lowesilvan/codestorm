<template>
  <v-app class="ma-0 pt-0 pb-0 mb-0">
    <v-main class="ma-0 pt-0">
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
          <v-spacer></v-spacer>
          <span class="blue--text font-weight-bold"
            >Paveway Technologies Inc Presents</span
          >
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
                <v-btn color="blue" text @click="dialog = false"> close </v-btn>
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
                <v-btn color="blue" text @click="dialog = false"> Close </v-btn>
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
                <v-btn color="blue" text @click="dialog = false"> Close </v-btn>
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
                <span class="mr-1 darken">Objective</span>
                <v-icon></v-icon>
              </v-btn>
            </template>
            <v-card>
              <v-card-title class="headline blue lighten-2">
                Our Objective
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
                <v-btn color="blue" text @click="dialog = false"> Close </v-btn>
              </v-card-actions>
            </v-card>
          </v-dialog>
        </v-app-bar>
        <v-container fluid fill height>
          <v-row no-gutters class="fill-height" justify="top">
            <v-col align="center" class="pt-0">
              <span class="heading display-4 font-weight-bold amber--text glow"
                >&lt;C o d e S t o r m/&gt;</span
              >
              <br />
              <span class="subheading basil--text font-weight-heavy display-1"
                >"The Next Generation Techies"</span
              >
            </v-col>
          </v-row>
          <v-row
            align-self="baseline"
            justify="baseline"
            no-gutters
            class="pb-0"
          >
            <v-col cols="4" d-flex class="pb-0">
              <v-card
                class="mx-auto pt-0 pb-0 pa-0 ma-0 mb-0"
                max-width="344"
                flat
                hover
                max-height="auto"
              >
                <v-img src="@/assets/avatar.png" height="150px"></v-img>

                <v-card-title>&lt;Host/&gt; Mbirriambang Alain </v-card-title>

                <v-card-subtitle>
                  CTO, PavewayTechnologies Inc
                </v-card-subtitle>

                <v-card-actions>
                  <v-btn text color="teal accent-4" @click="reveal = true">
                    Learn More
                  </v-btn>
                </v-card-actions>

                <v-expand-transition>
                  <v-card
                    v-if="reveal"
                    class="transition-fast-in-fast-out v-card--reveal"
                    style="height: 100%"
                  >
                    <v-card-text class="pb-0">
                      <p class="display-1 text--primary">Origin</p>
                      <p>
                        late 16th century (as a noun denoting a place where alms
                        were distributed): from medieval Latin eleemosynarius,
                        from late Latin eleemosyna ‘alms’, from Greek eleēmosunē
                        ‘compassion’
                      </p>
                    </v-card-text>
                    <v-card-actions class="pt-0">
                      <v-btn text color="teal accent-4" @click="reveal = false">
                        Close
                      </v-btn>
                    </v-card-actions>

                    <v-expand-transition>
                      <div v-show="show">
                        <v-divider></v-divider>

                        <v-card-text>
                          I'm a thing. But, like most politicians, he promised
                          more than he could deliver. You won't have time for
                          sleeping, soldier, not with all the bed making you'll
                          be doing. Then we'll go with that data file! Hey, you
                          add a one and two zeros to that or we walk! You're
                          going to do his laundry? I've got to find a way to
                          escape.
                        </v-card-text>
                      </div>
                    </v-expand-transition>
                  </v-card>
                </v-expand-transition>
              </v-card>
            </v-col>
            <v-spacer></v-spacer>
          </v-row>
        </v-container>
      </v-img>
      <v-footer padless dark absolute class="pb-0">
        <v-container class="pt-0 pb-0">
          <v-row no-gutters>
            <v-col lg offset-lg cols="4" class="pt-5 ml-0 pl-9" align="center">
              <v-card-title
                class="grey darken-4 amber--text text-center justify-center"
              >
                <strong class="subheading">
                  <p>CMTV Hall <br />Behind Eta Palace</p>
                </strong>
              </v-card-title>
              <v-spacer></v-spacer>
            </v-col>
            <v-col class="pt-2 mt-0 ml-1 pl-1" cols="auto">
              <flip-countdown deadline="2021-01-10 00:00:00"></flip-countdown>
            </v-col>
            <v-col cols="2" lg class="pt-8">
              <v-dialog v-model="dialog" max-width="600px">
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                    color="blue"
                    large
                    block
                    elevation
                    v-bind="attrs"
                    v-on="on"
                  >
                    <h3>click here to book a seat</h3>
                  </v-btn>
                </template>
                <v-card>
                  <v-card-title>
                    <span class="headline">Fill in your details</span>
                  </v-card-title>
                  <v-card-text>
                    <v-container>
                      <v-row>
                        <v-col cols="12" sm="6" md="6">
                          <v-text-field
                            label="First Name*"
                            required
                            outlined
                          ></v-text-field>
                        </v-col>
                        <v-col cols="12" sm="6" md="6">
                          <v-text-field
                            label="Last Name*"
                            persistent-hint
                            required
                            outlined
                          ></v-text-field>
                        </v-col>
                        <v-col cols="12">
                          <v-text-field
                            label="Email*"
                            required
                            placeholder="e.g myname@example.com"
                          ></v-text-field>
                        </v-col>
                        <v-col cols="6" md="4">
                          <v-text-field
                            label="Phone Number*"
                            type="integer"
                            required
                            outlined
                          ></v-text-field>
                        </v-col>
                        <v-col cols="12" sm="6" md="4">
                          <v-select
                            :items="['16-25', '26-35', '35-54', '54+']"
                            label="Age*"
                            required
                            outlined
                          ></v-select>
                        </v-col>
                        <v-col cols="12" sm="6" md="6">
                          <v-autocomplete
                            :items="[
                              'Developer',
                              'Software Engineer',
                              'Potential Investor',
                              'Scout',
                              'Project Manager',
                              'Other',
                            ]"
                            label="Who are you?"
                            multiple
                            outlined
                          ></v-autocomplete>
                        </v-col>
                      </v-row>
                    </v-container>
                    <small>*indicates required field</small>
                  </v-card-text>
                  <v-card-actions>
                    <v-spacer></v-spacer>
                    <v-btn color="blue darken-1" text @click="dialog = false">
                      Cancel
                    </v-btn>
                    <v-btn color="blue darken-1" text @click="dialog = false">
                      Register
                    </v-btn>
                  </v-card-actions>
                </v-card>
              </v-dialog>
            </v-col>
          </v-row>
        </v-container>
      </v-footer>
    </v-main>
  </v-app>
</template>

<script>
import FlipCountdown from "vue2-flip-countdown";
import Events from "./components/Events";

export default {
  components: { FlipCountdown },
  Events,
  data() {
    return {
      tab: null,
      items: ["PAST EVENTS", "FUTURE EVENTS"],
      text:
        " Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.",
    };
  },
  data: () => ({
    reveal: false,
  }),
};
</script>

<style lang="scss" scoped>
.glow {
  font-size: 30px;
  color: #ffffff;
  text-align: center;
  -webkit-animation: glow 1s ease-in-out infinite alternate;
  -moz-animation: glow 1s ease-in-out infinite alternate;
  animation: glow 1s ease-in-out infinite alternate;
}

@-webkit-keyframes glow {
  from {
    text-shadow: 0 0 5px #eeeeee, 0 0 10px #000000, 0 0 15px #000000,
      0 0 40px #000000, 0 0 25px #9554b3, 0 0 30px #9554b3, 0 0 45px #9554b3;
  }

  to {
    text-shadow: 0 0 10px #eeeeee, 0 0 15px #4d94ff, 0 0 40px #4d94ff,
      0 0 50px #4d94ff, 0 0 30px #4d94ff, 0 0 45px #4d94ff, 0 0 80px #4d94ff;
  }
}

.events {
  background-color: transparent !important;
  position: relative;
  bottom: 0px;

  &:hover {
    background-color: black !important;
    position: absolute;
    width: 100vw;

    .b-icon {
      display: none;
    }
  }
}

.v-card--reveal {
  bottom: 0;
  opacity: 1 !important;
  position: absolute;
  width: 100%;
}
</style>
