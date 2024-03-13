# React Summit

Summit Amsterdam Highlights

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<img src="assets/dt-white.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />
<span style="position: absolute; bottom: 10px; right: 48px; opacity: .2;"><span v-if="$page < 10">0<SlideCurrentNo /></span><span v-else><SlideCurrentNo /></span> / <SlidesTotal /></span>
