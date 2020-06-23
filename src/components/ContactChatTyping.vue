<template>
  <div>
    <a
      href="#"
      class="group flex items-center px-5 leading-5 font-medium hover:bg-gray-100 focus:outline-none focus:bg-gray-200 transition ease-in-out duration-150"
    >
      <div class="mr-3">
        <div>
          <img class="inline-block h-12 w-12 rounded-full" src="../assets/realtor_1.jpg" alt />
        </div>
      </div>
      <div class="border-b flex-1 py-6 border-gray-200 flex justify-between">
        <div>
          <p class="text-base font-bold">Mariatou Conteh</p>
          <Typing />
        </div>
        <div>
          <MessageTime time="9:41pm" />
          <MessageBadge messages="12" />
        </div>
      </div>
    </a>
  </div>
</template>

<script>
import MessageBadge from "./MessageBadge";
import MessageTime from "./MessageTime";
import Typing from "./Typing";

export default {
  name: "ContactChatTyping",
  components: {
    MessageBadge,
    MessageTime,
    Typing
  }
};
</script>

<style>
</style>