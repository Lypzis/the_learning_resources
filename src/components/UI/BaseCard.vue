<template>
  <div>
    <!-- now it is available to wrap any other component :D -->
    <slot></slot>
  </div>
</template>

<style scoped>
div {
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  padding: 1rem;
  margin: 2rem auto;
  max-width: 40rem;
}
</style>
