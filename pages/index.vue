<template>
  <section class="relative">

    <header class="h-auto mb-16 lg:h-1/4 lg:mb-0 px-4 py-6 flex justify-center">
      <logo />
    </header>

    <mascot />

    <!-- <art /> -->

    <div class="relative container mx-auto h-auto md:h-1/2 lg:flex lg:items-center z-30">
      <div class="flex justify-center items-center relative">
        <div class="w-3/4 p-2 lg:py-4 lg:px-10">
          <h2 class="text-5xl font-light mb-8 text-center">
            <span>Hi, I'm <span class="font-serif font-normal">Warda</span></span>
          </h2>
          <p class="text-2xl mb-8 md:text-3xl font-light leading-normal text-center">
            I'm a freelance frontend developer from Davao City, Philippines.
            I build awesome websites using ExpressionEngine and WordPress.
          </p>
        </div>
      </div>
    </div>

  </section>
</template>

<script>
import Art from '~/components/Art'
import Logo from '~/components/Logo'
import Mascot from '~/components/Mascot'

export default {
  components: {
    Art,
    Logo,
    Mascot
  },

  data() {
    return {
      greet: false
    }
  },

  methods: {
    toggleGreeting(greet) {
      this.greet = greet
    }
  }
}
</script>
