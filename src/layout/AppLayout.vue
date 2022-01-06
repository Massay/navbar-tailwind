<template>
  <div class="flex h-screen">
    <div id="sidenav" class="bg-gray-100">
      <div class="flex justify-between flex-col bg-white h-screen">
        <div>
          <div id="title">
            <h3 class="text-3xl text-center bg-gray-400 p-4">Admin Hub</h3>
          </div>
          <ul>
            <li>
              <a
                href="#"
                @click="open = !open"
                class="flex space-x-4 p-2 items-center hover:bg-gray-50"
              >
                <div class="w-10 h-8 rounded-full">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="text-black m-1"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M4 6h16M4 10h16M4 14h16M4 18h16"
                    />
                  </svg>
                </div>
                <div class="flex justify-between w-full items-center">
                  <span>Dasbboard</span>
                  <span
                    ><svg
                      v-if="!open"
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-6 w-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M19 9l-7 7-7-7"
                      />
                    </svg>
                    <svg
                      v-else
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-6 w-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M5 15l7-7 7 7"
                      />
                    </svg>
                  </span>
                </div>
              </a>

              <ul
                class="px-2 mx-2 flex-col pl-8"
                :class="{ flex: open, hidden: !open }"
              >
                <li class="font-semibold bg-red-200 space-y-2 py-2">
                  <a href="#">Child 1</a>
                </li>
                <li><a href="#">Child 2</a></li>
                <li><a href="#">Child 3</a></li>
                <li><a href="#">Child 4</a></li>
              </ul>
            </li>
            <li>
              <a
                href="#"
                class="flex space-x-4 p-2 items-center hover:bg-gray-50"
              >
                <div class="w-10 h-10 rounded-full">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="text-black m-1"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path d="M4 3a2 2 0 100 4h12a2 2 0 100-4H4z" />
                    <path
                      fill-rule="evenodd"
                      d="M3 8h14v7a2 2 0 01-2 2H5a2 2 0 01-2-2V8zm5 3a1 1 0 011-1h2a1 1 0 110 2H9a1 1 0 01-1-1z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </div>
                <span>My Store</span></a
              >
            </li>
            <li>
              <a
                href="#"
                class="flex space-x-4 p-2 items-center hover:bg-gray-50"
              >
                <div class="w-10 h-10 rounded-full">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="text-black m-1"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13 17h8m0 0V9m0 8l-8-8-4 4-6-6"
                    />
                  </svg>
                </div>
                <span>Analytics</span></a
              >
            </li>

            <li>
              <a
                href="#"
                class="flex space-x-4 p-2 items-center hover:bg-gray-50"
              >
                <div class="w-10 h-10 rounded-full">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="text-black m-1"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"
                    />
                  </svg>
                </div>
                <span>Messages</span></a
              >
            </li>
            <li>
              <a
                href="#"
                class="flex space-x-4 p-2 items-center hover:bg-gray-50"
              >
                <div class="w-10 h-10 rounded-full">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="text-black m-1"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"
                    />
                  </svg>
                </div>
                <span>Team</span></a
              >
            </li>
          </ul>
        </div>

        <ul>
          <li class="text-center p-4 hover:bg-gray-200">
            <a href="#">Settings</a>
          </li>

          <div class="text-center">
            <button
              class="
                text-center
                w-full
                rounded-r-full
                p-4
                hover:bg-red-400 hover:text-white hover:font-semibold
              "
            >
              Logout
            </button>
          </div>
        </ul>
      </div>
    </div>

    <div id="main-content" class="flex-auto">
      <div>
        <button
          @click="openNav"
          v-if="open"
          class="m-2 p-2 text-white font-semibold"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 10h16M4 14h16M4 18h16"
            />
          </svg>
        </button>

        <button
          v-else
          @click="closeNav"
          class="m-2 p-2 text-white font-semibold"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
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
        </button>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  setup() {
    const open = ref(false);
    function openNav() {
      console.log("openNav");
      document.getElementById("sidenav").style.width = "250px";
      open.value = !open.value;
      //   document.getElementById("sidenav").style.marginLeft = "250px";
    }

    function closeNav() {
      console.log("closeNav");
      document.getElementById("sidenav").style.width = 0;
      open.value = !open.value;
      //   document.getElementById("sidenav").style.marginLeft = "0";
    }
    return {
      open,
      closeNav,
      openNav,
    };
  },
});
</script>



<style>
#sidenav {
  transition: margin-left 0.5s ;
  transition: width 0.3s linear;
  /* padding: 16px; */
  width: 250px;
}
</style>
