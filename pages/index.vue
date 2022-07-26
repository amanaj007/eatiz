<template>
  <div>
  <Cover/>
  <TopRes/>
  <AdvancedBookVue/>
  <Services/>
  <Explore/>
  <Download/>
  <GetNotified/>
  </div>
</template>

<script>
import Cover from '../components/Cover.vue';
import TopRes from '../components/TopRes.vue';
import AdvancedBookVue from '../components/AdvancedBook.vue';
import Services from '../components/Services.vue';
import Explore from '../components/Explore.vue';
import Download from '../components/Download.vue'
import GetNotified from '../components/GetNotified.vue';

export default {
    name: "IndexPage",
    components: { Cover, TopRes, AdvancedBookVue, Services, Explore, Download, GetNotified }
}
</script>

<style>
body{
  background-color: #fff5ec;
  margin: 0px;
}


</style>
