<template>
  <div>
    <div class="sticky top-0 bg-gradient -mx-7 shadow-md">
      <div
        class="group flex items-center px-7 leading-5 font-medium focus:outline-none transition ease-in-out duration-150"
      >
        <div class="mr-3">
          <div>
            <img
              class="inline-block h-16 w-16 rounded-full"
              src="../assets/IMG_20190912_201913_342.jpg"
              alt
            />
          </div>
        </div>

        <div class="flex-1 py-6 flex justify-between items-center">
          <div class="text-white">
            <p class="text-xl font-bold">Abdou Jammeh</p>
            <span class="text-gray-100 text-sm">Hey There, I'm on whatsapp</span>
          </div>
          <div class="flex text-white">
            <i class="text-2xl mr-10 fa fa-search"></i>

            <i class="text-2xl mr-10 fa fa-paperclip"></i>

            <i class="text-2xl fa fa-phone"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ChatHeader"
};
</script>

<style>
</style>