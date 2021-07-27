<template>
  <div class="slidev-layout cover">
    <div class="logo">
      <img src="/logo/sjtu.png" />
      <img src="/logo/ipads.png" />
    </div>
    <div class="my-auto w-full">
      <slot />
    </div>
  </div>
</template>
<style lang="postcss">
.slidev-layout.cover .logo {
  height: 3rem;
  margin-left: auto;

  img {
    height: 100%;
    display: inline-block;
    margin: 0 0.5rem;
  }
}
</style>