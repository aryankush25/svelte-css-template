<style type="text/scss">
  @import "./styles/theme";

  h1 {
    color: $redColor;
  }

  div {
    background: $greenColor;

    > p {
      color: $whiteColor;
    }
  }
</style>

<h1>Hello Svelte!</h1>

<div>
  <p>SASS is working!</p>
</div>
