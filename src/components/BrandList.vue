<template>
  <div>
    <mt-search
      v-model="value"
      cancel-text="取消"
      placeholder="搜索">
    </mt-search>
  </div>
</template>

<script>
  export default {
    name: "BrandList",
    data() {
      return {
        value: '亚欧国际小镇'
      }
    }
  }
</script>

<style scoped>

</style>
