---
layout: post
title: Simulación del Sistema Solar
excerpt_separator: <!--more-->
ref: solar-system
lang: es
---

Simulación del Sistema Solar

<!--more-->

<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | Solar System Simulation</title>
    <link rel="shortcut icon" href="../assets/webgl/solar-system/TemplateData/favicon.ico">
    <link rel="stylesheet" href="../assets/webgl/solar-system/TemplateData/style.css">
    <script src="../assets/webgl/solar-system/TemplateData/UnityProgress.js"></script>  
    <script src="../assets/webgl/solar-system/Build/UnityLoader.js"></script>
    <script>
      var gameInstance = UnityLoader.instantiate("gameContainer", "../assets/webgl/solar-system/Build/WebGL.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
    <div class="webgl-content">
      <div id="gameContainer" style="width: 960px; height: 600px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
        <div class="title">Solar System Simulation</div>
      </div>
    </div>
  </body>
</html>
