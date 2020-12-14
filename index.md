### Gallery Here & Artist's Name/Work <!-- Loads <model-viewer> for old browsers like IE11: -->
  <script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js">
  </script>

  <!-- The following libraries and polyfills are recommended to maximize browser support -->  
  <!-- REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
  <script src="https://unpkg.com/@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>

  <!-- OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
  <script src="https://unpkg.com/intersection-observer/intersection-observer.js"></script>

  <!-- OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
  <script src="https://unpkg.com/resize-observer-polyfill/dist/ResizeObserver.js"></script>

  <!-- OPTIONAL: Fullscreen polyfill is required for experimental AR features in Canary -->
  <!--<script src="https://unpkg.com/fullscreen-polyfill/dist/fullscreen.polyfill.js"></script>-->

  <!-- OPTIONAL: Include prismatic.js for Magic Leap support -->
  <!--<script src="https://unpkg.com/@magicleap/prismatic/prismatic.min.js"></script>-->

<model-viewer loading="eager" id="paused-change-demo" camera-controls autoplay animation-name="Tail_whip" ar shadow-intensity="1" src="Models/scene.gltf" ar="" ar-modes="scene-viewer webxr quick-look" ios-src="Positivasaurus.usdz" alt="Art Demo" auto-rotate="" auto-rotate-delay="0" ar-scale="auto" style="width: 95%; height: 500px" exposure="0.5">  <button slot="ar-button" style="background-color: white; border-radius: 8px; border: 1 px solid black; position: absolute; top: 20px; right: 20px; ">
      👋 AR Click Here
  </button>
</model-viewer>
<script>
(() => {
  const modelViewer = document.querySelector('#paused-change-demo');

  self.setInterval(() => {
    modelViewer.animationName = modelViewer.animationName === 'Tail_whip' ?
      'Roar': 'Tail_whip';
  }, 1000.0);
})();
</script>
<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>

---

### <a href="https://avertek.net">Learn More About AVERtek's XR-NOW</a> 
  <br><br>
