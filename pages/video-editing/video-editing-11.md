
<h1>Video container</h1>
<div style="display: flex">
    <img src="assets/video-container.png" width=400/>
    <v-click>
        <div>
            <h4>Examples</h4>
            <li>.mp4 - MPEG-4</li>
            <li>.mov - QuickTime File Format</li>
            <li>.avi - Audio Video Interleave</li>
            <li>.mkv - Matroska</li>
        </div>
    </v-click> 
</div>

<img src="assets/dt-white.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />
<span style="position: absolute; bottom: 10px; right: 48px; opacity: .2;"><span v-if="$page < 10">0<SlideCurrentNo /></span><span v-else><SlideCurrentNo /></span> / <SlidesTotal /></span>
