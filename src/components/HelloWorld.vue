<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Jersey+25&display=swap" rel="stylesheet">

  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      <p>Hello, my name is Lucas (aka DevSecCat), Welcome to my laboratory!</p>
      <p>This is where I post some fun experiments, and some articles about stuff I like.</p>
      <p>Feel free to reach me out in my social networks.</p>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-family: "Jersey 25", sans-serif;
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
