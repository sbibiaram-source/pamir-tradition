<script setup lang="ts">

</script>

<template>
  <nav class="bg-[#a30000] p-4">
    <div class="container mx-auto flex flex-col lg:flex-row justify-between items-center">
      <div class="text-white font-bold text-3xl mb-4 lg:mb-0 hover:text-orange-600 hover:cursor-pointer">Pamirian tradition
      </div>

      <div class="lg:hidden">
        <button class="text-[#bbf5a3] focus:outline-none">
          <svg
              class="h-6 w-6"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
          >
            <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="2"
                d="M4 6h16M4 12h16m-7 6h7"
            ></path>
          </svg>
        </button>
      </div>

      <div class="lg:flex flex-col lg:flex-row lg:space-x-4 lg:mt-0 mt-4 flex flex-col items-center text-xl">
        <NuxtLink to="/" class="text-white  px-4 py-2 hover:text-orange-600 ">Home</NuxtLink>
        <NuxtLink to="/about" class="text-white  px-4 py-2 hover:text-orange-600 ">About traditions</NuxtLink>
        <NuxtLink to="/tradition" class="text-white  px-4 py-2  hover:text-orange-600">Traditional foods</NuxtLink>
        <NuxtLink to="/culture" class="text-white  px-4 py-2  hover:text-orange-600">Culture</NuxtLink>
        <NuxtLink to="/contact" class="text-white  px-4 py-2  hover:text-orange-600">Contact Us</NuxtLink>
      </div>
    </div>

  </nav>


  <!-- Use this component with react -->
  <!-- function App() {
      const [isOpen, setIsOpen] = useState(false);

      const toggleMenu = () => {
          setIsOpen(!isOpen);
      };

      return (
          <div>
              {/* Navbar */}
              <nav className="bg-black p-4">
                  <div className="container mx-auto flex flex-col lg:flex-row justify-between items-center">
                      <div className="text-white font-bold text-3xl mb-4 lg:mb-0 hover:text-orange-600 hover:cursor-pointer">Porfolio </div>

                      {/* Hamburger menu for small screens */}
                      <div className="lg:hidden">
                          <button onClick={toggleMenu} className="text-white focus:outline-none">
                              <svg
                                  className="h-6 w-6"
                                  fill="none"
                                  stroke="currentColor"
                                  viewBox="0 0 24 24"
                                  xmlns="http://www.w3.org/2000/svg"
                              >
                                  <path
                                      strokeLinecap="round"
                                      strokeLinejoin="round"
                                      strokeWidth="2"
                                      d="M4 6h16M4 12h16m-7 6h7"
                                  ></path>
                              </svg>
                          </button>
                      </div>

                      {/* Navigation links */}
                      <div className={`lg:flex flex-col lg:flex-row ${isOpen ? 'block' : 'hidden'} lg:space-x-4 lg:mt-0 mt-4 flex flex-col items-center text-xl`}>
                          <a href="/" className="text-white  px-4 py-2 hover:text-orange-600 ">Home</a>
                          <a href="#Projects" className="text-white  px-4 py-2  hover:text-orange-600">Projects</a>
                          <a href="/" className="text-white  px-4 py-2  hover:text-orange-600">About</a>
                          <a href="/" className="text-white  px-4 py-2  hover:text-orange-600">Contact Me</a>
                      </div>
                  </div>

              </nav>


          </div>
      );
  }

  export default App; -->
</template>

<style scoped>

</style>