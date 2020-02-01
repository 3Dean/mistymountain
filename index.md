<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Misty Mountain Valley</title>
    <meta name="description" content="Misty Mountain Valley">
    <script src="https://aframe.io/releases/0.7.0/aframe.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/donmccurdy/aframe-extras@v6.1.0/dist/aframe-extras.min.js"></script>
      <script src="https://cdn.rawgit.com/zcanter/aframe-gradient-sky/master/dist/gradientsky.min.js"></script>
    <script src="https://unpkg.com/aframe-animation-component@^4.1.2/dist/aframe-animation-component.min.js"></script> 
  </head>
  <body>
    <iframe width="10" height="0" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/218070884&auto_play=true"></iframe>
    <a-scene fog="type: linear; color: #ffc974; far: 55; near: 0">
<a-assets>
  </a-assets>
        <a-camera position="0 85 0" rotation="-25 0 0"></a-camera>
      <!--<a-sky color="#a3d0ed"></a-sky>-->
          <a-gradient-sky material="shader: gradient; topColor: 249 154 54; bottomColor: 255 201 116;"></a-gradient-sky>
      <a-entity light="type: hemisphere; color: #f99f36; groundColor: #ad42cc; intensity: 1"></a-entity>
      <!--<a-light type="directional" position="0 0 0" rotation="-90 0 0">-->
      <a-entity gltf-model="https://aws-website-studiob-x-dqxqd.s3.amazonaws.com/assets/canyon/assets/canyon08.glb" position="0 0 0" scale="60 60 60" animation="property: rotation; to: 360 0 0; loop: true; dur: 460000; loop: true; easing: linear"></a-entity>
      <a-entity gltf-model="https://aws-website-studiob-x-dqxqd.s3.amazonaws.com/assets/canyon/assets/hawkanimate2.glb" animation-mixer="" position="0 86 -8" scale="0.25 0.25 0.25"></a-entity>
    </a-scene>
  </body>
</html>
