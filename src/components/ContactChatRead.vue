<template>
  <div>
    <a
      href="#"
      class="group flex items-center px-5 leading-5 font-medium hover:bg-gray-100 focus:outline-none focus:bg-gray-200 transition ease-in-out duration-150"
    >
      <div class="mr-3">
        <div>
          <img class="inline-block h-12 w-12 rounded-full" src="../assets/realtor_4.jpg" alt />
        </div>
      </div>
      <div class="border-b flex-1 py-6 border-gray-200 flex justify-between">
        <div>
          <p class="text-base font-bold">Henrietta Cadet</p>
          <span class="text-gray-500 font-semibold">
            <span class="text-blue-400 mr-1">
              <i class="fas fa-check-double"></i>
            </span>
            Okay i'll look at it whe i have time
          </span>
        </div>
        <MessageTime time="5:43pm" />
      </div>
    </a>
  </div>
</template>

<script>
import MessageTime from "./MessageTime";
export default {
  name: "ContactChatRead",
  components: {
    MessageTime
  }
};
</script>

<style>
</style>