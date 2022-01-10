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
                    <v-icon color="primary"> mdi-clock </v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <v-list-item-title>
                      Friday May 27th @ 6pm
                    </v-list-item-title>
                    Rehearsal Dinner
                    <v-list-item-subtitle>
                      Optimism Brewing Company<br />
                      1158 Broadway<br />
                      Seattle, WA 98122
                    </v-list-item-subtitle>
                    <v-list-item-subtitle class="pt-1">
                      <i>Children welcome!</i>
                    </v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>

                <v-list-item>
                  <v-list-item-icon>
                    <v-icon color="primary"> mdi-clock </v-icon>
                  </v-list-item-icon>
                  <v-list-item-content>
                    <v-list-item-title>
                      Saturday, May 28th @ 5pm
                    </v-list-item-title>
                    Ceremony & Reception
                    <v-list-item-subtitle>
                      The MV Skansonia<br />
                      205 NE Northlake Way #6855 <br />
                      Seattle, WA 98105
                    </v-list-item-subtitle>
                    <v-list-item-subtitle class="pt-1">
                      <i>
                        Saturday will be an adult-only event.<br />
                        Please reach out for babysitting details.<br />
                      </i>
                    </v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </v-col>
            <v-col md="7" cols="12">
              <div class="text-h4 font-weight-black mb-8">
                We can’t wait to celebrate with you!
              </div>
              <p class="mb-10">
                Complete the following Google Form to let us know you are coming
              </p>
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
