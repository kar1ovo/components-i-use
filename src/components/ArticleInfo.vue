<template>
  <div
    class="max-w-sm mx-auto my-8 p-8 space-y-4 font-sans bg-gray-100 rounded-2xl sm:max-w-4xl shadow-2xl"
  >
    <div>
      <p class="text-3xl font-bold">{{ title }}</p>
    </div>
    <div class="grid grid-cols-12 gap-x-2 opacity-50">
      <svg
        class="col-start-1 col-span-1 h-6"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"
        />
      </svg>
      <button
        class="bg-blue-500 text-white rounded-md px-2 text-sm col-start-2 col-span-4 h-6"
      >
        {{ createTime }}
      </button>
      <svg
        class="col-start-6 col-span-1 h-6"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M7 7h.01M7 3h5c.512 0 1.024.195 1.414.586l7 7a2 2 0 010 2.828l-7 7a2 2 0 01-2.828 0l-7-7A1.994 1.994 0 013 12V7a4 4 0 014-4z"
        />
      </svg>
      <button
        class="bg-blue-500 text-white rounded-md px-2 text-sm col-start-7 col-span-2 h-6"
      >
        个人
      </button>
      <button
        class="bg-blue-500 text-white rounded-md px-2 text-sm col-start-9 col-span-2 h-6"
      >
        经验
      </button>
    </div>
    <div>
      <p class="font-light leading-7">
        {{ summary }}
      </p>
    </div>
    <div class="grid grid-cols-12 h-6">
      <svg
        class="col-start-1 col-span-1 h-8"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
        />
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"
        />
      </svg>
      <div class="col-start-3 col-span-1 h-8 text-2xl">{{ eyes }}</div>
      <button
        class="bg-blue-500 text-white rounded-lg px-2 text-base shadow-2xl col-start-9 col-span-4 h-8 focus:outline-none"
      >
        阅读原文
      </button>
    </div>
  </div>
</template>

<script>
export default {
  props: ["title", "summary", "eyes", "createTime", "tags"],
  data() {
    return {};
  },
};
</script>

<style scoped>
span {
  display: inline-block;
}
</style>
