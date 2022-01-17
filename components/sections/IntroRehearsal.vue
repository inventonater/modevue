<template>
  <section class='primary darken-1 white--text text-center py-16'>
    <v-container>
      <v-row>
        <v-col class='text-center'>
          <h2 class='text-h4 text-md-h3 text-center font-weight-black mb-7'> Rehearsal Reception </h2>
          <h2 class='text-h4 text-md-h3 text-center mb-7'> Friday, May 27th </h2>

          <div class='title font-weight-light'>
            <p class='mb-0'>6pm - 10pm @ <a class='text--secondary pa-1 pa-md-0'
                                            href='https://g.page/OptimismBrewing?share' target="_blank">Optimism Brewery</a></p>
            <p class='mb-0'>1158 Broadway, Seattle, WA</p>
          </div>

          <p class='pt-10'>
            After you arrive in Seattle on Friday, come have a beer with us! <br/> We invite you all to join us for a casual get
            together, with food and drinks.<br/>
          </p>
          <p class='pt-2'>
            <i >Children are very welcome on Friday!</i>
          </p>
        </v-col>
      </v-row>
      <!--      <v-row>-->
      <!--        <v-col-->
      <!--          v-for="(card, index) in cards"-->
      <!--          :key="index"-->
      <!--          cols="12"-->
      <!--          sm="4"-->
      <!--          class="text-center"-->
      <!--        >-->
      <!--          <v-avatar-->
      <!--            size="80"-->
      <!--            class="display-1 white font-weight-bold primary&#45;&#45;text mb-5"-->
      <!--            style="opacity: 1.15"-->
      <!--            >{{ card.callout }}</v-avatar-->
      <!--          >-->
      <!--          <div class="title text-uppercase mt-1 mb-4" v-text="card.title"></div>-->

      <!--          <p v-text="card.text"></p>-->
      <!--          <v-row no-gutters>-->
      <!--            <v-col cols="12"> </v-col>-->
      <!--          </v-row>-->
      <!--        </v-col>-->
      <!--      </v-row>-->
      <!--      <v-row no-gutters>-->
      <!--        <v-btn x-large rounded color="white primary&#45;&#45;text mx-auto mt-10 px-16">-->
      <!--          <v-icon dark left> mdi-check-bold </v-icon>Upload-->
      <!--        </v-btn>-->
      <!--      </v-row>-->
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
          callout: '01'
        },
        {
          title: 'Masks',
          subtitle: 'Special Offers',
          text: 'Upon arrival and while indoors',
          callout: '02'
        },
        {
          title: 'Boosters',
          subtitle: 'Income Flow',
          text: 'Please keep up with the latest recommendations',
          callout: '03'
        }
      ]
    }
  }
}
</script>
