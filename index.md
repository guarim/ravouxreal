<html>
<!-- Déclaration du framework aframe pour décrire les objets 3D -->
<!-- Déclaration du framework AR.js pour mettre en place la réalité augmentée -->
	<script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
        <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
        <script src="https://raw.githack.com/donmccurdy/aframe-extras/master/dist/aframe-extras.loaders.min.js"></script>
        <script src="https://raw.githack.com/AR-js-org/studio-backend/master/src/modules/marker/tools/gesture-detector.js"></script>
        <script src="https://raw.githack.com/AR-js-org/studio-backend/master/src/modules/marker/tools/gesture-handler.js"></script>

<body style="margin : 0px; overflow: hidden;">
<h2>Mohamed Guarim PLP génie mécanique et automatisme</h2>
   <a-scene embedded arjs>
      <!-- Partie consacrée au contenu : le fichier de description du marqueur -->
  <a-marker type="pattern" url="https://raw.githubusercontent.com/guarim/rarv.github.io/main/marker.patt">
         <!-- marker -->
		<a-text position="-2 -2 -2.8" rotation="-90 0 0" height="2" width="2" color="blue" value="Mohamed Guarim PLP"></a-text>
	 	<a-image position="-2 0 -2" rotation="-90 0 0" height="1" width="3" src="https://raw.githubusercontent.com/guarim/rarv.github.io/main/logo-ravoux.png"></a-image>
	        <a-image position="1 0 -2" rotation="-90 0 0" height="2" width="3" src="https://raw.githubusercontent.com/guarim/rarv.github.io/main/ravoux.png"></a-image>
	        <a-image position="-2 0.5 -0.75" rotation="-90 0 0" height="1" width="3" src="https://raw.githubusercontent.com/guarim/rarv.github.io/main/rampe.png"></a-image>
      		<a-video rotation="-90 0 0" src="https://raw.githubusercontent.com/guarim/rarv.github.io/main/mise-en-service.mp4" width="1" height="1" position="0 1 0" autoplay loop="true"></a-video>
	  <!-- Partie consacrée au contenu : le fichier de description de l objet 3D -->
        
    </a-marker>
      <a-entity camera></a-entity>
   </a-scene>
</body>
</html>
© 2021 GitHub, Inc.
