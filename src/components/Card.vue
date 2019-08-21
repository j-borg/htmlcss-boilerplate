<script>
export default {
  props: {
    type: String
  }
};
</script>

<template>
  <section class="card flex" :class="type">
    <header class="card__header">
      <img src="/assets/card-image.jpg" alt="Image" />
    </header>

    <div class="card__content flex flex--column">
      <p class="card__subtitle">Card subtitle</p>
      <h2 class="card__title">Card title</h2>
      <p class="card__body">
        Donec mi odio, faucibus at, scelerisque quis, convallis in, nisi. Praesent nec nisl a
        purus blandit viverra.
      </p>
      <a class="card__link" href="/">Lees meer</a>
    </div>
  </section>
</template>
