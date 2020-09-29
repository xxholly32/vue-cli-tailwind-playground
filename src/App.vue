<template>
  <div>
    <tailwind-header></tailwind-header>
    <div class="w-full max-w-screen-xl mx-auto px-6">
      <div class="lg:flex -mx-6">
        <!-- sidebar -->
        <tailwind-siderbar></tailwind-siderbar>
        <!-- content -->
        <div
          id="content-wrapper"
          class="min-h-screen w-full lg:static lg:max-h-full lg:overflow-visible lg:w-3/4 xl:w-4/5"
        >
          <div id="content">
            <div id="app" class="flex">
              <Intro></Intro>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TailwindHeader from "@/components/TailwindHeader.vue";
import TailwindSiderbar from "@/components/TailwindSiderbar.vue";
import Intro from "@/components/Intro.vue";
export default {
  name: "app",
  components: { TailwindHeader, TailwindSiderbar, Intro },
};
</script>
