<template>
  <div class="" id="main-page">
    <header>
      <!-- Toogle for Mobile Devices -->
      <input type="checkbox" id="nav_toogler" />
      <label for="nav_toogler" class="sm:hidden flex justify-end">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6 open sm:hidden"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6 close sm:hidden"
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

      <!-- Side Nav for Small Devices -->
      <!-- Menu for Mobile Devices -->
      <div
        class="flex flex-col h-screen bg-sky-800 justify-between sm:hidden"
        id="sidenav"
      >
        <div
          id="user-profile"
          class="flex items-center flex-col p-4 text-white h-full"
        >
          <img
            src="https://1.bp.blogspot.com/-vhmWFWO2r8U/YLjr2A57toI/AAAAAAAACO4/0GBonlEZPmAiQW4uvkCTm5LvlJVd_-l_wCNcBGAsYHQ/s16000/team-1-2.jpg"
            alt=""
            class="w-16 h-16 rounded-full"
          />

          <h3 class="text-lg font-extrabold">Anamilka Roy</h3>
          <h4 class="text-md font-semibold">Designer</h4>
        </div>

        <div id="nav-links">
          <ul class="text-white">
            <li
              class="
                flex
                justify-start
                hover:text-sky-700 hover:bg-white
                px-2
                py-2
              "
            >
              <span
                ><svg
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
                    d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                  /></svg
              ></span>
              <a href="#" class="ml-3">Home</a>
            </li>
            <li
              class="
                flex
                justify-start
                hover:text-sky-700 hover:bg-white
                px-2
                py-3
              "
            >
              <span
                ><svg
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
                    d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"
                  /></svg
              ></span>
              <a href="#" class="ml-3">My Dashboard</a>
            </li>
            <li
              class="
                flex
                justify-start
                hover:text-sky-700 hover:bg-white
                px-2
                py-4
              "
            >
              <span
                ><svg
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
                    d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"
                  /></svg
              ></span>
              <a href="#" class="ml-3">People</a>
            </li>
            <li
              class="
                flex
                justify-start
                hover:text-sky-700 hover:bg-white
                px-2
                py-4
              "
            >
              <span
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                >
                  <path
                    fill-rule="evenodd"
                    d="M3 3a1 1 0 000 2v8a2 2 0 002 2h2.586l-1.293 1.293a1 1 0 101.414 1.414L10 15.414l2.293 2.293a1 1 0 001.414-1.414L12.414 15H15a2 2 0 002-2V5a1 1 0 100-2H3zm11 4a1 1 0 10-2 0v4a1 1 0 102 0V7zm-3 1a1 1 0 10-2 0v3a1 1 0 102 0V8zM8 9a1 1 0 00-2 0v2a1 1 0 102 0V9z"
                    clip-rule="evenodd"
                  /></svg
              ></span>
              <a href="#" class="ml-3">Performance</a>
            </li>
            <li
              class="
                flex
                justify-start
                hover:text-sky-700 hover:bg-white
                px-2
                py-4
              "
            >
              <span
                ><svg
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
                    d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"
                  /></svg
              ></span>
              <a href="#" class="ml-3">Reports</a>
            </li>
            <li
              class="
                flex
                justify-start
                hover:text-sky-700 hover:bg-white
                px-2
                py-4
              "
            >
              <span
                ><svg
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
                    d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                  /></svg
              ></span>
              <a href="#" class="ml-3">Admin</a>
            </li>
            <li
              class="
                flex
                justify-start
                hover:text-sky-700 hover:bg-white
                px-2
                py-2
              "
            >
              <span
                ><svg
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
                    d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                  /></svg
              ></span>
              <a href="#" class="ml-3">Settings</a>
            </li>
          </ul>
        </div>
      </div>
      <!-- End Menu for Mobile Devices -->
      <nav
        class="
          hidden
          sm:block
          bg-red-700
          text-white
          font-semibold
          rounded-lg
          p-2
        "
      >
        <ul class="flex justify-start text-xs">
          <li
            class="
              rounded-md
              p-2
              text-center
              hover:border-b-sky-900
              border-b-4
              hover:cursor-pointer
              flex
              items-end
            "
          >
            <span>
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
                  d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                />
              </svg>
            </span>
            <span>Home</span>
          </li>
          <li
            class="
              rounded-md
              p-2
              text-center
              hover:border-b-sky-900
              border-b-4
              hover:cursor-pointer
              flex
              items-end
            "
          >
            <span
              ><svg
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
                  d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"
                /></svg
            ></span>
            <span>My Dashboard</span>
          </li>
          <li
            class="
              rounded-md
             
              p-2
              text-center
              hover:border-b-sky-900
              border-b-4
              hover:cursor-pointer
              flex
              items-end
            "
          >
            <span
              ><svg
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
                  d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"
                /></svg
            ></span>
            <span>People</span>
          </li>
          <li
            class="
              rounded-md
             
              p-2
              text-center
              hover:border-b-sky-900
              border-b-4
              hover:cursor-pointer
              ml-auto
              flex
              items-end
            "
          >
            <span
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M3 3a1 1 0 000 2v8a2 2 0 002 2h2.586l-1.293 1.293a1 1 0 101.414 1.414L10 15.414l2.293 2.293a1 1 0 001.414-1.414L12.414 15H15a2 2 0 002-2V5a1 1 0 100-2H3zm11 4a1 1 0 10-2 0v4a1 1 0 102 0V7zm-3 1a1 1 0 10-2 0v3a1 1 0 102 0V8zM8 9a1 1 0 00-2 0v2a1 1 0 102 0V9z"
                  clip-rule="evenodd"
                /></svg
            ></span>
            <span>Performance</span>
          </li>
          <li
            class="
              rounded-md
             
              p-2
              text-center
              hover:border-b-sky-900
              border-b-4
              hover:cursor-pointer
              flex
              items-end
            "
          >
            <span
              ><svg
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
                  d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"
                /></svg
            ></span>
            <span>Reports</span>
          </li>
          <li
            class="
              rounded-md
             
              p-2
              text-center
              hover:border-b-sky-900
              border-b-4
              hover:cursor-pointer
              flex
              items-end
            "
          >
            <span
              ><svg
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
                  d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                /></svg
            ></span>
            <span>Admin</span>
          </li>
          <li
            class="
              rounded-md
             
              p-2
              text-center
              hover:border-b-sky-900
              border-b-4
              hover:cursor-pointer
              flex
              items-end
            "
          >
            <span
              ><svg
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
                  d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                /></svg
            ></span>
            <span>Settings</span>
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <div class="grid grid-cols-1 sm:grid-cols-2">
        <div class="bg-red-100">div 1</div>
        <div class="bg-blue-300">div 2</div>
        <div class="bg-sky-400">div 3</div>
        <div class="bg-purple-200">div 4</div>
        <div class="bg-indigo-500">div 5</div>
        <div class="bg-violet-300">div 6</div>
      </div>
    </main>
  </div>
</template>

<style scoped>
#main-page {
  position: relative;
}
#sidenav {
  position: absolute;
  left: -360px;
  transition: all 200ms ease;
}

#nav_toogler {
  display: none;
}

#nav_toogler:checked ~ div#sidenav {
  left: 0;
  transition: all 500ms ease;
}

#nav_toogler:not(:checked) ~ div#sidenav {
  left: -360px;
  transition: all 500ms ease-in-out;
}

.close {
  display: none;
}

#nav_toogler:checked ~ label .open {
  display: none;
}

#nav_toogler:checked ~ label .close {
  display: block;
}
</style>