<template>
  <button @click="go">RouterPractice.vueへ</button>
</template>
<script>
export default {
  methods: {
    go() {
      this.$router.push({ name: "RouterPractice" });
    },
  },
};
</script>
