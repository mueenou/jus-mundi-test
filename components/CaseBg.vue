<template>
  <div
    v-motion
    :initial="{
      opacity: 0,
    }"
    :enter="{
      opacity: 1,
      transition: {
        duration: 300,
        delay: 1800,
      },
    }"
    class="md:absolute case_bg rounded-lg overflow-hidden w-[450px] h-[320px] top-[270px] left-[20px] bg-cover bg-center z-0"
  ></div>
</template>

<style scoped>
.case_bg {
  background-image: url("../public/images/case_bg.gif");
  box-shadow: inset 0px 0px 60px 60px rgb(250 250 250 / var(--tw-bg-opacity));
}
</style>
