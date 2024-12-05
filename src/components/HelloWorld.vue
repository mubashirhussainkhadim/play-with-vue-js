<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">Mubashir Hussain</h1>
    <h3>
      Experienced Full Stack Web Developer specializing in Angular, Laravel, PHP, and WordPress.
      Proven track record in healthcare and IT sectors, optimizing performance and user experience.
      Expertise in web app development, security, and collaborative problem-solving. Let's discuss
      enhancing your online presence!
      <a href="/" target="_blank" rel="noopener">Mubashirhussain</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
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
