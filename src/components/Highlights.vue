<template>
  <div class="custom-content-card content-card card">
    <div class="card-body pb-0">
    <div class="content-header h4 text-center pt-2 pb-3">Highlights</div>
      <div class="row">
        <UVIndex :highlights="highlights"></UVIndex>
        <Visibility :highlights="highlights"></Visibility>
        <WindStatus :highlights="highlights"></WindStatus>
      </div>
    </div>
  </div>
</template>

<script>
import UVIndex from "./UVIndex.vue";
import Visibility from "./Visibility.vue";
import WindStatus from "./WindStatus.vue";

export default {
  props: ["highlights"],
  components: {
    "UVIndex": UVIndex,
    "Visibility": Visibility,
    "WindStatus": WindStatus,
  },
};
</script>