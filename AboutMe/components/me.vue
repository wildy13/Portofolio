<template>
  <div class="grid grid-rows-4 bg-zinc-900">
    <div class="shrink-0 pointer-events-auto row-start-1 h-24 border-b-2 border-zinc-800">
      <div class="flex items-start border contents">
        <div class="relative">
          <div class="top-0 left-0 font-sans flex justify-between items-center">
            <div class="flex items-center">
              <img src="../assets/img/me.jpeg" class="rounded-full h-16 w-16 object-cover ml-2 mt-2" />
              <div class="text-center ml-1 text-white">Wildy Johanes Simanjuntak</div>
            </div>
            <div class="mr-2 text-white">
              <a class="mx-2 none">Project</a>
              <a class="mx-2 none">Contact</a>
              <a class="mx-2 none">Github</a>
              <a class="mx-2 none">Linkedin</a>
              <a class="mx-2 none">Instagram</a>
              <div class="fixed z-0 h-0 top-0 right-0 overflow-y-hidden">
                <div class="navigation text-center mt-7 top-20 w-40">
                  <a class="block text-zinc-300 p-2 text-sm no-underline" href="https://github.com/wildy13">Github</a>
                  <a class="block text-zinc-300 p-2 text-sm no-underline" href="https://www.linkedin.com/in/wildy-simanjuntak-181a691a4">linkedin</a>
                  <a class="block text-zinc-300 p-2 text-sm no-underline" href="https://www.instagram.com/jo.14m/">Instagram</a>
                </div>
              </div>
              <button class="hamburger mr-4 mr-4" @click="show()">
                <div id="bar1" class="bar" />
                <div id="bar2" class="bar" />
                <div id="bar3" class="bar" />
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="text-slate-200 grid grid-cols-4 gap-4 items-center row-start-2 row-span-3">
      <div class="col-start-1 col-span-3 ml-10">
        <div class="text-xl font-sans font-semibold">Hi, I'm Wildy Johanes Simanjuntak</div>
        <div class="font-normal text-2xl">Web Developer</div>
        <p class="text-sm font-normal text-zinc-300 mt-10">
          I'm from Batam Island, Indonesia and i had experience about Web Developer at
          the Labtech Internatonal Ltd as a intern Fullstack Developer, and either as
          production employee at Nok Freudenberg Sealing Technologies for a year, etc.
          i had worked on various projects, and maybe you can go to my Github for detail.
        </p>
        <div class="mt-4">
          <div class="flex items-center bg-slate-400 rounded-lg w-36 justify-center hover:bg-zinc-900 hover:text-slate-200">
            <img src="../assets/img/email.svg" class="h-8 w-6">
            <a href="mailto:wildy.simanjuntak13@gmail.com" class="ml-2">Hire Me</a>
            </img>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    show () {
      document.querySelector('.hamburger').classList.toggle('open')
      document.querySelector('.navigation').classList.toggle('active')
    }
  }
}
</script>