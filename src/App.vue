<template>

</template>

<script setup lang="ts">


import {onMounted} from "vue";
import {Schematic} from "mindustry-schematic-parser";


onMounted(function () {
  load()
})

function load() {
  const base64Code = "bXNjaAF4nE2N227CMAyGf9KjhrRpSNznBXqFtBfhCUJjUBEklUkH7NG5oDhppWHH+Rwf/iBDqZA7cyZ8b24/emuc1cHrbcumx9LSpeWuD513WL899MFrvWOxGh/9cPol7v6IJfdX4sZ5S/jqnJQD2ebiBYzPwVni/clfm4MJhPo4uDZJl/NEyX6IrHYmCO8AVvi3RTpQdQWMT6hxlBBKVYlLZ3zMo9mEHKleFDHN0vYiQjxPW6koUQjyNFVKVsSOmiSiOqr5A7myCUlZzcovD0488Q=="
  let schematic = Schematic.decode(base64Code);
}

</script>
<style scoped>

</style>
