<template>
  <div
    class="lg:w-[550px] flex flex-col gap-y-6 mx-auto py-24 px-4 md:px-20 lg:px-12 xl:px-0"
  >
    <!-- quote -->
    <div class="relative">
      <LeftQuoteIcon />
      <blockquote
        class="font-larkenLightItalic text-zinc-600 text-[15px] leading-8 text-justify"
      >
        Publiscing and disseminating information about arbitration has been one of ICC's
        commitments since its creation and an instrumental factor in facilitating the
        development of trade worldwide.
      </blockquote>
      <RightQuoteIcon />
    </div>
    <p class="font-ibm font-light text-sm text-center text-zinc-800">
      Note to the Parties and the Arbitral Tribunals <br />
      on the Conduct of Arbitration under the ICC Rules of Arbitration
    </p>
    <NuxtLink
      class="font-ibm font-light text-center text-xs underline underline-offset-4 tracking-widest"
      to="#"
      >READ THE WHOLE DOCUMENT</NuxtLink
    >
  </div>
</template>
