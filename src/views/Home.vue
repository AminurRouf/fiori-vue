<template>
<div>
  <fd-section title="Home">
    <fd-panel>Home page</fd-panel>
  </fd-section>

  <dismissable-alert></dismissable-alert>
</div>
</template>

<script>
import DismissableAlert from "../components/DismissableAlert.vue";

export default {

   components: { DismissableAlert }
}
</script>
