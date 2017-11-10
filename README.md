# svg_AnimatedSpinner

https://codepen.io/fabiovergani/pen/wPJzQg

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="100" height="100">
	<style>
		@keyframes i{to{transform:rotate(359deg)}}
		*{transform-origin:50px 50px;}
		line{fill:none;stroke:#000;stroke-width:6;stroke-linecap:round}
		#g{stroke-opacity:.2}
	</style>
	<defs>
		<line id="l" x1="50" x2="50" y1="20" y2="5"/>
		<g id="g">
			<use xlink:href="#l"/>
			<use xlink:href="#l" transform="rotate(90 0 0)"/>
			<use xlink:href="#l" transform="rotate(180 0 0)"/>
			<use xlink:href="#l" transform="rotate(270 0 0)"/>
		</g>
	</defs>
	<use xlink:href="#g"/>
	<use xlink:href="#g" transform="rotate(22.5 0 0)"/>
	<use xlink:href="#g" transform="rotate(45 0 0)"/>
	<use xlink:href="#g" transform="rotate(67.5 0 0)"/>
	<g style="animation:i 1.2s steps(16) infinite">
		<use xlink:href="#l" stroke-opacity=".4"/>
		<use xlink:href="#l" stroke-opacity=".2" transform="rotate(-22.5 0 0)"/>
		<use xlink:href="#l" stroke-opacity=".1" transform="rotate(-45 0 0)"/>
	</g>
</svg>


