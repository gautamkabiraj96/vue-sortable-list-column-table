<template>
  <div id="app">
    <ItemList />
  </div>
</template>

<script>
/* Code by www.nightprogrammer.com */

import ItemList from "./components/ItemList";
export default {
  name: "App",
  components: {
    ItemList,
  },
};
</script>

<style>
body {
  font-family: arial, sans-serif;
}
</style>