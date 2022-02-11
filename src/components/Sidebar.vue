<template>
  <div class="w-20 text-gray-400 bg-gray-900 xl:w-72">
    <div class="relative flex items-center px-4 py-6">
      <div class="p-3 bg-white rounded-xl">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 text-gray-900"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 8V4m0 0h4M4 4l5 5m11-1V4m0 0h-4m4 0l-5 5M4 16v4m0 0h4m-4 0l5-5m11 5l-5-5m5 5v-4m0 4h-4"
          />
        </svg>
      </div>
      <button
        class="absolute p-1 bg-gray-800 rounded-full xl:-right-3 -right-8"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-5 h-5 xl:rotate-180"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
            clip-rule="evenodd"
          />
        </svg>
      </button>
    </div>

    <div class="px-4 py-4">
      <ul class="space-y-1">
        <li>
          <a
            href="#"
            class="flex items-center p-3 space-x-3 text-white bg-gray-800 rounded-xl"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-6 h-6"
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
            <span class="hidden text-base font-medium xl:block">Dashboard</span>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center justify-between p-3 hover:bg-gray-800 hover:text-white rounded-xl"
          >
            <div class="flex items-center space-x-3">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <span class="hidden text-base font-medium xl:block"
                >Audience</span
              >
            </div>
            <div class="items-center hidden space-x-2 xl:flex">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-5 h-5"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center justify-between p-3 hover:bg-gray-800 hover:text-white rounded-xl"
          >
            <div class="flex items-center space-x-3">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
                />
              </svg>
              <span class="hidden text-base font-medium xl:block">Posts</span>
            </div>
            <div class="items-center hidden space-x-2 xl:flex">
              <button
                type="button"
                class="px-2 font-bold text-gray-900 bg-green-200 rounded-md"
              >
                8
              </button>
            </div>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center justify-between p-3 hover:bg-gray-800 hover:text-white rounded-xl"
          >
            <div class="flex items-center space-x-3">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                />
              </svg>
              <span class="hidden text-base font-medium xl:block"
                >Schedules</span
              >
            </div>
            <div class="items-center hidden space-x-2 xl:flex">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <button
                type="button"
                class="px-2 font-bold text-gray-900 bg-red-200 rounded-md"
              >
                3
              </button>
            </div>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="relative flex items-center justify-between p-3 text-white bg-gray-800 rounded-xl"
          >
            <div class="flex items-center space-x-3">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
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
                />
              </svg>
              <span class="hidden text-base font-medium xl:block">Income</span>
            </div>
            <div class="items-center hidden space-x-2 xl:flex">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-5 h-5"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M14.707 12.707a1 1 0 01-1.414 0L10 9.414l-3.293 3.293a1 1 0 01-1.414-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 010 1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
          </a>
          <div
            class="absolute mt-1 bg-gray-800 border-2 border-gray-700 xl:pl-4 rounded-xl xl:ml-5 xl:border-gray-700 xl:border-l-2 xl:relative xl:bg-gray-900 xl:border-0 xl:rounded-none"
          >
            <ul class="w-48 space-y-1 xl:w-full">
              <li>
                <a
                  href="#"
                  class="flex items-center justify-between p-3 group hover:text-white hover:bg-gray-800 rounded-xl"
                  ><span>Earnings</span
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="w-5 h-5 text-gray-800 xl:text-gray-900 group-hover:text-white"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                      clip-rule="evenodd"
                    /></svg
                ></a>
              </li>
              <li>
                <a
                  href="#"
                  class="flex items-center justify-between p-3 text-white bg-gray-800 rounded-xl"
                  ><span>Refunds</span
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="w-5 h-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                      clip-rule="evenodd"
                    /></svg
                ></a>
              </li>
              <li>
                <a
                  href="#"
                  class="flex items-center justify-between p-3 hover:text-white group hover:bg-gray-800 rounded-xl"
                  ><span>Declines</span
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="w-5 h-5 text-gray-900 group-hover:text-white"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                      clip-rule="evenodd"
                    /></svg
                ></a>
              </li>
              <li>
                <a
                  href="#"
                  class="flex items-center justify-between p-3 hover:text-white group hover:bg-gray-800 rounded-xl"
                  ><span>payouts</span
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="w-5 h-5 text-gray-900 group-hover:text-white"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                      clip-rule="evenodd"
                    /></svg
                ></a>
              </li>
            </ul>
          </div>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center justify-between p-3 hover:bg-gray-800 hover:text-white rounded-xl"
          >
            <div class="flex items-center space-x-3">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
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
              <span class="hidden text-base font-medium xl:block">Promote</span>
            </div>
            <div class="items-center hidden space-x-2 xl:flex">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-5 h-5"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>
