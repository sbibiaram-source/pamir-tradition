<script setup lang="ts">

</script>

<template>
  <div class="relative px-6 lg:px-8 dark:bg-gray-800">
    <div class="mx-auto max-w-3xl pt-20 pb-32 sm:pt-48 sm:pb-40">
      <div>
        <div>
          <h1 class="text-4xl font-bold tracking-tight sm:text-center sm:text-6xl text-[#a30000]">
            Pamirian tradition.
          </h1>
          <p class="mt-6 text-lg leading-8 text-gray-600 sm:text-center dark:text-gray-200">
            The Pamir Mountains, located mainly in Tajikistan, are home to unique and ancient cultural traditions.Family and community play a central role in Pamiri tradition. Hospitality is a sacred duty, and guests are treated with great honor.
          </p>
          <div class="mt-8 flex gap-x-4 sm:justify-center">
            <NuxtLink to="/about"
               class="inline-block rounded-lg bg-red-500 px-4 py-1.5 text-base font-semibold leading-7 text-white shadow-sm ring-1 ring-indigo-600 hover:bg-indigo-700 hover:ring-indigo-700">
              About
              <span aria-hidden="true" class="text-indigo-200">→</span>
            </NuxtLink>
            <NuxtLink to="/contact"
               class="inline-block rounded-lg px-4 py-1.5 text-base font-semibold leading-7 text-gray-900 dark:text-gray-100 ring-1 ring-gray-900/10 hover:ring-gray-900/20">
              Contact Us
              <span aria-hidden="true" class="text-black">→</span>
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </div>
  <section class="text-gray-600 -mt-20 pb-6">
    <div class="container mx-auto flex px-5  md:flex-row flex-col items-center">
      <div
          class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-red-500">My Homeland
          <br class="hidden lg:inline-block">Culture
        </h1>
        <p class="mb-8 leading-relaxed">The Pamirian culture originates from the mountainous Pamir region. It is rich in history and tradition, shaped by centuries of isolation and a unique blend of Persian, Central Asian, and local influences.The Pamiri people speak several Eastern Iranian languages, such as Shughni, Wakhi, and Ishkashimi, and many follow the Ismaili branch of Islam. Their culture is known for its colorful clothing, intricate handicrafts, hospitality, and oral storytelling traditions. Music and poetry play a key role in community life, often reflecting themes of love, nature, and spiritual devotion.</p>

      </div>
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
        <img class="object-cover object-center rounded" alt="hero" src="https://avatars.mds.yandex.net/i?id=05e4f3c4c749593cf3b6433cf9652bf454cef139-9043076-images-thumbs&n=13">
      </div>
    </div>
  </section>
  <section>
    <div class="relative items-center w-full px-5 py-12 mx-auto md:px-12 lg:px-24 max-w-7xl">
      <div class="grid w-full grid-cols-1 gap-6 mx-auto lg:grid-cols-3">
        <div class="p-6">
          <img class="object-cover object-center w-full mb-8 lg:h-48 md:h-36 rounded-xl" src="https://avatars.mds.yandex.net/i?id=65ffd19237952ec1438ea9b12cc07f3207f5f08b-16346665-images-thumbs&n=13" alt="blog">

          <h1 class="mx-auto mb-8 text-2xl font-semibold leading-none tracking-tighter text-red-500 lg:text-3xl">Tradition</h1>
          <p class="mx-auto text-base leading-relaxed text-gray-500">
            High in the majestic Pamir Mountains, where the sky feels close enough to touch, the Pamiri people keep ancient traditions alive.
            Weddings are grand, multi-day celebrations filled with music, dancing, and symbolic rituals like the tying of scarves and sharing of traditional dishes such as osh (rice pilaf).</p>                <div class="mt-4">
          <NuxtLink to="/trad2" class="inline-flex items-center mt-4 font-semibold text-red-500 lg:mb-0 hover:text-neutral-600" title="read more"> Read More » </NuxtLink>
        </div>
        </div>
        <div class="p-6">
          <img class="object-cover object-center w-full mb-8 lg:h-48 md:h-36 rounded-xl" src="https://avatars.mds.yandex.net/i?id=4dd9d32c635bbfc7d441324d47bab116282ce649-5210611-images-thumbs&n=13" alt="blog">

          <h1 class="mx-auto mb-8 text-2xl font-semibold leading-none tracking-tighter text-neutral-600 lg:text-3xl">People</h1>
          <p class="mx-auto text-base leading-relaxed text-gray-500">
            The Pamir peoples are native to the highlands of the Pamir Mountains, mainly in eastern Tajikistan (Gorno-Badakhshan), northern Afghanistan, and parts of China and Pakistan. Living at some of the highest altitudes in the world, they have adapted to a harsh yet breathtakingly beautiful environment, earning the nickname "people of the roof of the world.Despite geographical isolation, Pamir communities are culturally rich—famous for their music, poetry, hospitality, and oral storytelling." </p>                <div class="mt-4">
          <NuxtLink to="/people" class="inline-flex items-center mt-4 font-semibold text-black lg:mb-0 hover:text-neutral-600" title="read more"> Read More » </NuxtLink>
        </div>
        </div>
        <div class="p-6">
          <img class="object-cover object-center w-full mb-8 lg:h-48 md:h-36 rounded-xl" src="https://avatars.mds.yandex.net/i?id=7eebd3159823b3304ccaa2186187b1852a3e9998-5137308-images-thumbs&n=13" alt="blog">

          <h1 class="mx-auto mb-8 text-2xl font-semibold leading-none tracking-tighter text-red-500 lg:text-3xl">Pamir mountains</h1>
          <p class="mx-auto text-base leading-relaxed text-gray-500">
            The Pamir Mountains rise like ancient giants where Central Asia touches the sky. Known as the "Roof of the World,For centuries, traders, travelers, and explorers crossed these mountains on the Silk Road. </p>                <div class="mt-4">
          <NuxtLink to="/mountains" class="inline-flex items-center mt-4 font-semibold text-red-500 lg:mb-0 hover:text-neutral-600" title="read more"> Read More » </NuxtLink>
        </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>