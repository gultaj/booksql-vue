<template>
  <div class="home">

  </div>
</template>

<script>
// @ is an alias to /src
import gql from 'graphql-tag';

export default {
  name: 'home',
  data() {
    return {
      categories: []
    }
  },
  apollo: {
    categories: gql`{
      categories {
        id
        name
      }
    }`
  }
}
</script>
