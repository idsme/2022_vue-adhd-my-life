<template>
  <v-toolbar color="rgba(0,0,0,0)" flat dark class="mt-n6">
    <div>
      <v-icon color="#7C7C7F" class="mr-2">
        far fa-calendar-alt
      </v-icon>
      <v-badge
          color="red"
          content="1"
      >
          <span class="caption grey--text mt-2">
           DIM 9, 2022
          </span>
      </v-badge>
    </div>
    <v-spacer></v-spacer>
    <div color="rgba(0,0,0,0)">
      <v-tabs
          color="#A9DDD8"
          right
          background-color="#171721"
      >
        <v-tab>Day</v-tab>
        <v-tab>Week</v-tab>
        <v-tab>Month</v-tab>
        <v-tab>Year</v-tab>
      </v-tabs>
    </div>
  </v-toolbar>
</template>
<script>
export default {
  name: 'TimeFilterBar'
}
</script>
