<template>
  <header>
    <nav>
      <!-- {{ state.windowWidth }} -->
      <!-- Primary Links -->
      <!-- Hide  by default and show for Screens of greater than 640px  -->
      <div class="hidden sm:flex justify-between p-4 bg-red-100">
        <a href="#">Home</a>
        <a href="#">ABout Us</a>
        <a href="#">Gallery</a>
        <a href="#">News</a>
        <a href="#">Contact Us</a>
      </div>

      <!-- Secondary Links -->

      <!-- Mobile Hambuger  -->
       <input type="checkbox" id="nav__checkbox"  />
        <div class="flex justify-end">
          <label for="nav__checkbox">
          <svg
            viewBox="0 0 100 80"
            width="40"
            height="40"
            class="sm:hidden p-2"
          >
            <rect width="100" height="20"></rect>
            <rect y="30" width="100" height="20"></rect>
            <rect y="60" width="100" height="20"></rect>
          </svg>
        </label>
        </div>
      <!-- Hide  for Screens of greater than 640px  -->
      <div  id="MobileMenu" class="mobileMenu sm:hidden">
        <ul class="flex flex-col text-center justify-between h-screen">
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
              class="block px-4 py-4 hover:bg-green-100 transition duration-300"
              >About Us</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block px-4 py-4 hover:bg-green-100 transition duration-300"
              >Gallery</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block px-4 py-4 hover:bg-green-100 transition duration-300"
              >News</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block px-4 py-4 hover:bg-green-100 transition duration-300"
              >Contact Us</a
            >
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>



<style>


#nav__checkbox{
    display: none;
}

.mobileMenu ul {
  display: none;
}


#nav__checkbox:checked ~ .mobileMenu ul{
  display: flex;
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


