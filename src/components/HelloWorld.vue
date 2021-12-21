<template>
  <div class="flex max-h-screen">
    <div class="flex flex-col justify-between bg-gray-100 p-5">
      <div class="flex flex-col space-y-7">
        <a>
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
              d="M8 13v-1m4 1v-3m4 3V8M8 21l4-4 4 4M3 4h18M4 4h16v12a1 1 0 01-1 1H5a1 1 0 01-1-1V4z"
            />
          </svg>
        </a>
        <a>
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
              d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"
            />
          </svg>
        </a>
        <a>
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
              d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"
            />
          </svg>
        </a>
        <a>
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
              d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"
            />
          </svg>
        </a>
      </div>
      <div>
        <a>
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
              d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
            />
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
            />
          </svg>
        </a>
      </div>
    </div>
    <div class="flex flex-col w-3/12 p-5 space-y-10">
      <input
        class="
          appearance-none
          border
          rounded
          w-full
          py-2
          px-3
          text-gray-500
          leading-tight
          focus:outline-none
          focus:shadow-outline
        "
        type="text"
      />
      <div class="flex flex-row justify-between align-middle">
        <div class="text-xl">Integrations</div>
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
            d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"
          />
        </svg>
      </div>
      <div class="flex flex-col space-y-2 pr-5 flex-grow overflow-y-auto">
        <div class="bg-red-500 rounded p-5 text-gray-700">Integration 1</div>
        <div class="bg-green-500 rounded p-5 text-gray-700">Integration 2</div>
        <div class="bg-blue-500 rounded p-5 text-gray-700">Integration 3</div>
        <div class="bg-red-500 rounded p-5 text-gray-700">Integration 1</div>
        <div class="bg-green-500 rounded p-5 text-gray-700">Integration 2</div>
        <div class="bg-blue-500 rounded p-5 text-gray-700">Integration 3</div>
        <div class="bg-red-500 rounded p-5 text-gray-700">Integration 1</div>
        <div class="bg-green-500 rounded p-5 text-gray-700">Integration 2</div>
        <div class="bg-blue-500 rounded p-5 text-gray-700">Integration 3</div>
        <div class="bg-red-500 rounded p-5 text-gray-700">Integration 1</div>
        <div class="bg-green-500 rounded p-5 text-gray-700">Integration 2</div>
        <div class="bg-blue-500 rounded p-5 text-gray-700">Integration 3</div>
        <div class="bg-red-500 rounded p-5 text-gray-700">Integration 1</div>
        <div class="bg-green-500 rounded p-5 text-gray-700">Integration 2</div>
        <div class="bg-blue-500 rounded p-5 text-gray-700">Integration 3</div>
        <div class="bg-red-500 rounded p-5 text-gray-700">Integration 1</div>
        <div class="bg-green-500 rounded p-5 text-gray-700">Integration 2</div>
        <div class="bg-blue-500 rounded p-5 text-gray-700">Integration 3</div>
      </div>
    </div>
    <div class="w-9/12 p-5 bg-gray-100 shadow rounded-tl-xl">
      <div class="flex justify-between">
        <div class="flex-1 mb-5">
          <input
            class="
              outline-none
              p-2
              bg-gray-100
              border-b border-dashed border-gray-300
            "
            placeholder="Click to set title"
          />
        </div>
        <div class="flex space-x-5 mb-5">
          <a>
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
                d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z"
              />
            </svg>
          </a>
          <a>
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
                d="M17 17h2a2 2 0 002-2v-4a2 2 0 00-2-2H5a2 2 0 00-2 2v4a2 2 0 002 2h2m2 4h6a2 2 0 002-2v-4a2 2 0 00-2-2H9a2 2 0 00-2 2v4a2 2 0 002 2zm8-12V5a2 2 0 00-2-2H9a2 2 0 00-2 2v4h10z"
              />
            </svg>
          </a>
        </div>
      </div>
      <div class="grid grid-cols-3 gap-5">
        <div class="p-10 bg-white rounded shadow">chart</div>
        <div class="p-10 bg-white rounded shadow">chart</div>
        <div class="p-10 bg-white rounded shadow">chart</div>
        <div class="p-10 bg-white rounded shadow">chart</div>
        <div class="col-span-2 p-10 bg-white rounded shadow">chart</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>