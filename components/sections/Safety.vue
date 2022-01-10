<template>
  <section class="primary darken-1 white--text py-16">
    <v-container>
      <v-row>
        <v-col class="text-center">
          <h2 class="text-h4 text-md-h3 text-center font-weight-black">
            Wedding Safety Guidelines
          </h2>
          <div
            class="text-h5 text-md-h4 text-center font-weight-black py-3 mb-10"
          >
            We can't wait to gather our friends and family...
          </div>
          <p class="title font-weight-light">
            We are closely monitoring COVID and how it will impact our wedding
            plans. We can’t wait to celebrate with you in May, and your health
            and safety continue to be our priority. With that being said, we are
            asking all guests who are attending our wedding in person to please
            be fully vaccinated.
          </p>
          <p class="title font-weight-light">
            We also request that all of our guests arrive masked. You are
            welcome to remove your mask (only if you feel comfortable) for our
            outdoor celebration. We truly hope everyone will comply with this
            rule but we understand if you can’t. In the interest of ensuring the
            safety of all guests, vendors, and venue employees, unfortunately no
            guest will be admitted to our celebration without proof of full
            vaccination.
          </p>
        </v-col>
      </v-row>
      <v-row>
        <v-col
          v-for="(card, index) in cards"
          :key="index"
          cols="12"
          sm="4"
          class="text-center"
        >
          <v-avatar
            size="80"
            class="display-1 white font-weight-bold primary--text mb-5"
            style="opacity: 1.15"
            >{{ card.callout }}</v-avatar
          >
          <div class="title text-uppercase mt-1 mb-4" v-text="card.title"></div>

          <p v-text="card.text"></p>
          <v-row no-gutters>
            <v-col cols="12"> </v-col>
          </v-row>
        </v-col>
      </v-row>
      <v-row no-gutters>
        <!--        <v-btn x-large rounded color="white primary&#45;&#45;text mx-auto mt-10 px-16">-->
        <!--          <v-icon dark left> mdi-check-bold </v-icon>Upload-->
        <!--        </v-btn>-->
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          title: 'Proof of Vaccination',
          subtitle: 'Best Productivity',
          text: '14 days prior to our special day',
          callout: '01',
        },
        {
          title: 'Masks',
          subtitle: 'Special Offers',
          text: 'Upon arrival and while indoors',
          callout: '02',
        },
        {
          title: 'Boosters',
          subtitle: 'Income Flow',
          text: 'Please keep up with the latest recommendations',
          callout: '03',
        },
      ],
    }
  },
}
</script>
