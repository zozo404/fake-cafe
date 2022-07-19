<script setup>
import HeaderApp from './components/HeaderApp.vue'
import Prices from './components/Prices.vue';
import Services from './components/Services.vue';
import TitleWithSubtitle from './components/TitleWithSubtitle.vue';
import Title from './components/Title.vue';
import GameUbisoft from './components/gameUbisoft.vue';


</script>
<template>
<div>
  <HeaderApp />
  <img src="/vrcafe.webp" class="text-center" alt="vr-headset" sizes="xs:100vw lg:100vw xl:100vw"/>
  </div>
  <Prices />
  <Services />
  <TitleWithSubtitle
      id="escape"
      subtitle="UBISOFT"
      title="EXPERIENCE ESCAPE GAME VR"
    />
    <GameUbisoft />
    <Title title="ARVI VR" :exclu="true" />
    <TitleWithSubtitle
      id="arcade"
      subtitle="WANADEV"
      title="EXPERIENCE ARCADE VR"
    />
    <Title title="SYNTHESYS" />
    <TitleWithSubtitle
      id="culture"
      subtitle="LUCID REALITY"
      title="EXPERIENCE CULTURE"
    />
</template>



