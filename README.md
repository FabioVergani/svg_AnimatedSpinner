# svg_AnimatedSpinner



<svg xmlns="http://www.w3.org/2000/svg" width="64" height="64">
	<style type="text/css" >

	 @-webkit-keyframes spin{from{-webkit-transform:scale(1) rotate(0deg);}to{-webkit-transform:scale(1) rotate(360deg);}}
	 @-moz-keyframes spin{from{-moz-transform:scale(1) rotate(0deg);}to{-moz-transform:scale(1) rotate(360deg);}}
	 @keyframes spin{from{transform:scale(1) rotate(0deg);}to{transform:scale(1) rotate(360deg);}}

	 #spinner{
		-webkit-animation:spin 1s infinite linear;
		-moz-animation:spin 1s infinite linear;
		animation:spin 1s infinite linear;
		-webkit-transform-origin:50% 50%;
		-moz-transform-origin:50% 50%;
		transform-origin:50% 50%;
	 }

	</style>
	<g id="spinner">
		<path fill-opacity=".7" d="M59.6 36h-8c-2 0-3.8-1.8-3.8-4s1.7-4 4-4h7.8c2 0 4 1.8 4 4s-2 4-4 4z"/><path fill-opacity=".8" d="M48.7 21c-1.5 1.4-4 1.4-5.5 0s-1.6-4.2 0-5.7l5.5-5.6c1.5-1.5 4-1.5 5.6 0s1.4 4 0 5.6l-5.6 5.5z"/>
		<path d="M32 16.3c-2 0-4-1.8-4-4v-8c0-2 1.8-3.8 4-3.8s4 1.7 4 4v7.8c0 2.2-1.8 4-4 4z"/>
		<path fill-opacity=".2" d="M15.3 21l-5.6-5.7c-1.5-1.5-1.5-4 0-5.6s4-1.5 5.6 0l5.5 5.6c1.5 1.5 1.5 4 0 5.5s-4 1.6-5.5 0z"/>
		<path fill-opacity=".3" d="M16.3 32c0 2.2-1.8 4-4 4h-8c-2 0-3.8-1.8-3.8-4s1.7-4 4-4h7.8c2 0 4 1.8 4 4z"/>
		<path fill-opacity=".4" d="M15.3 54.3c-1.6 1.5-4 1.5-5.6 0-1.5-1.6-1.5-4 0-5.6l5.6-5.5c1.5-1.5 4-1.5 5.5 0s1.5 4 0 5.5l-5.5 5.6z"/>
		<path fill-opacity=".5" d="M32 63.5c-2 0-4-1.7-4-4v-7.8c0-2 1.8-4 4-4s4 1.8 4 4v8c0 2-2 3.8-4 3.8z"/>
		<path fill-opacity=".6" d="M48.7 43l5.5 5.7c1.6 1.5 1.6 4 0 5.5-1.5 1.5-4 1.5-5.5 0l-5.5-5.6c-1.6-1.5-1.6-4 0-5.5s4-1.4 5.5 0z"/>
	</g>
</svg>
