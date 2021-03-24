<template>
  <div class="about text-center mx-64">
    <!-- We're not using the logo component here (not using the default size) -->
    <div class="logo pb-4">
      <NuxtLink to="/">
        <img
          src="~/assets/img/logo.png"
          class="w-12 h-12 mx-auto animate-spin-slow"
        />
      </NuxtLink>
    </div>
    <div class="body">
      <div class="title pb-4">
        <h3
          class="sm:text-5xl text-2xl font-sans font-semibold text-gray-900 dark:text-white"
        >
          Who are we?
        </h3>
      </div>
      <div class="body text-gray-900 dark:text-white font-sans text-xl">
        <p>
          The <span class="text-purple-700">Luna</span> Collective is a small
          army of transgender girls who have "Luna" in their names. We kind of
          want to make stuff for people. We think they'd like it, y'know?
        </p>
        <p class="pt-4">
          So far, we only have four members, who are listed below:
        </p>
        <div
          class="grid grid-cols-4 gap-4 text-gray-900 dark:text-white font-sans font-medium text-xl pt-4"
        >
          <div>LunaIsNotABoy</div>
          <div>Luna Frankland</div>
          <div>LunaRin</div>
          <div>SkaiLuna</div>
          <div>
            <img
              src="~/assets/img/profiles/lunaisnotaboy.png"
              class="w-24 h-24 mx-auto rounded-full"
            />
          </div>
          <div>
            <img
              src="~/assets/img/profiles/lunafrankland.png"
              class="w-24 h-24 mx-auto rounded-full"
            />
          </div>
          <div>
            <img
              src="~/assets/img/profiles/lunarin.png"
              class="w-24 h-24 mx-auto rounded-full"
            />
          </div>
          <div>
            <img
              src="~/assets/img/profiles/skailuna.png"
              class="w-24 h-24 mx-auto rounded-full"
            />
          </div>
          <div>(she/they)</div>
          <div>(she/her)</div>
          <div>(she/her)</div>
          <div>(gey/gem)</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
