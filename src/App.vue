<template>
  <div id="app">
    <appHeader></appHeader>
    <div class="header">
      I am header
    </div>
    <div class="tab">
      I am tab
    </div>
    <div class="content">
      I am content
    </div>
  </div>
</template>

<script>
  import appHeader from './components/header/header';

  export default {
      components: {
          appHeader
      }
  };
</script>

<style>

</style>
