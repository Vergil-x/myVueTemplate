<script setup lang="ts">

const router = useRouter();
const count = ref(0);
</script>

<template>
  <h1 class="text-5xl text-gray-400"> Test TailWind Css </h1>
  <div class="text-5xl">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

</template>

<style lang="less" scoped>
</style>
