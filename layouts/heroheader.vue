<template>
  <div
    class="flex flex-col lg:grid w-screen lg:grid-cols-2 px-16 md:px-32 xl:px-72 gap-x-20 py-20 bg-zinc-50 relative overflow-hidden"
  >
    <!-- green artifacts -->
    <HeroTopLeftArtifact />
    <HeroBotLeftArtifact />
    <HeroBotRightArtifact />
    <!-- call to action button try jus mundi -->
    <JmCtaButton />
    <!-- left side content -->
    <div class="hidden lg:block relative">
      <IccLogo />
      <JmLogo />
      <CaseBg />
    </div>
    <!-- right side content -->
    <div class="flex flex-col md:gap-y-10 justify-between mt-10 z-10">
      <HeroHeaderTitle />
      <HeroIccParagraph />
      <AccessIccButton />
    </div>
  </div>
  <slot />
</template>
