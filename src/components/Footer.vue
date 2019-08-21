<template>
  <footer class="app-footer">
    <div class="app-footer__inner container flex flex--row">
      <ul v-for="index in 3" :key="index" class="app-footer__list">
        <Li class="app-footer__list-item">
          <a class="app-footer__link" href="/">Link 1</a>
        </Li>
        <Li class="app-footer__list-item">
          <a class="app-footer__link" href="/">Link 2</a>
        </Li>
        <Li class="app-footer__list-item">
          <a class="app-footer__link" href="/">Link 3</a>
        </Li>
        <Li class="app-footer__list-item">
          <a class="app-footer__link" href="/">Link 4</a>
        </Li>
      </ul>
    </div>
  </footer>
</template>