<template functional>
  <div>
    <p v-for="brand in props.brands" :key="brand">{{brand}} </p>
  </div>
</template>
<script> 
export default {
  functional: true,
  name: 'Test',
  props: {
    brands: Array
  }
}
</script>