<template>
  <section id="home">
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />

        <v-container>
          <v-row>
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Stay a while and explore Seattle!
              </h3>
              <p>
                Seattle has both city life and nature to offer! There are many
                delicious restaurants, breweries, and bars, and we recommend
                Belltown, Capitol Hill, Fremont, and Ballard to check out! There
                is also Lake Union and Lake Washington at your disposal for
                kayaking, stand up paddle boarding, boating, or a nice lakeside
                picnic. If you care to venture further from the city, the
                Seattle ferry can take you to Bainbridge Island that’s about an
                hour drive to Olympic National Park. Or drive east to hike in
                Wenatchee National Forest and visit the Bavarian town of
                Leavenworth. Portland, OR isn’t too far either with just a few
                hours drive south. There’s something for everyone in the PNW,
                and we hope you get to have some adventures while here!
              </p>
            </div>
          </v-row>
          <v-row class="my-2">
            <v-col md="6" cols="12">
              <h3 class="text-h5 text-uppercase font-weight-thin text-center">
                Friday May 27th @ 6pm <br />
                Rehearsal Dinner
              </h3>
            </v-col>
            <v-col md="6" cols="12">
              <h3 class="text-h5 text-uppercase font-weight-thin text-center">
                Saturday, May 28th @ 5pm <br />
                Ceremony & Reception
              </h3>
            </v-col>
          </v-row>

          <v-row class="">
            <v-col md="6" cols="12">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2689.6857430495115!2d-122.32272674903258!3d47.61279997908299!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x54906acc07f09b89%3A0xaec46580d07fc936!2sOptimism%20Brewing%20Company!5e0!3m2!1sen!2sus!4v1641360380301!5m2!1sen!2sus"
                width="100%"
                height="400"
                style="border: 0; display: block"
                allowfullscreen="true"
                aria-hidden="false"
                tabindex="0"
              ></iframe>
            </v-col>
            <v-col md="6" cols="12">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d21501.213613982!2d-122.33665778626509!3d47.65233479945281!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x549014fa1aacd849%3A0x76beb6093ebdaf94!2sThe%20MV%20Skansonia!5e0!3m2!1sen!2sus!4v1636859998029!5m2!1sen!2sus"
                width="100%"
                height="400"
                style="border: 0; display: block"
                allowfullscreen="true"
                aria-hidden="false"
                tabindex="0"
              ></iframe>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
    </v-row>
  </section>
</template>

<script>
export default {
  data() {
    return {
      heroAlt: [
        {
          src: 'shoot/81.jpg',
          heading: ' Travel ',
        },
      ],
    }
  },
  head() {
    return {
      title: 'Gallery',
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
