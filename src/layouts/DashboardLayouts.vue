<template>
  <div class="antialiased w-full min-h-screen text-slate-300 relative py-4">
    <div class="grid grid-cols-12 mx-auto gap-2 sm:gap-4 md:gap-6 lg:gap-10 xl:gap-14 max-w-7xl my-10 px-2">
      <Sidebar></Sidebar>
       <div id="content" class="bg-white/10 col-span-9 rounded-lg p-6 outline outline-cyan-500">
         <router-view></router-view>
       </div>
    </div>
</div>
</template>
<script>
import Sidebar from "../components/dashboard/Sidebar.vue";

export default {
  components: {
  Sidebar
}
};
</script>
<style>
    :root { font-family: 'Inter', sans-serif; }
@supports (font-variation-settings: normal) {
  :root { font-family: 'Inter var', sans-serif; }
}
</style>