<template>
  <section id="home">
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />
        <h2 class="text-h4 text-md-h3 text-center font-weight-black mb-7">
          Coming soon...
        </h2>
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d21501.213613982!2d-122.33665778626509!3d47.65233479945281!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x549014fa1aacd849%3A0x76beb6093ebdaf94!2sThe%20MV%20Skansonia!5e0!3m2!1sen!2sus!4v1636859998029!5m2!1sen!2sus"
          width="100%"
          height="600"
          style="border: 0; display: block"
          allowfullscreen="true"
          aria-hidden="false"
          tabindex="0"
        ></iframe>
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
