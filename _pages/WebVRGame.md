---
layout: "page"
title: WebVR_Game
permalink: /VR_Game/
---


Web VR Game

<html>
  <head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
    <script src="https://unpkg.com/aframe-physics-system@1.4.0/dist/aframe-physics-system.min.js"></script>
  </head>
  <body>
    <a-scene physics>
      <a-box position="-1 4 -3" rotation="0 45 0" color="#4CC3D9" dynamic-body></a-box>
      <a-sphere position="0 4 -5" radius="1.25" color="#EF2D5E" dynamic-body></a-sphere>
      <a-cylinder position="1 4 -3" radius="0.5" height="1.5" color="#FFC65D" dynamic-body></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4" static-body></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
