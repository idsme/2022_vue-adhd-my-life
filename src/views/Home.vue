<template>
  <v-app :style="{background: $vuetify.theme.themes.dark.background}">
    <SideBar/>
    <RightSideBar/>
    <v-container>
      <HeaderTitleBar/>
      <TimeFilterBar/>
      <v-divider color="#7C7C7F"></v-divider>
      <v-row>
        <v-col cols="12" sm="3">
          <IssueTypeFilter :selected-item="selectedItem"/>
        </v-col>
        <v-col cols="12" sm="9">
          <VerticalTaskTimeLine/>
        </v-col>
      </v-row>
      <FooterList/>
    </v-container>
  </v-app>
</template>

<script>
import SideBar from '../components/SideBar'
import RightSideBar from '../components/RightSideBar'
import HeaderTitleBar from "@/views/HeaderTitleBar";
import TimeFilterBar from "@/views/TimeFilterBar";
import IssueTypeFilter from "@/views/IssueTypeFilter";
import FooterList from "@/views/FooterList";
import VerticalTaskTimeLine from "@/views/VerticalTaskTimeLine";

export default {
  name: 'Home',
  data: () => ({
    selectedItem: 2,
    items: [
      {text: 'Real-Time'},
      {text: 'Audience'},
      {text: 'Conversions'},
    ],
  }),

  components: {
    VerticalTaskTimeLine,
    FooterList,
    IssueTypeFilter,
    TimeFilterBar,
    HeaderTitleBar,
    SideBar,
    RightSideBar
  },
}
</script>
<style scoped>
.theme--light.v-timeline::before {
  background: #7C7C7F !important;
}

.border {

  background: #22222C;
  border-radius: 50%;


}
</style>
