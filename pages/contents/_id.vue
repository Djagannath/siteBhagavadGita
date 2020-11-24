<template>
  <article>
    {{ $route.params.id }}
  </article>
</template>

<script>
export default {
  validate({params}) {
    console.log('validate', params);
    return true;
  }
}
</script>

<style scoped>

</style>
