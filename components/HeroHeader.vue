<template>
  <div
    class="flex flex-col md:grid w-screen md:grid-cols-2 md:px-32 gap-x-20 py-20 bg-zinc-50 relative overflow-hidden"
  >
    <!-- green artifacts -->
    <HeroTopLeftArtifact />
    <HeroBotLeftArtifact />
    <HeroBotRightArtifact />
    <!-- call to action button try jus mundi -->
    <JmCtaButton />
    <!-- left side content -->
    <div class="hidden md:block relative">
      <IccLogo />
      <JmLogo />
      <CaseBg />
    </div>
    <!-- right side content -->
    <div class="flex flex-col gap-10 justify-between mt-10 z-10">
      <HeroHeaderTitle />
      <HeroIccParagraph />
      <AccessIccButton />
    </div>
  </div>
</template>
