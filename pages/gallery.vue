<template>
  <section>
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />
        <v-container class="py-16">
          <v-row>
            <v-col
              v-for="(image, index) in images"
              :key="index"
              class="d-flex child-flex"
              cols="4"
              xl="3"
            >
              <!--                :lazy-src="image.lazySrc"-->
              <v-img
                :src="image.src"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
                <template v-slot:placeholder>
                  <v-row
                    class="fill-height ma-0"
                    align="center"
                    justify="center"
                  >
                    <v-progress-circular
                      indeterminate
                      color="grey lighten-5"
                    ></v-progress-circular>
                  </v-row>
                </template>
              </v-img>
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
          src: 'pexels-andrea-piacquadio-3830745.jpg',
          heading: ' Gallery ',
        },
      ],
      images: [
        {
          src: 'shoot/8.jpg',
        },
        {
          src: 'shoot/9.jpg',
        },
        {
          src: 'shoot/14.jpg',
        },
        {
          src: 'shoot/36.jpg',
        },
        {
          src: 'shoot/40.jpg',
        },
        {
          src: 'shoot/51.jpg',
        },
        {
          src: 'shoot/66.jpg',
        },
        {
          src: 'shoot/70.jpg',
        },
        {
          src: 'shoot/81.jpg',
        },
        {
          src: 'shoot/107.jpg',
        },
        {
          src: 'shoot/116.jpg',
        },
        {
          src: 'shoot/121.jpg',
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
