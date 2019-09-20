<template>
  <div>
    <h3>Events Listing</h3>
    <EventCard />
    <MediaBox url="/hqdefault.jpg">
      <h3 slot="heading">Adam Jahr</h3>
      <p slot="paragraph">My Words.</p>
    </MediaBox>
  </div>
</template>

<script>
import EventCard from '@/components/EventCard.vue'
import MediaBox from '@/components/MediaBox.vue'
export default {
  components: {
    EventCard,
    MediaBox
  }
}
</script>
