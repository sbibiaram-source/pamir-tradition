<script setup lang="ts">

</script>

<template>
  <div class="relative flex flex-col items-center mx-auto lg:flex-row-reverse lg:max-w-5xl lg:mt-12 xl:max-w-6xl">

    <!-- Image Column -->
    <div class="w-full h-64 lg:w-1/2 lg:h-auto">
      <img class="h-full w-full object-cover" src="https://i0.wp.com/pamirinside.org/wp-content/uploads/2023/05/pamirskaja-odezhda3.jpg?fit=1920%2C1209&ssl=1" alt="">
    </div>
    <!-- Close Image Column -->

    <!-- Text Column -->
    <div
        class="max-w-lg bg-white md:max-w-2xl md:z-10 md:shadow-lg md:absolute md:top-0  lg:w-3/5 lg:left-0  lg:ml-20 xl:ml-12">
      <!-- Text Wrapper -->
      <div class="flex flex-col p-12 md:px-16">
        <h2 class="text-2xl font-medium uppercase text-red-500 lg:text-4xl">About</h2>
        <p class="mt-4">
          The Pamir region, often called "The Roof of the World", is home to ancient and rich cultural traditions preserved for centuries by the Pamiri people. Nestled among the towering mountains of Tajikistan, Afghanistan, China, and Pakistan, the Pamirs are not just a geographical wonder—they're also a living museum of heritage, language, music, and spirituality.
        </p>
        <!-- Button Container -->
        <div class="mt-8">
          <a href="#"
             class="inline-block w-full text-center text-lg font-medium text-gray-100 bg-red-500 border-solid border-2 border-gray-600 py-4 px-10 hover:bg-green-800 hover:shadow-md md:w-48">Read
            More</a>
        </div>
      </div>
      <!-- Close Text Wrapper -->
    </div>
    <!-- Close Text Column -->

  </div>
  <div class="bg-gray-100">
    <div class="container mx-auto px-4 py-8">
      <h1 class="text-4xl font-bold text-center mb-8"></h1>
      <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
        <!-- Large item -->
        <div class="md:col-span-2 md:row-span-2 relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://avatars.mds.yandex.net/i?id=7bdbf930229461a1697b509e88f0e026ba776ab0-5221140-images-thumbs&n=13" alt="Nature" class="w-full h-full object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h3 class="text-2xl font-bold text-white">In village</h3>
              <p class="text-white">Shepherdesses of Pamir</p>
            </div>
          </div>
        </div>

        <!-- Two small items -->
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://www.eliteplusmagazine.com/ckfinder/userfiles/images/batch_Khor1dan6AAAA(1).jpg" alt="Food" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Festiv photo of Pamirian women</h4>
            </div>
          </div>
        </div>
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://avatars.mds.yandex.net/i?id=5c8508d54b6cc3e8a9a2dbae864cd544a3874ded-9181873-images-thumbs&n=13" alt="Technology" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Pamirian wedding style </h4>
            </div>
          </div>
        </div>

        <!-- Three medium items -->
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://avatars.mds.yandex.net/i?id=6834eb591d6a5209c24790a55ffb689bb2f511bd-9860796-images-thumbs&ref=rim&n=33&w=300&h=200" alt="Travel" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Travel Adventures
              Pamir is one of the most famous and interesting trips in Tajikistan</h4>
            </div>
          </div>
        </div>
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://cache3.youla.io/files/images/720_720_out/57/49/574962b014d2f5fc664a4c6b.jpg" alt="Art" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Music tradition
                The traditional rubab (a string instrument) and dambura accompany songs of love, loss, and divine longing.</h4>
            </div>
          </div>
        </div>

        <!-- bottom cards -->
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://avatars.mds.yandex.net/i?id=136ea655ab1abe3cfe00578d11be96e24527df64-16492246-images-thumbs&n=13" alt="Sport" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Pamirian house(Pomeri Chorkhona)</h4>
            </div>
          </div>
        </div>
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://avatars.mds.yandex.net/i?id=ba2ec2492e62fb8c4e22c8ec551229658a77d172-8497450-images-thumbs&n=13" alt="Sport" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Wakhan people</h4>
            </div>
          </div>
        </div>
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://avatars.mds.yandex.net/i?id=3d0e1a6a4f1c42afe7d53e299cd004efc012fe3f-9243502-images-thumbs&ref=rim&n=33&w=356&h=200" alt="Sport" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Photo of Murgaba</h4>
            </div>
          </div>
        </div>
        <div class="relative overflow-hidden rounded-2xl shadow-lg group">
          <img src="https://i.pinimg.com/736x/f8/8a/ca/f88acaedaca05c7f9dc2017454692428.jpg" alt="Sport" class="w-full h-48 object-cover">
          <div
              class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
            <div class="absolute bottom-0 left-0 right-0 p-4">
              <h4 class="text-xl font-bold text-white">Pamirian Girls
             One of the beautiful girls in the world. </h4>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>