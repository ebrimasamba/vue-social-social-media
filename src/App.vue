<template>
  <div id="app" class="flex h-screen text-sm overflow-x-auto">
    <div
      class="relative bg-white h-full w-full lg:w-1/3 shadow overflow-y-auto px-5 border-r border-gray-200"
    >
      <ProfileHeader />
      <NavigationalTabs />
      <div>
        <ContactChatTyping />
        <ContactChatReceived contactName="Abdos" />
        <ContactChatRead />
        <ContactChatDelivered />
        <ContactChatTyping />
        <ContactChatTyping />
        <ContactChatTyping />
        <ContactChatTyping />
      </div>
    </div>
    <div class="relative h-full flex-1 overflow-y-auto px-7 hidden lg:block">
      <ChatHeader />
      <div class="py-5">
        <SentText />
        <ReceivedText />
      </div>
    </div>
  </div>
</template>

<script>
import ProfileHeader from "./components/ProfileHeader";
import ContactChatTyping from "./components/ContactChatTyping";
import NavigationalTabs from "./components/NavigationalTabs";
import ContactChatReceived from "./components/ContactChatReceived";
import ContactChatRead from "./components/ContactChatRead";
import ContactChatDelivered from "./components/ContactChatDelivered";
import ChatHeader from "./components/ChatHeader";
import SentText from "./components/SentText";
import ReceivedText from "./components/ReceivedText";

export default {
  name: "App",
  components: {
    ProfileHeader,
    ContactChatTyping,
    NavigationalTabs,
    ContactChatReceived,
    ContactChatRead,
    ContactChatDelivered,
    ChatHeader,
    SentText,
    ReceivedText
  }
};
</script>

<style>
* {
  font-family: inter;
}

.bg-gradient {
  background-image: linear-gradient(to right, #3f83f8, #1555c4);
}
</style>
