<template>
  <div>
    <div class="sticky top-0 bg-gradient -mx-5 z-10">
      <div class="flex flex justify-between items-center py-5 px-7 text-gray-100">
        <i class="fas fa-comment text-2xl"></i>
        <img
          class="inline-block h-12 w-12 rounded-full"
          src="../assets/IMG-20190916-WA0017.jpg"
          alt
        />
        <!-- <p class="text-base text-white"> -->
        <!-- <SettingsIcon /> -->
        <i class="fa fa-cog text-2xl"></i>
        <!-- </p> -->
      </div>
      <div class="relative">
        <i class="fa fa-search absolute top-1/2 transform -translate-y-1/2 left-3 text-gray-300"></i>
        <input
          type="text"
          class="w-full bg-gray-100 py-3 px-10 text-cente border-b-2 focus:border-blue-500"
          placeholder="search message or contact"
        />
      </div>
    </div>
  </div>
</template>

<script>
import { SettingsIcon } from "vue-feather-icons";
export default {
  name: "ProfileHeader",
  components: SettingsIcon
};
</script>

<style>
</style>