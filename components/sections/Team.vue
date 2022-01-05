<template>
  <section :class="$vuetify.theme.dark ? 'grey darken-4' : 'grey lighten-4'">
    <v-container fluid class="text-center">
      <!--      <v-row>-->
      <!--        <v-col>-->
      <!--          <h2 class="text-h4 text-sm-h3 text-capitalize font-weight-black mb-4">-->
      <!--            This will be a party to remember!-->
      <!--          </h2>-->
      <!--          <p>-->
      <!--            Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam-->
      <!--            nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat-->
      <!--            volutpat.-->
      <!--          </p>-->
      <!--        </v-col>-->
      <!--      </v-row>-->
      <v-row>
        <v-col v-for="(item, i) in ourTeam" :key="`person-${i}`">
          <v-sheet class="py-12 px-6" outlined shaped>
            <v-avatar size="240"
              ><img
                :src="`/friends/${item.photo}`"
                :lazy-src="`friends/${item.photo}`"
                alt="John"
            /></v-avatar>
            <div class="text-h5 text-uppercase font-weight-black mt-6 mb-2">
              {{ item.name }}
            </div>
            <div class="text--disabled text-uppercase">
              {{ item.position }}
            </div>
            <!--<div class="text-h6 font-weight-black mt-8">{{ item.phone }}</div>-->
            <!--<div class="subtitle-1 mt-3">{{ item.email }}</div>-->
            <div class="subtitle-1 mt-3">{{ item.bio }}</div>
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  props: {
    ourTeam: {
      type: Array,
      default: () => [],
    },
  },
}
</script>
