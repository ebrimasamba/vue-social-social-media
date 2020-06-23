<template>
  <div>
    <a
      href="#"
      class="group flex items-center px-5 leading-5 font-medium hover:bg-gray-100 focus:outline-none focus:bg-gray-200 transition ease-in-out duration-150"
    >
      <div class="mr-3">
        <div>
          <img
            class="inline-block h-12 w-12 rounded-full"
            src="../assets/IMG_20190912_201913_342.jpg"
            alt
          />
        </div>
      </div>
      <div class="border-b flex-1 py-6 border-gray-200 flex justify-between">
        <div>
          <p class="text-base font-bold">{{contactName}}</p>
          <span class="text-gray-500 font-semibold">boi how is nodejs?</span>
        </div>
        <small class="text-gray-400">9:41pm</small>
      </div>
    </a>
  </div>
</template>

<script>
export default {
  name: "ContactChatReceived",
  props: {
    contactName: String
  }
};
</script>

<style>
</style>