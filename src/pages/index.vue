<template>
  <div>
    <!-- flash -->
    <styled-title>nuxt-template</styled-title>
    <!-- not flash -->
    <h1 class="test">
      nuxt-template2
    </h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import styled from 'vue-styled-components';

const StyledTitle = styled.h1`
  font-size: 1.5em;
  text-align: center;
`;

export default Vue.extend({
  components: { StyledTitle }
});
</script>

<style scoped>
.test {
  font-size: 2em;
  text-align: right;
  color: red;
}
</style>
