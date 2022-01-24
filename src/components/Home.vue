<template>
  <div>
    <h1>Hello from home component</h1>
    <h2>{{ data }}</h2>
  </div>
</template>
<script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {
    Name = "Home";
  },
});
</script>
