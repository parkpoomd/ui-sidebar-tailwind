<template>
  <div class="flex h-screen bg-gray-200 font-nunito">
    <Sidebar />
    <div class="flex-1">
      <div class="h-16 bg-white">Toolbar</div>
      <main>Content</main>
    </div>
  </div>
</template>

<script>
import Sidebar from "@/components/Sidebar";

export default {
  name: "App",

  components: {
    Sidebar,
  },
};
</script>
