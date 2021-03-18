<template>
  <div id="app">
    <ReactiveBase
      app="good-books-yj"
      credentials="gBgUqs2tV:3456f3bf-ea9e-4ebc-9c93-08eb13e5c87c"
    >
    </ReactiveBase>
  </div>
</template>

<script>
import { ReactiveBase } from "@appbaseio/reactivesearch-vue";

export default {
  components: {
    ReactiveBase
  },
  name: "app"
};
</script>
