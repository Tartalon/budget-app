<template>
  <div class="budget-list-wrapp">
    <ElCard :header="header">

    </ElCard>
  </div>
</template>

<script>
export default {
  name: "BadgetList",
  props: {
    list: {
      type: Object,
      default: () => ({ })
    }
  },
  data: () => ({
    header: 'Budget List',
  })
}
</script>

<style scoped>

</style>