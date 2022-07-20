<script setup>
import HeaderApp from '@/components/HeaderApp.vue'
import Prices from '@/components/AppPrices.vue';
import Services from '@/components/Services.vue';
import TitleWithSubtitle from '@/components/TitleWithSubtitle.vue';
import Title from '@/components/Title.vue';
import WanaDev from '@/components/wanaDev.vue';
import Synthesys from '@/components/AppSynthesys.vue';
import GameUbisoft from '@/components/GameUbisoft.vue';
import ArviVR from '@/components/ArviVR.vue';


</script>
<template>
  <div>
    <HeaderApp />
    <img
      src="/vrcafe.webp"
      class="text-center"
      alt="vr-headset"
      sizes="xs:100vw lg:100vw xl:100vw"
    >
  </div>
  <Prices />
  <Services />
  <TitleWithSubtitle
    id="escape"
    subtitle="UBISOFT"
    title="EXPERIENCE ESCAPE GAME VR"
  />
  <GameUbisoft />
  <Title
    title="ARVI VR"
    :exclu="true"
  />
  <ArviVR />
  <TitleWithSubtitle
    id="arcade"
    subtitle="WANADEV"
    title="EXPERIENCE ARCADE VR"
  />
  <WanaDev />
  <Title title="SYNTHESYS" />
  <Synthesys />
  <TitleWithSubtitle
    id="culture"
    subtitle="LUCID REALITY"
    title="EXPERIENCE CULTURE"
  />
</template>



