<template>
  <v-app id="gc-element">
    <v-content>
      <v-container>
        <v-card elevation="0" style="background-color: #111;">
          <div class="pa-6">
            <v-row>
              <v-col cols="12" md="6" class="text-center">
                <v-img
                  style="max-width:250px"
                  class="mx-auto"
                  src="https://images.prismic.io/jonathan-wilke/6dde37c3-42c7-4a5d-9aa9-49b6862ee9c4_work-finally-friday-logo.png?auto=compress,format&amp;w=300&amp;auto=compress"
                  alt="Finally Friday"
                  loading="lazy"
                />
                <div
                  class="mt-8 primary--text font-weight-bold text-uppercase tag-list"
                >
                  <span class="d-inline-block">#Design</span>
                  <span class="d-inline-block pl-3">#Wordpress</span>
                </div>
                <v-btn depressed rounded color="primary" class="mt-6" large
                  >Seite ansehen</v-btn
                >
              </v-col>
              <v-col cols="12" md="6">
                <v-img
                  class="max-w-full"
                  src="https://images.prismic.io/jonathan-wilke/6812cb85-387d-4140-ab17-c09518d6eb27_work-finally-friday.png?auto=compress,format&amp;w=800&amp;auto=compress"
                  alt="Finally Friday"
                  loading="lazy"
                />
              </v-col>
            </v-row>
          </div> </v-card
      ></v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  })
};
</script>
