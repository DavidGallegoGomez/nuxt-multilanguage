<template>
  <div v-editable="blok" class="util__flex">
    <component
      :is="blok.component"
      :key="blok._uid"
      v-for="blok in blok.columns"
      :blok="blok"
    />
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
