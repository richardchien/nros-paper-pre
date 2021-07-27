<template>
  <div class="slidev-layout center h-full grid place-content-center">
    <span class="top-line"></span>
    <div class="my-auto">
      <slot />
    </div>
  </div>
</template>
<style lang="postcss">
.slidev-layout.center .top-line {
  position: fixed;
  width: 100%;
  height: 0.3rem;
  left: 0;
  top: 0;
  background-color: #bf394b;
}
</style>