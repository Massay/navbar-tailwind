<template>
  <div class="sm:container sm:mx-auto h-screen">
    <header>
      <nav class="fixed left-0 right-0 top-0 z-50 bg-green-600">
        <!-- {{ state.windowWidth }} -->
        <!-- Primary Links -->
        <!-- Hide  by default and show for Screens of greater than 640px  -->
        <div class="hidden sm:flex justify-between p-4">
          <a href="#">Home</a>
          <a href="#">ABout Us</a>
          <a href="#">Gallery</a>
          <a href="#">News</a>
          <a href="#">Contact Us</a>
        </div>

        <!-- Secondary Links -->

        <!-- Mobile Hambuger  -->
        <input type="checkbox" id="nav__checkbox" />
        <div class="flex justify-end">
          <label for="nav__checkbox" class="sm:hidden">
            <svg
              viewBox="0 0 100 80"
              width="40"
              height="40"
              class="p-2 open"
            >
              <rect width="100" height="20"></rect>
              <rect y="30" width="100" height="20"></rect>
              <rect y="60" width="100" height="20"></rect>
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-11 w-11 close p-2 font-extrabold"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              />
            </svg>
          </label>
        </div>
        <!-- Hide  for Screens of greater than 640px  -->
        <div id="MobileMenu" class="mobileMenu sm:hidden">
          <ul class="flex flex-col text-center justify-between">
            <li>
              <a
                href="#"
                class="
                  block
                  px-4
                  py-4
                  hover:bg-green-100
                  transition
                  duration-300
                  bg-red-300
                "
                >Home</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  px-4
                  py-4
                  hover:bg-green-100
                  transition
                  duration-300
                "
                >About Us</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  px-4
                  py-4
                  hover:bg-green-100
                  transition
                  duration-300
                "
                >Gallery</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  px-4
                  py-4
                  hover:bg-green-100
                  transition
                  duration-300
                "
                >News</a
              >
            </li>
            <li>
              <a
                href="#"
                class="
                  block
                  px-4
                  py-4
                  hover:bg-green-100
                  transition
                  duration-300
                "
                >Contact Us</a
              >
            </li>
          </ul>
        </div>
      </nav>
    </header>

    <div
      id="wrapper"
      class="
        grid grid-cols-1
        relative
        sm:grid-cols-2
        md:grid-cols-4
        sm:mt-16
        p-2
        sm:p-0
        gap-3
        sm:gap-0
        mt-10
      "
    >
      <div class="h-48 bg-purple-300">div 1</div>
      <div class="h-48 bg-gray-200">div 2</div>
      <div class="h-48 bg-red-200">div 3</div>
      <div class="h-48 bg-yellow-200">div 4</div>
      <div class="h-48 bg-blue-200">div 5</div>
      <div class="h-48 bg-green-200">div 6</div>

      <div
        class="
          bg-red-400
          w-10
          h-10
          rounded-full
          text-center
          flex
          items-center
          justify-center
          p-2
          sm:p-8
          my-2
          fixed
          bottom-6
          sm:bottom-16
          right-4
        "
      >
        Icon
      </div>
    </div>
  </div>
</template>



<style>
#nav__checkbox {
  display: none;
}
.close{
  display: none;
}
.mobileMenu ul {
  display: none;
}

#nav__checkbox:checked ~ .mobileMenu ul {
  display: flex;
}

#nav__checkbox:checked ~ div label .open {
  display: none;
}

#nav__checkbox:checked ~ div  label .close {
  display: block;
}
</style>


<script>
import { defineComponent, onMounted, nextTick, ref, reactive } from "vue";

export default defineComponent({
  setup() {
    const state = reactive({
      width: window.innerWidth,
    });

    function clickMenu() {
      const MenuBtn = document.querySelector("#MenuBtn");
      const MobileMenu = document.querySelector("#MobileMenu");
      MobileMenu.classList.toggle("hidden");
      MenuBtn.innerHTML = `X`;
    }

    function onResize() {
      state.windowWidth = window.innerWidth;
      const MobileMenu = document.querySelector("#MobileMenu");
    }

    onMounted(() => {
      nextTick(() => {
        window.addEventListener("resize", onResize);
      });
    });

    return {
      clickMenu,
      state,
    };
  },
});
</script>


