<template>
  <fd-container>
    <fd-alert dismissible>
      Default dismissable alert componet with a hello popover. Click on the close button.
    </fd-alert>

      <fd-popover v-fd-margin:large placement="bottom-start" with-arrow>
    <h1 v-fd-margin:large>
      🚀 Hello Fundamental Vue 🚀
    </h1>
    <template #control="{toggle}">
      <fd-button @click="toggle">Show Popover</fd-button>
    </template>
  </fd-popover>
  </fd-container>
</template>
