<template>
  <h1
    v-motion
    :initial="{
      opacity: 0,
      y: 20,
    }"
    :enter="{
      y: 0,
      opacity: 1,
      transition: {
        duration: 1300,
        delay: 1000,
        ease: 'easeOut',
      },
    }"
    class="font-larkenExtraBold text-5xl leading-[65px] text-zinc-800"
  >
    A Unique Partnership for the Publication of ICC Arbitration <br />
    Awards
  </h1>
</template>
