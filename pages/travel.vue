<template>
  <section id="home">
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />
        <h2 class="text-h4 text-md-h3 text-center font-weight-black mb-7">
          Coming soon...
        </h2>
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
