<template>
  <div id="cd-wrapper">
    <ChordDictionary />
  </div>
</template>
<script>
import ChordDictionary from "./components/ChordDictionary.vue";

export default {
  name: "app",
  components: {
    ChordDictionary
  }
};
</script>

<style scoped>
#cd-wrapper {
  position: rerative;
}
</style>
