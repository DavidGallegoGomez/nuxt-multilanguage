<template>
  <div v-editable="blok" class="page">
    <component
      :is="blok.component"
      :key="blok._uid"
      v-for="blok in blok.body"
      :blok="blok"
    />
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
