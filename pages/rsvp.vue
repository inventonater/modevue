<template>
  <section>
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />
        <v-container>
          <v-row class="py-16">
            <v-col md="5" cols="12">
              <div class="text-h6 font-weight-bold mt-12 mb-5">Schedule</div>
              <v-list two-line class="transparent">
                <v-list-item>
                  <v-list-item-icon>
                    <v-icon color="primary"> mdi-map-marker </v-icon>
                  </v-list-item-icon>

                  <v-list-item-content>
                    <v-list-item-title>ADDRESS</v-list-item-title>
                    <v-list-item-subtitle
                      >205 NE Northlake Way #6855<br />Seattle, WA
                      98105</v-list-item-subtitle
                    >
                  </v-list-item-content>
                </v-list-item>

                <v-list-item>
                  <v-list-item-icon>
                    <v-icon color="primary"> mdi-clock </v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <v-list-item-title> FRIDAY May 27th </v-list-item-title>
                    <v-list-item-subtitle>
                      Rehearsal Dinner
                    </v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>

                <v-list-item>
                  <v-list-item-icon>
                    <v-icon color="primary"> mdi-clock </v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <v-list-item-title> SATURDAY May 28th </v-list-item-title>
                    <v-list-item-subtitle>
                      Ceremony & Reception
                    </v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </v-col>
            <v-col md="7" cols="12">
              <!--
              <div class="text-h4 font-weight-black mb-8">
                Let us know you are coming!
              </div>
              <p class="mb-10">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
-->
              <rsvpGoogleForm />
            </v-col>
          </v-row>
        </v-container>
      </v-col>
    </v-row>
  </section>
</template>

<script>
import rsvpGoogleForm from '~/components/sections/rsvpGoogleForm.vue'
export default {
  components: {
    rsvpGoogleForm,
  },
  data() {
    return {
      heroAlt: [
        {
          src: 'shoot/107.jpg',
          heading: ' RSVP ',
        },
      ],
    }
  },
  head() {
    return {
      title: 'RSVP',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'Infographic hypotheses influencer user experience Long madel ture gen-z paradigm shift client partner network product seilans solve management influencer analytics leverage virality. incubator seed round massmarket. buyer agile development growth hacking business-to-consumer ecosystem',
        },
      ],
    }
  },
}
</script>

<style scoped>
#footer-top {
  display: none !important;
}
</style>
