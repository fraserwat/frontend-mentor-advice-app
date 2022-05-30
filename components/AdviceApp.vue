<!-- Please remove this file from your project -->
<template>
  <section class="[ app-container ] [ bg-dark-grayish-blue max-width-540 pad-900 align-center rad-15 ]">
    <div class="advice">
      <h1 class="color-neon-green text-300 gap-bottom-600">Advice #{{ adviceNo }}</h1>
      <h2 class="color-light-cyan">“{{ adviceText }}”</h2>
    </div>
    <button class="[ reroll ] [ bg-neon-green ]" @click="rerollAdviceCall"/>
  </section>
</template>

<script>
export default {
  name: 'NuxtTutorial',
  data () {
    return {
      adviceNo: 117,
      adviceText: "It is easy to sit up and take notice, what's difficult is getting up and taking action."
    }
  },
  methods: {
  }
}
</script>
