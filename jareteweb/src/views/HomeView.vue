<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/FotoJarete.jpg" width="80" height="80" />
    <Description msg="Jared Arroyo Martín" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Description from "@/components/Description.vue"; // @ is an alias to /src

@Component({
  components: {
    Description,
  },
})
export default class HomeView extends Vue {}
</script>
