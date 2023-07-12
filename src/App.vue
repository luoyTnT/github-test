<template>
  <div id="container">
    <search />
    <List />
  </div>
</template>

<script>
import List from "./components/List";
import Search from "./components/Search";

export default {
  name: "App",
  components: {
    List,
    Search,
  },
};
</script>