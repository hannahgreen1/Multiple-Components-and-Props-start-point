<template lang="html">
  <h1>My Shopping List</h1>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      items: [
        {name: 'Milk', isPurchased: false},
        {name: 'Cheese', isPurchased: true},
        {name: 'Beans', isPurchased: false},
      ]
    };
  }
}
</script>

<style lang="css" scoped>
</style>