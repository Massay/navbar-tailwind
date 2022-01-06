<template>
  <div class="grid grid-cols-12 h-screen">
    <aside class="bg-red-200 col-span-2">
      <nav>
        <ul>
          <li>
            <a
              href="#"
          
              class="flex justify-between p-3 bg-blue-100 m-2 homeMenu"
            >
              <span>Home</span>
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
                  d="M19 9l-7 7-7-7"
                />
              </svg>
            </a>
            <ul class="pl-7 menu-items hidden">
              <li><a href="#">Menu 1</a></li>
              <li><a href="#">Menu 2</a></li>
              <li><a href="#">Menu 3</a></li>
              <li><a href="#">Menu 4</a></li>
            </ul>
          </li>
          <li class="flex justify-between p-3 bg-blue-100 m-2 ">
            <a href="#" class="homeMenu">Gallery</a>
             <ul class="pl-7 menu-items hidden">
              <li><a href="#">Menu 1</a></li>
              <li><a href="#">Menu 2</a></li>
              <li><a href="#">Menu 3</a></li>
              <li><a href="#">Menu 4</a></li>
            </ul>
          </li>
          <li class="flex justify-between p-3 bg-blue-100 m-2">
            <a href="#">News</a>
          </li>
          <li class="flex justify-between p-3 bg-blue-100 m-2">
            <a href="#">Contact Us</a>
          </li>
        </ul>
      </nav>
    </aside>

    <main class="bg-blue-300 col-span-10">main</main>
  </div>
</template>

<style>
/* .menu-items {
  display: none;
} */
</style>

