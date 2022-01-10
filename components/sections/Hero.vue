<template>
  <section id="hero">
    <v-carousel
      height="calc(100vh - 64px)"
      dark
      cycle
      show-arrows-on-hover
      draggable="true"
      hide-delimiter-background
    >
      <v-carousel-item
        v-for="(carousel, carindex) in carouselsData"
        :key="carindex"
        :src="carousel.src"
        :position="carousel.position"
        class="gradient-fill"
      >
        <v-container fill-height>
          <div style="max-width: 600px">
            <div class="text-md-h2 mb-3 text-sm-h3 text-h5 font-weight-black">
              Nate & Christie
              <!--              {{ carousel.heading.toUpperCase() }}-->
            </div>
            <p class="mb-5">
              are getting married :)
              <!--              {{ carousel.subHeading }}-->
            </p>
            <v-btn
              :x-large="$vuetify.breakpoint.smAndUp"
              href="/rsvp"
              class="my-3 primary"
              >RSVP</v-btn
            >
            <span class="mx-2 my-4"></span>
            <v-btn
              :x-large="$vuetify.breakpoint.smAndUp"
              text
              href="/travel"
              class="my-3"
              outlined
              ><v-icon left large color="primary">mdi-play</v-icon>Travel</v-btn
            >
          </div>
        </v-container>
      </v-carousel-item>
    </v-carousel>
  </section>
</template>

<script>
export default {
  data() {
    return {
      carouselsData: [
        // {
        //   src: 'shoot/9.jpg',
        //   position: 'left 80% top 25%',
        //   heading: ' Nate & Christie',
        //   subHeading:
        //     'Litora a interdum primis. Lectus facilisi sit cum arcu aliquam velit imperdiet sapien suspendisse at vel facilisis. Facilisis metus, curae; nibh mi orci et. Fringilla sociis magna rutrum bibendum arcu.',
        // },
        // {
        //   src: 'shoot/14.jpg',
        //   position: 'left 60% top 50%',
        //   heading: ' Nate & Christie ',
        //   subHeading:
        //     'Tellus cum turpis natoque id justo interdum tincidunt faucibus aptent congue pellentesque. Proin luctus orci netus! Scelerisque parturient cursus donec parturient et, luctus aptent habitant aliquet felis. Sapien placerat ultricies.',
        // },
        {
          src: 'shoot/40.jpg',
          position: 'left 50% top 50%',
          heading: ' Nate & Christie ',
          subHeading:
            'Infographic hypotheses influencer user experience Long madel ture gen-z paradigm shift client partner network product seilans solve management influencer analytics leverage virality. incubator seed round massmarket. buyer agile development growth hacking business-to-consumer ecosystem ',
        },
        {
          src: 'shoot/51.jpg',
          position: 'left 90% top 50%',
          heading: ' Join Us ',
          subHeading:
            'Litora a interdum primis. Lectus facilisi sit cum arcu aliquam velit imperdiet sapien suspendisse at vel facilisis. Facilisis metus, curae; nibh mi orci et. Fringilla sociis magna rutrum bibendum arcu.',
        },

        {
          src: 'shoot/66.jpg',
          position: 'left 60% top 50%',
          heading: ' Nate & Christie ',
          subHeading:
            'Tellus cum turpis natoque id justo interdum tincidunt faucibus aptent congue pellentesque. Proin luctus orci netus! Scelerisque parturient cursus donec parturient et, luctus aptent habitant aliquet felis. Sapien placerat ultricies.',
        },
        {
          src: 'shoot/70.jpg',
          position: 'left 80% top 50%',
          heading: ' URNA TINCIDUNT MATTIS TORTOR ',
          subHeading:
            'Dapibus cras, ligula suspendisse potenti himenaeos mus volutpat pulvinar est facilisi. Vehicula malesuada parturient euismod litora mollis penatibus. Penatibus cum nullam facilisi enim nisi ac suspendisse. Ullamcorper ad amet netus.',
        },
        {
          src: 'shoot/81.jpg',
          position: 'left 50% top 50%',
          heading: ' Join Us ',
          subHeading:
            'Infographic hypotheses influencer user experience Long madel ture gen-z paradigm shift client partner network product seilans solve management influencer analytics leverage virality. incubator seed round massmarket. buyer agile development growth hacking business-to-consumer ecosystem ',
        },
        {
          src: 'shoot/107.jpg',
          position: 'left 80% top 50%',
          heading: ' Nate & Christie',
          subHeading:
            'Litora a interdum primis. Lectus facilisi sit cum arcu aliquam velit imperdiet sapien suspendisse at vel facilisis. Facilisis metus, curae; nibh mi orci et. Fringilla sociis magna rutrum bibendum arcu.',
        },
        {
          src: 'shoot/116.jpg',
          position: 'left 65% top 50%',
          heading: ' Nate & Christie ',
          subHeading:
            'Tellus cum turpis natoque id justo interdum tincidunt faucibus aptent congue pellentesque. Proin luctus orci netus! Scelerisque parturient cursus donec parturient et, luctus aptent habitant aliquet felis. Sapien placerat ultricies.',
        },
        // {
        //   src: 'shoot/121.jpg',
        //   heading: ' URNA TINCIDUNT MATTIS TORTOR ',
        //   subHeading:
        //     'Dapibus cras, ligula suspendisse potenti himenaeos mus volutpat pulvinar est facilisi. Vehicula malesuada parturient euismod litora mollis penatibus. Penatibus cum nullam facilisi enim nisi ac suspendisse. Ullamcorper ad amet netus.',
        // },
        {
          src: 'shoot/8.jpg',
          position: 'left 40% top 50%',
          heading: ' Join Us ',
          subHeading:
            'Infographic hypotheses influencer user experience Long madel ture gen-z paradigm shift client partner network product seilans solve management influencer analytics leverage virality. incubator seed round massmarket. buyer agile development growth hacking business-to-consumer ecosystem ',
        },
        // {
        //   src: 'shoot/36.jpg',
        //   position: 'left 90% top 50%',
        //   heading: ' Join Us ',
        //   subHeading:
        //     'Dapibus cras, ligula suspendisse potenti himenaeos mus volutpat pulvinar est facilisi. Vehicula malesuada parturient euismod litora mollis penatibus. Penatibus cum nullam facilisi enim nisi ac suspendisse. Ullamcorper ad amet netus.',
        // },
      ],
    }
  },
}
</script>

<style>
.gradient-fill .v-responsive__content {
  background: rgb(0, 0, 0);
  background: linear-gradient(
    to right,
    rgba(3, 12, 41, 0.75),
    rgba(5, 11, 31, 0.65)
  );
}
</style>
