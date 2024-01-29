<script>
  import favicon from '$lib/favicon.png?enhanced';
</script>

<enhanced:img alt="Foo" src={favicon} class="foo" />

<style>
  img.foo { /* Unused CSS selector "img.foo" svelte(css-unused-selector) */
    border: 8px solid blue;
  }

  .foo {
    outline: 8px solid red;
  }
</style>
