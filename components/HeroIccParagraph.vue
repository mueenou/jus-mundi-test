<template>
  <p
    v-motion
    :initial="{
      opacity: 0,
    }"
    :enter="{
      opacity: 1,
      transition: {
        duration: 300,
        delay: 1000,
      },
    }"
    class="font-ibm text-md font-light leading-7 text-zinc-800 tracking-wide mb-10"
  >
    The International Chamber of Commerce (ICC) & Jus Mundi have joined forces to make ICC
    Arbitration Awards and related materials freely available to the global legal
    community.
  </p>
</template>
