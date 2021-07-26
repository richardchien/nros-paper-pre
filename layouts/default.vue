<template>
  <div class="slidev-layout default">
    <span class="left-corner"></span>
    <slot />
  </div>
</template>
<style lang="postcss">
.slidev-layout.default {
  .left-corner {
    position: fixed;
    width: 0.8rem;
    height: 3.2rem;
    left: 0;
    top: 2.1rem;
    background-color: #bf394b;
  }
}

.slidev-layout.default,
.slidev-layout.center {
  h1 {
    color: #bf394b;
    font-weight: bold;
  }

  color: #333;
  font-size: 1.6rem;

  ul {
    list-style-type: disc;
  }

  ul,
  ol {
    li {
      font-weight: bold;

      strong {
        color: #bf394b;
        text-decoration: underline;
      }

      ul,
      ol {
        li {
          font-weight: normal;
          font-size: 95%;
        }
      }
    }
  }
}
</style>
