<template>
  <v-list rounded
          flat
          color="rgba(0,0,0,0)"
          class="mt-3"
  >

    <v-list-item-group
        v-model="selectedItem"
        color="#A9DDD8"
    >
      <v-list-item active-class="border">
        <v-list-item-content>
          <v-list-item-title class="grey--text">Design</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
      <v-list-item active-class="border" class="mt-11">
        <v-list-item-content>
          <v-list-item-title class="grey--text">Mobile Apps</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
      <v-list-item active-class="border" class="mt-8">
        <v-list-item-content>
          <v-list-item-title class="grey--text">Infography</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
      <v-list-item active-class="border" class="mt-8">
        <v-list-item-content>
          <v-list-item-title class="grey--text">Protoyping</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
    </v-list-item-group>
  </v-list>
</template>
<script>
export default {
  name: 'IssueTypeFilter',
  props: {
    selectedItem: {}
  }
}
</script>
