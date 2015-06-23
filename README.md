# grid
Barebones CSS/SCSS responsive grid system for your small projects.

## Features ##
* 12 columns and offsets
* Containers, rows, and clearfixes
* Floats!
* _weighs less than 2kb_

## SCSS Options ##
* Set amount of columns
* Gutter padding/margin
* Breakpoints

This 'grid' is a barebones grid system for your projects. It weighs less than 2kb and provides very basic column/grid/row support.
The main break is set at 768px, at which point, the grid falls back to single column rows.

**Columns** are defined like `col-4` and should always be wrapped in a `row`. 
**Containers** wrap content into smaller breakpoints based on viewport (good for centering content).

You can set column offsets like `off-3` where the number is the amount of columns you're moving over.

The standard padding (gutter) between columns is 15px. This gives each row -15px margin to the left and right side.

Here's an example:

```html
<section class="container">
	<div class="row">
		<div class="col-8 off-2">
			<h1>grid</h1>
			<p>Barebones CSS/SCSS responsive grid system for your small projects.</p>
		</div>
	</div>
</section>
```

## Directions ##
Add minified version to the top of your css file or include the partial _grid.scss in your scss files.

#### Notes ####
Feel free to add/contribute. It's something I've used locally and created for small projects.