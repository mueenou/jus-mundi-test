<template>
  <button
    v-motion
    :initial="{
      opacity: 0,
    }"
    :enter="{
      opacity: 1,
      transition: {
        duration: 300,
        delay: 2600,
      },
    }"
    class="flex flex-row gap-x-2 items-center font-lato font-bold rounded-[4px] bg-[#019EFD] text-white self-start py-5 px-8 text-xs tracking-widest shadow-xl"
  >
    <span>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="20"
        viewBox="0 0 24 24"
        style="fill: rgba(255, 255, 255, 1); transform: ; msfilter: "
      >
        <path
          d="M10.707 17.707 16.414 12l-5.707-5.707-1.414 1.414L13.586 12l-4.293 4.293z"
        ></path></svg
    ></span>
    ACCESS ICC AWARDS
  </button>
</template>
