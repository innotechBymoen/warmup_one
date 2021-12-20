<template>
  <div>
    <h1>Books!</h1>
    <!-- TODO-2 I want to loop through all my books and create a BookOption for each one -->
    <book-option></book-option>
  </div>
</template>

<script>
import BookOption from '@/components/BookOption.vue';

export default {
  name: 'HomePage',
  components: {
    BookOption
  },
  // TODO-1 I want to make an axios request when this page loads to the API: https://fakerapi.it/api/v1/books
  // I know that I can give the parameter _quantity to select how many bookes I want, and I want 5
  // When I get the 5 books, I need to but them in a local variable in this component
}
</script>

<style lang="scss" scoped>

</style>
