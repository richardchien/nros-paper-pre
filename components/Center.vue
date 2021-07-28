<template>
  <div class="center-component">
    <slot />
  </div>
</template>
<style lang="postcss" scoped>
.center-component {
  height: 100%;
  margin-top: -1rem;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}
</style>