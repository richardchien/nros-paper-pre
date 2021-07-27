<template>
  <div class="slidev-layout default">
    <span class="left-corner"></span>
    <slot />
  </div>
</template>
<style lang="postcss">
.slidev-layout.default .left-corner {
  position: fixed;
  width: 0.8rem;
  height: 3.2rem;
  left: 0;
  top: 2.1rem;
  background-color: #bf394b;
}
</style>