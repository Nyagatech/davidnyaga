<template>
  <div class="container mx-auto border-x border-gray-900 bg-slate-950">
    <div class="flex justify-center">
      <Navbar />
    </div>
    <div class="mt-20">
      <Image class="mx-4" />
    </div>
    <div>
      <h1 class="text-slate-600 font-bold text-2xl px-4 my-6">FullStack Developer and <br> Internet Entrepreneur.</h1>
    </div>
    <div class="px-4 my-6 md:w-1/2 md:mx-auto">
      <p class="my-4">I’m David, a fullstack developer and entrepreneur based in Kenya. I’m
        the creator of Spire Rentals, a platform that allows property owners to manage their apartments.</p>
      <p class="my-4">My main tools of trade are Nuxt.Js, Vue.Js, Tailwind CSS and Laravel. I am proficient in both
        frontend and
        backend development, and my only code editor is VS Code. Yes, I am a full-time V-coder!</p>
      <p class="my-4">
        Outside work, I play chess and read chess books. I am a big fan of Jobavo London System for white and the Caro
        Kann Defense for black. My elo rating on Lichess is around <span class="text-slate-600">1700+</span>. But I am
        striving to get to <span class="text-slate-600">2000+</span>.
      </p>
      <p class="my-4">Why am I building this portfolio? I want it to be my personal online journal. And I am happy to
        have you as my guest!</p>
      <div>
        <a href="https://github.com/Nyagatech">
          <Icon name="uil:github" class="w-6 h-6 my-4 mx-4" />
        </a>
        <a href="https://www.linkedin.com/in/david-nyaga-3a5a13247" class="text-slate-600">
          <Icon name="uil:linkedin" class="w-6 h-6 my-4 mx-4" />
        </a>
      </div>
      <Footer />
    </div>
  </div>
</template>