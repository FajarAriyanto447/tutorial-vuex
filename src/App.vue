<template>
  <div id="app" class="container">
    <div class="row py-4">
      <agenda-input />
    </div>
    <div class="row py-4"> 
      <agenda-show />
    </div>
  </div>
</template>

<script>
import AgendaInput from "./components/AgendaInput.vue";
import AgendaShow from "./components/AgendaShow.vue";

export default {
  name: "App",
  components: {
    AgendaInput,
    AgendaShow,
  },
};
</script>
