<template>
  <v-timeline align-top :dense="$vuetify.breakpoint.smAndDown" class="mt-2 mr-3">
    <v-timeline-item color="red" fill-dot small icon="mdi-cog">
      <TimeLineItemCard/>
    </v-timeline-item>
    <v-timeline-item color="cyan" fill-dot small>
      <v-card color="#22222C" dark>
        <v-card-title class="text-subtitle-2 cyan--text">
          About 5 hours
          <v-spacer></v-spacer>
          <v-avatar size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/3.jpg" alt="John">
          </v-avatar>
        </v-card-title>
      </v-card>
    </v-timeline-item>
    <v-timeline-item color="pink" fill-dot small>
      <v-card color="#22222C" dark>
        <v-card-title class="text-subtitle-2 pink--text">
          About 5 hours
          <v-spacer></v-spacer>
          <v-avatar size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/4.jpg" alt="John">
          </v-avatar>
          <v-avatar class="ml-n3" size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/2.jpg" alt="John">
          </v-avatar>
        </v-card-title>
      </v-card>
    </v-timeline-item>
    <v-timeline-item color="yellow" fill-dot small>
      <v-card color="#22222C" dark>
        <v-card-title class="text-subtitle-2 yellow--text">
          About 3 hours
          <v-spacer></v-spacer>
          <v-avatar size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/1.jpg" alt="John">
          </v-avatar>
          <v-avatar class="ml-n3" size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/3.jpg" alt="John">
          </v-avatar>
          <v-avatar class="ml-n3" size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/5.jpg" alt="John">
          </v-avatar>
        </v-card-title>
      </v-card>
    </v-timeline-item>
    <v-timeline-item color="yellow" fill-dot small>
      <v-card color="#22222C" dark>
        <v-card-title class="text-subtitle-2 yellow--text">
          About 10 hours
          <v-spacer></v-spacer>
          <v-avatar size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/1.jpg" alt="John">
          </v-avatar>
          <v-avatar class="ml-n3" size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/3.jpg" alt="John">
          </v-avatar>
          <v-avatar class="ml-n3" size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/5.jpg" alt="John">
          </v-avatar>
        </v-card-title>
      </v-card>
    </v-timeline-item>
    <v-timeline-item color="green" fill-dot small>
      <v-card color="#22222C" dark>
        <v-card-title class="text-subtitle-2 pink--text">
          About 5 hours
          <v-spacer></v-spacer>
          <v-avatar size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/4.jpg" alt="John">
          </v-avatar>
          <v-avatar class="ml-n3" size="30">
            <img src="https://cdn.vuetifyjs.com/images/lists/2.jpg" alt="John">
          </v-avatar>
        </v-card-title>
      </v-card>
    </v-timeline-item>

  </v-timeline>
</template>
<script>
import TimeLineItemCard from "@/views/TimeLineItemCard";

export default {
  name: 'VerticalTaskTimeLine',
  components: {TimeLineItemCard}
}
</script>
