<template>
  <div class="gradient-bg flex-col h-[100vh]">
    <Header></Header>
  </div>

</template>

<script>
import {defineComponent} from "vue";
import Header from "./components/Header.vue";

export default defineComponent({
  components: {Header}
})
</script>
<style scoped>
.gradient-bg {
  background: linear-gradient(135deg, #9CF4FF 0%, #FFFFFF 100%);
}
</style>