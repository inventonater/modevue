<template>
  <section id="intro" class="py-16">
    <v-container>
      <v-responsive class="max-auto mx-auto text-center" max-width="600">
        <v-avatar color="primary" size="70" class="mb-8">
          <v-icon x-large dark>mdi-ring</v-icon>
        </v-avatar>
        <h2 class="text-h4 text-md-h3 text-center font-weight-black mb-7">
          It's going down...
        </h2>
        <h2 class="text-h4 text-md-h3 text-center mb-7"> Saturday, May 28th </h2>
        <div class="title font-weight-light">
          <p class="mb-0"> 5pm @  <a class='text--secondary pa-1 pa-md-0' href='https://goo.gl/maps/bQA4yr1DJWgs4mBJ9' target="_blank">The MV Skansonia</a></p>
          <p class="mb-0">205 NE Northlake Way</p>
          <p class="mb-0">Seattle, WA</p>
        </div>

        <v-btn

          :x-large="$vuetify.breakpoint.smAndUp"
          href="/rsvp"
          class="my-16 primary text-h4 "
          >RSVP Online</v-btn
        >

        <p class='mb-0'><i>Saturday will be an adult-only event.</i></p>
        <p><i> Please reach out for babysitting details.</i></p>
      </v-responsive>

      <!--      <v-row class="pt-12">-->
      <!--        <v-col v-for="card in cards" :key="card.title" cols="12" md="4">-->
      <!--          <v-row no-gutters>-->
      <!--            <v-col :cols="card.callout ? 9 : 12">-->
      <!--              <div class="pr-2">-->
      <!--                <div class="text&#45;&#45;disabled" v-text="card.subtitle"></div>-->
      <!--                <h4-->
      <!--                  class="text-uppercase mt-1 mb-4"-->
      <!--                  style="letter-spacing: 0.15em"-->
      <!--                  v-text="card.title"-->
      <!--                ></h4>-->
      <!--                <p v-text="card.text"></p>-->
      <!--              </div>-->
      <!--            </v-col>-->
      <!--            <v-col v-if="card.callout" cols="2">-->
      <!--              <span-->
      <!--                class="text-h3 grey&#45;&#45;text font-weight-bold pr-8"-->
      <!--                style="opacity: 0.1"-->
      <!--                >{{ card.callout }}</span-->
      <!--              >-->
      <!--            </v-col>-->
      <!--          </v-row>-->
      <!--        </v-col>-->
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
          title: 'Best Productivity',
          subtitle: 'Professionally developed',
          text:
            'All components and features are developed using the most up-to-date coding practices.',
          callout: '01',
        },
        {
          title: 'Fast & optimized',
          subtitle: 'Performance',
          text:
            'Themes are designed for maximum performance and are semantically structured to maximize SEO.',
          callout: '02',
        },
        {
          title: 'Built on Vuetify',
          subtitle: 'Material Design',
          text:
            "Being developed with Vuetify means you have access to all of the framework's available features.",
          callout: '03',
        },
      ],
    }
  },
}
</script>
