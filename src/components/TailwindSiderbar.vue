<template>
  <div
    id="sidebar"
    class="fixed inset-0 h-full bg-white z-90 w-full border-b -mb-16 lg:-mb-0 lg:static lg:h-auto lg:overflow-y-visible lg:border-b-0 lg:pt-0 lg:w-1/4 lg:block lg:border-0 xl:w-1/5 hidden pt-16"
  >
    <div
      id="navWrapper"
      class="h-full overflow-y-auto scrolling-touch lg:h-auto lg:block lg:relative lg:sticky lg:bg-transparent overflow-hidden lg:top-16 bg-white"
    >
      <div
        id="nav"
        class="px-6 pt-6 overflow-y-auto text-base lg:text-sm lg:py-12 lg:pl-6 lg:pr-8 sticky?lg:h-(screen-16)"
      >
        <div class="mb-8">
          <h5
            class="mb-3 lg:mb-2 uppercase tracking-wide font-bold text-sm lg:text-xs text-gray-500"
          >
            开始学习
          </h5>
        </div>
        <ul>
          <li class="mb-3 lg:mb-1">
            <a
              class="px-2 -mx-2 py-1 transition duration-200 ease-in-out relative block text-teal-600 font-medium"
              href="#"
            >
              <span
                class="rounded absolute inset-0 bg-teal-200 opacity-25"
              ></span>
              <span class="relative">介绍</span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
