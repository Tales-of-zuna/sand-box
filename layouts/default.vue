<template>
  <v-app style="background-color: #f7f7f7">
    <v-app-bar color="white" app elevate-on-scroll
      ><v-app-bar-nav-icon></v-app-bar-nav-icon
      ><v-container grid-list-xs>
        <v-row class="d-flex justify-center"
          ><v-col cols="10" class="align-center d-flex"
            ><img
              width="100"
              src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RW4ESm?ver=c63e"
              alt=""
            /><v-btn
              text
              color="grey darken-3 "
              class="text--text text-capitalize ml-5"
              >Утас</v-btn
            ><v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >Консол</v-btn
            ><v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >Зөөврийн компьютер</v-btn
            >
            <v-spacer> </v-spacer>
            <v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >хямдралтай</v-btn
            ><v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >Тусламж</v-btn
            >
            <v-btn
              icon
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              ><v-icon>mdi-magnify</v-icon></v-btn
            ><v-btn
              icon
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              ><v-icon>mdi-account</v-icon></v-btn
            >
            <v-btn
              icon
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              ><v-icon>mdi-cart</v-icon></v-btn
            >
          </v-col></v-row
        >
      </v-container></v-app-bar
    >
    <v-main>
      <Nuxt />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",
  data() {
    return {};
  },
};
</script>
