<style>
	.full-screen {
		position: absolute;
		top: 0;
		left: 0;
		bottom: 0;
		right: 0;
	} 
</style>
<!-- https://youtu.be/-d6q4yb57F8?si=-T-AjJ8Z9RC0z4s1 -->
<img class="full-screen" src="assets/video.png">

<img src="assets/dt-white.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />
<span style="position: absolute; bottom: 10px; right: 48px; opacity: .2;"><span v-if="$page < 10">0<SlideCurrentNo /></span><span v-else><SlideCurrentNo /></span> / <SlidesTotal /></span>
