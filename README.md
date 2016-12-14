# SVG
SVG stands for scalar vector graphics and can draw shapes using it.

SVG Elements:
	svg

	circle

	rect

	ellipse

	line

	polyline

	polygone

	path
		The SVG <path> element is used to draw advanced shapes combined from lines, arcs, curves etc.

		Path commands:
			M - moveto
			L - lineto
			H - horizantal lineto
			V - vertical lineto
			C - curveto
			S - smooth curveto
			Q - quadratic Bezier curve
			T - smooth quadratic Bezier curve
			A - elliptical Arc
			Z - closepath
			



	marker

	text

	tspan

	tref

	textpath

	switch

	image

	a

	defs

	symbol

	use

SVG styles:
	Using style attribute you can apply css to svg shapes.
	Some of the most used css properties in SVG
	
	fill 		   - It sets the color of the shape

	fill-opacity   - Sets fill opacity of the shape

	fill-rule	   - Sets fill rule of the shape

	stroke		   - Sets the stroke(line) color used to draw the outline 
	                 	of the shape
	stroke-width   - Sets the stroke(line) width used to draw the outline 
						of the shape

	stroke-opacity - Sets the stroke opacity used draw the outline of the 
						shape

Examples:
	<svg>
		<circle cx="20" cy="20"></circle>	
	</svg>


Resources:
	https://css-tricks.com/svg-path-syntax-illustrated-guide/

	http://tutorials.jenkov.com/svg/path-element.html

	https://developer.mozilla.org/en/docs/Web/SVG/Tutorial/Paths

	https://www.sitepoint.com/closer-look-svg-path-data/

	https://www.dashingd3js.com/svg-paths-and-d3js

