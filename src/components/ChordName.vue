<template>
  <h3 id="chord">{{ chordName }}</h3>
</template>

<script>
export default {
  name: "ChordName",
  props: {
    chordName: String
  }
};
</script>

<style scoped>
#chord {
  font-size: 18px;
  height: 20px;
  margin-top: 0;
  margin-bottom: 0;
  font-weight: 500;
  line-height: 1.2;
}
</style>
