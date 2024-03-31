<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <div class="bg">
    <header>
      <img
        alt="Vue logo"
        class="logo"
        src="./assets/me1.png"
        width="180"
        height="180"
      />

      <div class="wrapper">
        <HelloWorld msg="Muhammad Shahreza Khadafi!" />
      </div>
    </header>
  </div>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
.biok {
  background-color: #294471;
}

.bg {
  border-top: 634px solid #294471;
  border-right: 80px solid hsl(217, 48%, 56%);
  box-shadow: -10px 10px 10px;
}

header {
  line-height: 1.1;
}

.logo {
  display: block;
  margin: 0 auto 280px 200px;
  border-radius: 50%;
  box-shadow: -10px 10px 10px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin-top: -600px;
  }

  header .wrapper {
    color: #e3d2c8;
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
    margin-top: -450px;
    margin-left: -500px;
    margin-right: -100px;
    font-size: 300px;
    font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
  }
}
</style>
