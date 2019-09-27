<template>
  <div class="home">
    
  </div>
</template>

<script>
import gql from 'graphql-tag';

export default {
  name: 'Home',
  appolo: {
    categories: gql`{
      categories {
        id
        name
      }
    }`
  }
}
</script>

