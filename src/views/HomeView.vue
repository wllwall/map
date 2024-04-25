<template>
   <Mapview></Mapview>
</template>

<script>
// @ is an alias to /src
import Mapview from '@/components/MapContainer.vue'

export default {
  name: 'HomeView',
  components: {
    Mapview
  },
}
</script>
<style>
html,
body,
#container {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}
</style>
