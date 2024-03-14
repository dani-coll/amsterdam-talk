<style>
	.presenters {
		display: flex;
	}
    .half {
        display: flex;
        flex-direction: column;
        width: 50%;
        align-items: center;
        justify-content: center;
        margin-top: 33px;
    }
	.dani {
		background-size: cover;
		background-image: url("/assets/dani.jpg");
		background-position-x: -60px;
	}
</style>

<section class="presenters">
	<div class="half">
	    <img src="assets/valen.jpeg" height=200 width=200 alt="Valen">
	    <h1>Valentin Gutierrez</h1>
	    <h4 style="margin-top: 22px;">Software Engineer & Product Owner</h4>
	    <h3>@ Dynatrace </h3>
	</div>
	<img src="assets/dt-white.png" width=100 alt="logo Dynatrace" style="position: absolute; top: calc(50% - 111px); left: calc(50% - 50px);">
	<div class="half">
	    <img class="dani" height=200 width="200">
	    <h1>Dani Coll</h1>
	    <h4 style="margin-top: 22px;">Senior Software Engineer</h4>
	    <h3>@ Dynatrace </h3>
	</div>
</section>

<img src="assets/dt-white.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />
<span style="position: absolute; bottom: 10px; right: 48px; opacity: .2;"><span v-if="$page < 10">0<SlideCurrentNo /></span><span v-else><SlideCurrentNo /></span> / <SlidesTotal /></span>

<!-- Disclaimer: We are not experts on all the topics -->
