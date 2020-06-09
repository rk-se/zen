<template>
  <div style="position: relative;">
      <TempVarChart :tempVar="tempVar"></TempVarChart>
      <Highlights :highlights="highlights"></Highlights>
  </div>
</template>

<script>
import TempVarChart from './TempVarChart.vue';
import Highlights from './Highlights.vue';

export default {
  props: ['highlights', 'tempVar'],
  components: {
    'TempVarChart': TempVarChart,
    'Highlights': Highlights
  },
}
</script>