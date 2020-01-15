<template>
  <div class="container mx-auto border rounded-full">
    <div class="flex justify-between">
      <div class="inline-flex items-center ml-4">
        <svg
          class="fill-current w-4 h-4 mr-2"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
        >
          <path
            class="heroicon-ui"
            d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"
          />
        </svg>
        <input
          type="text"
          class="h-full focus:outline-none"
          placeholder="Search fonts"
        />
      </div>

      <button class="py-2 px-4">
        Prev
      </button>
      <button class="py-2 px-4">
        refresh
      </button>
    </div>
  </div>
</template>
