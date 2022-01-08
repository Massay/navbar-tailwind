<template>
  <div class="container mx-auto">
    <div
      class="
        h-screen
        grid
        lg:grid-cols-2
        grid-cols-1
        lg:gap-24 lg:grid-flow-col-dense lg:px-8 px-4 lg:max-w-7xl
      "
    >
      <div class="p-4 flex flex-col justify-center items-start">
        <h2 class="font-extrabold text-xl">
          Best-in-Class Support for Monorepos
        </h2>
        <p class="p-2">
          Nx builds a project graph by analyzing your workspace, which it then
          uses to only rebuild what is necessary and to never run the same
          computation twice. Nx also helps establish structured code sharing and
          ownership management to keep the workspace maintainable.
        </p>
      </div>
      <div
        class="
          grid grid-cols-1
          lg:grid-cols-2
          items-center
          px-4
          py-14
          h-full
          m-0
          gap-2
          relative
          text-sm
        "
      >
        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            lg:self-center lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-orange-600
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Editor plugins</h4>
            <p>nx-aware autocompletion and refactoring</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-sky-400
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Github & CI</h4>
            <p>Searchable and filterable CO outputs, anlytics, and more</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
            lg:-left-12
          "
        >
          <div
            class="
              mr-3
              bg-blue-500
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Distributed rask execution</h4>
            <p>
              Nx provides a modern integrated dev experience. It has a
              high-quality VS Code plugin, interactive visualizations, GitHub
              integration and more.
            </p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            lg:-left-8
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-yellow-500
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Computation caching</h4>
            <p>Nx never rebuilds or tests the same code twice</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-violet-900
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Easy Code sharing</h4>
            <p>Nx simplifies extracing and refactoring shared libraries</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-red-900
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Nx Devkit</h4>
            <p>
              Nx enables a custmo dev experience to match the needs of your
              organizatino
            </p>
          </div>
        </div>
      </div>

      <div class="p-4 flex flex-col justify-center items-start">
        <h2 class="text-2xl font-extrabold p-2">
          Integrated Development Experience
        </h2>
        <p class="p-2">
          Nx provides a modern integrated dev experience. It has a high-quality
          VS Code plugin, interactive visualizations, GitHub integration and
          more.
        </p>
      </div>

      <div
        class="
          grid grid-cols-1
          lg:grid-cols-2
          items-center
          px-4
          py-14
          h-full
          m-0
          gap-2
          relative
          lg:col-start-1 lg:col-end-2 lg:row-start-2 lg:row-end-3
          text-sm
        "
      >
        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-orange-600
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Editor plugins</h4>
            <p>nx-aware autocompletion and refactoring</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-sky-400
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Github & CI</h4>
            <p>Searchable and filterable CO outputs, anlytics, and more</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
            lg:-left-12
          "
        >
          <div
            class="
              mr-3
              bg-blue-500
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Distributed rask execution</h4>
            <p>
              Nx provides a modern integrated dev experience. It has a
              high-quality VS Code plugin, interactive visualizations, GitHub
              integration and more.
            </p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            lg:-left-8
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-yellow-500
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Computation caching</h4>
            <p>Nx never rebuilds or tests the same code twice</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-violet-900
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Easy Code sharing</h4>
            <p>Nx simplifies extracing and refactoring shared libraries</p>
          </div>
        </div>

        <div
          class="
            border
            shadow-md
            py-3
            px-4
            rounded-md
            space-x-4
            transition
            relative
            self-center
            lg:justify-self-start
            flex
            items-center
          "
        >
          <div
            class="
              mr-3
              bg-red-900
              w-8
              h-8
              lg:rounded-full
              p-1
              rounded-md
              flex
              justify-center
              items-center
            "
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              />
            </svg>
          </div>
          <div>
            <h4 class="font-extrabold text-sm">Nx Devkit</h4>
            <p>
              Nx enables a custmo dev experience to match the needs of your
              organizatino
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>