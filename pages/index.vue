<template>
  <section class="relative">

    <header class="h-auto md:h-1/4 px-4 py-6 flex justify-center">
      <logo />
    </header>

    <div class="container mx-auto h-auto md:h-1/2">
      <div class="flex justify-center items-center relative">
        <div class="w-3/4 p-4">
          <h2 class="text-5xl font-light mb-8 text-center">
            <span>Hi, I'm <span class="font-serif font-normal">Warda</span></span>
          </h2>
          <p class="text-3xl font-light leading-normal text-center">
            I'm a freelance frontend developer from Davao City, Philippines.
            I build awesome websites using Expression Engine and WordPress.
          </p>
        </div>
      </div>
    </div>
    
    <mascot />
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
