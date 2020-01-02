<template>
  <div v-editable="blok" class="page">
    <component
      :key="blok._uid"
      v-for="blok in blok.body"
      :blok="blok"
      v-bind:is="blok.component"
    ></component>
  </div>
</template>

<script>
export default {
  props: {
    blok: {
      type: Object,
      default: () => {}
    }
  }
}
</script>
