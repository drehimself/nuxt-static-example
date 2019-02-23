<template lang="md">
  # Hello World!

    Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum veritatis autem beatae. Eligendi obcaecati pariatur facilis non, consequatur reiciendis voluptate deserunt quo omnis. Ab aspernatur repellendus maxime, sapiente aut recusandae.

    Current route is: {{ $route.path }}

    *Italic*, **bold**, and `monospace`

    ```js
    <script>
      const foo = 'bar';
      console.log(foo);
    </script>

    ```

    Itemized lists look like:

      * this one
      * that one
      * the other one

    > Block quotes are
    > written like so.
    >
    > They can span multiple paragraphs,
    > if you like.
</template>

<script>
export default {
  layout: 'blog'
}
</script>

