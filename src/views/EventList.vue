

<template>
  <div>
    <h1>Event Listing</h1>
<EventCard></EventCard>
<router-link :to="{name:'event-show',params:{'id':'1'}}">Show Event #1</router-link> 
  </div>
</template>
<script>
import EventCard from '@/components/EventCard.vue';
export default {
  components:{
    EventCard
  }
}
</script>