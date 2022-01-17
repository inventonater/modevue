<template>
  <section id='home'>
    <v-row no-gutters>
      <v-col cols='12'>
        <SectionsHeroAlt :hero-alt='heroAlt' />
        <v-container>
          <v-row class='my-16 text-center font-weight-thin '>
            <v-col md='6' cols='12'>
              <h3 class='text-h5  mb-1'>
                Airport
              </h3>
              <p class='mx-16 mb-16'>
                Flights can be booked to <a class='text--secondary' href='https://goo.gl/maps/PUb5eL9LRowQZqVr6' target="_blank">SeaTac (SEA)</a> airport.
              </p>

              <h3 class='text-h5  mb-1'>
                Airbnb
              </h3>
              <p class='mx-16'>
                We’ve curated a
                <a class='text--secondary' href='https://www.airbnb.com/wishlists/1000021098' target="_blank">list of Airbnb hosts</a>
                not too far from the venue. These are great options if you have a big group, or just want something
                cozier than the hotels.
              </p>
            </v-col>
            <v-col md='6' cols='12'>
              <h3 class='text-h5 mb-1'>
                Hotels
              </h3>
              <div class='mx-16'>
                <p class='mb-0'><a class='text--secondary' href='https://goo.gl/maps/tRPhUTLCEKdDSAP3A' target="_blank"> Staybridge Suites Seattle</a></p>
                <p class='mb-2'>~5 minute drive, 1.2 miles</p>
                <p class='mb-0'><a class='text--secondary' href='https://goo.gl/maps/tT9jW5XggFJUaS3E7' target="_blank"> Silver Cloud Inn </a></p>
                <p class='mb-2'>~7 minute drive, 2.5 miles</p>
                <p class='mb-0'><a class='text--secondary' href='https://goo.gl/maps/DKUFtQxLPYxLbpFHA' target="_blank"> Residence Inn by Marriott Seattle Downtown/Lake Union </a></p>
                <p class='mb-2'>~8 minute drive, 2.8 miles</p>
              </div>
            </v-col>
          </v-row>
        </v-container>

        <v-container class='font-weight-thin text-center'>
          <v-row class='my-2'>
            <v-col md='6' cols='12'>
              <h3 class='text-h5'> Rehearsal Dinner Venue</h3>
              <p class='mb-0'> Friday, May 27th @ 6pm </p>
              <p>Optimism Brewing Company</p>
            </v-col>
            <v-col md='6' cols='12'>
              <h3 class='text-h5 font-weight-thin text-center'> Ceremony & Reception Venue</h3>
              <p class='mb-0'> Saturday, May 28th @ 5pm </p>
              <p>The MV Skansonia</p>
            </v-col>
          </v-row>

          <v-row class=''>
            <v-col md='6' cols='12'>
              <iframe
                src='https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2689.6857430495115!2d-122.32272674903258!3d47.61279997908299!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x54906acc07f09b89%3A0xaec46580d07fc936!2sOptimism%20Brewing%20Company!5e0!3m2!1sen!2sus!4v1641360380301!5m2!1sen!2sus'
                width='100%'
                height='400'
                style='border: 0; display: block'
                allowfullscreen='true'
                aria-hidden='false'
                tabindex='0'
              ></iframe>
            </v-col>
            <v-col md='6' cols='12'>
              <iframe
                src='https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d21501.213613982!2d-122.33665778626509!3d47.65233479945281!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x549014fa1aacd849%3A0x76beb6093ebdaf94!2sThe%20MV%20Skansonia!5e0!3m2!1sen!2sus!4v1636859998029!5m2!1sen!2sus'
                width='100%'
                height='400'
                style='border: 0; display: block'
                allowfullscreen='true'
                aria-hidden='false'
                tabindex='0'
              ></iframe>
            </v-col>
          </v-row>

          <v-row >
            <div class='pa-4 my-8' >
              <h3 class='text-h5 mb-2'>
                Explore Seattle
              </h3>
              <p>
                Seattle has both city life and nature to offer! There are many
                delicious restaurants, breweries, and bars, and we recommend
                Belltown, Capitol Hill, Fremont, and Ballard to check out! There
                is also Lake Union and Lake Washington at your disposal for
                kayaking, stand up paddle boarding, boating, or a nice lakeside
                picnic.
              </p>
              <p>
                If you care to venture further from the city, the
                Seattle ferry can take you to Bainbridge Island that’s about an
                hour drive to Olympic National Park. Or drive east to hike in
                Wenatchee National Forest and visit the Bavarian town of
                Leavenworth. Portland, OR isn’t too far either with just a few
                hours drive south. There’s something for everyone in the PNW,
                and we hope you get to have some adventures while here!
              </p>
            </div>
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
          heading: ' Travel '
        }
      ]
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
            'Infographic hypotheses influencer user experience Long madel ture gen-z paradigm shift client partner network product seilans solve management influencer analytics leverage virality. incubator seed round massmarket. buyer agile development growth hacking business-to-consumer ecosystem'
        }
      ]
    }
  }
}
</script>
