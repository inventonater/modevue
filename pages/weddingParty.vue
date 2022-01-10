<template>
  <section>
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />
        <SectionsTeam :our-team="ourTeam" />

        <v-row no-gutters>
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="friends/yoshimotoFam.jpg"
              lazy-src="friends/yoshimotoFam.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                Bride's Family
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                <!--                Lorem ipsum dolor sit amet, consectetur adipisicing elit-->
              </h3>
              <p>
                Being a US Navy Family, they moved around a bit and lived in
                Hawaii, California, Virginia, Japan, and finally Washington.
                Growing up, they’ve enjoyed taking family road trips around the
                country, and visiting local casinos. Michael (father) loves
                music and plays guitar, and is a big UFC fan. Junita (mother)
                loves cooking and baking, and spending time with grand- nieces
                and nephews. Janelle (sister) is the life of the party, and is
                always down for a fun board game.
              </p>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="friends/aschenbachFam.jpg"
              lazy-src="friends/aschenbachFam.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                Groom's Family
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                <!--                Lorem ipsum dolor sit amet, consectetur adipisicing elit-->
              </h3>
              <p>
                Scott (father) and Judy (mother) Aschenbach met in Madison,
                Wisconsin and moved to Ann Arbor, Michigan when Nate was still
                young. Nathan has three little sisters: Krista, Kerry, and Ali.
                Krista has three children with her husband Christian. Kerry
                lives with her husband Perry in Batavia, IL and Ali with her
                husband Jordan in Saint Paul, MN. There are also a great many
                dogs and cats.
              </p>
            </div>
          </v-col>
        </v-row>

        <!--        <SectionsTimeline />-->

        <!--        <v-container>-->
        <!--          <v-row class="py-16">-->
        <!--            <v-col cols="12">-->
        <!--              <h2-->
        <!--                class="text-h4 text-md-h3 text-center font-weight-black text-capitalize"-->
        <!--              >-->
        <!--                Who we are?-->
        <!--              </h2>-->
        <!--              <h3-->
        <!--                class="text-h4 text-uppercase font-weight-thin text-center my-8"-->
        <!--              >-->
        <!--                Lorem ipsum dolor sit amet, consectetur adipisicing elit-->
        <!--              </h3>-->
        <!--            </v-col>-->
        <!--            <v-col cols="12" md="6">-->
        <!--              <p>-->
        <!--                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do-->
        <!--                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut-->
        <!--                enim ad minim veniam, quis nostrud exercitation ullamco laboris-->
        <!--                nisi ut aliquip ex ea commodo consequat.-->
        <!--              </p>-->
        <!--              <blockquote class="text-h4 pa-5 my-4 font-weight-thin">-->
        <!--                …Lorem Ipsum proin gravida nibh vel velit auctor aliquet. Aenean-->
        <!--                sollicitudin, lorem quis-->
        <!--              </blockquote>-->
        <!--              <p>-->
        <!--                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do-->
        <!--                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut-->
        <!--                enim ad minim veniam, quis nostrud exercitation ullamco laboris-->
        <!--                nisi ut aliquip ex ea commodo consequat.-->
        <!--              </p>-->
        <!--            </v-col>-->
        <!--            <v-col cols="12" md="6">-->
        <!--              <p>-->
        <!--                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do-->
        <!--                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut-->
        <!--                enim ad minim veniam, quis nostrud exercitation ullamco laboris-->
        <!--                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor-->
        <!--                in reprehenderit in voluptate velit esse cillum dolore eu fugiat-->
        <!--                nulla pariatur. Excepteur sint occaecat cupidatat non proident,-->
        <!--                sunt in culpa qui officia deserunt mollit anim id est laborum.-->
        <!--                Sed ut perspiciatis unde omnis iste natus error sit voluptatem-->
        <!--                accusantium. Doloremque laudantium, totam rem aperiam, eaque-->
        <!--                ipsa quae ab illo inventore veritatis et quasi architecto beatae-->
        <!--                vitae dicta sunt explicabo. emo enim ipsam voluptatem quia-->
        <!--                voluptas sit aspernatur aut odit aut fugit, sed quia-->
        <!--                consequuntur magni dolores eos qui ratione voluptatem sequi-->
        <!--                nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor-->
        <!--                sit amet, consectetur, adipisci velit, sed quia non numquam eius-->
        <!--                modi tempora incidunt ut labore et dolore magnam aliquam quaerat-->
        <!--                voluptatem. Nemo enim ipsam voluptatem quia voluptas sit-->
        <!--                aspernatur aut odit aut fugit-->
        <!--              </p>-->
        <!--            </v-col>-->
        <!--          </v-row>-->
        <!--        </v-container>-->
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
          src: 'shoot/121.jpg',
          heading: ' Wedding Party ',
        },
      ],
      ourTeam: [
        {
          name: 'Janelle Yoshimoto',
          position: 'Co-Maid of Honor',
          phone: '+1 (987) 5894684',
          email: 'fiona@example.com',
          photo: 'yoshi.jpg',
          bio: '',
        },
        {
          name: 'David Arditti',
          position: 'Best Man',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'arditti.jpg',
          bio: '',
        },
        {
          name: 'Natalie Nakamine',
          position: 'Co-Maid of Honor',
          phone: '+1 (987) 6982456',
          email: 'justin@example.com',
          photo: 'nakamine.jpg',
          bio: '',
        },

        {
          name: 'Tony Magro',
          position: 'Groomsman',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'magro.jpg',
          bio: '',
        },
        {
          name: 'Nan Hultgren',
          position: 'Bridesmaid',
          phone: '+1 (987) 6982456',
          email: 'sebastian@example.com',
          photo: 'hultgren.jpg',
          bio: '',
        },

        {
          name: 'Chris Olsen',
          position: 'Groomsman',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'olsen.jpg',
          bio: '',
        },

        {
          name: 'Tannaz Faal',
          position: 'Bridesmaid',
          phone: '+1 (987) 6982456',
          email: 'amelia@example.com',
          photo: 'faal.jpg',
          bio: '',
        },
        {
          name: 'Dan Adkins',
          position: 'Groomsman',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'adkins.jpg',
          bio: '',
        },
        {
          name: 'Shoko Espinoza',
          position: 'Bridesmaid',
          phone: '+1 (987) 6982456',
          email: 'bernadette@example.com',
          photo: 'espinoza.jpg',
          bio: '',
        },
        {
          name: 'Carlos Marcano',
          position: 'Groomsman',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'marcano.jpg',
          bio: '',
        },
        {
          name: 'Chrisha Bali',
          position: 'Bridesmaid',
          phone: '+1 (987) 6982456',
          email: 'christian@example.com',
          photo: 'bali.jpg',
          bio: '',
        },
        {
          name: 'Joe Dwyer',
          position: 'Groomsman',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'dwyer.jpg',
          bio: '',
        },
        {
          name: 'Christine (CJ) Glenn',
          position: 'Bridesmaid',
          phone: '+1 (987) 6982456',
          email: 'audrey@example.com',
          photo: 'glenn.jpg',
          bio: '',
        },
        {
          name: 'Antonio Perez',
          position: 'Groomsman',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'perez.jpg',
          bio: '',
        },
        {
          name: 'Michael Walker',
          position: 'Groomsman',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'walker.jpg',
          bio: '',
        },
      ],
    }
  },
  head() {
    return {
      title: 'Wedding Party',
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
