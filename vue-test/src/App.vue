<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You frickin' did it, kid." />
    </div>
  </header>

  <main>
    <TheWelcome />
    {{ edit_1 }} <!-- Added new div -->
    <div class="small-text">Oh hey, you found the secret message. Good for you. You're very observant. We all like you</div>
    {{ edit_1 }} <!-- End of new div -->
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

main { 
  background-color: #e6faff; /* Added background color */
}

.small-text { /* New class for smaller text */
  font-size: 0.5rem; /* Adjust the size as needed */
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
    background-color: #ffe6e6;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
