# CSS only Image Slider

I really like all those demos where people create something on CSS that was not even imaginable. And now, because I was learning some selectors, I decided to create an Image slider (where images fade but don't slide) using css animations and some crazy selectors.

If you want, you can use it on your page because it's very simple to implement, but be aware that it only supports Firefox and Chrome (for now).

For a more detailed explanation, read my [blogpost](http://campinhos.posterous.com/css-only-image-slider).

## Instructions

Import the css file **is.css**. This is the only file you will need. Open this file and edit line *17* to the correct image height.
Then, on your html file, add this structure:

	<div class="slideshow">
		<div class="slider">
			<img id="ID" src="..." />
		</div>
		<div class="navigation">
			<a href="#SAME AS IMAGE ID"></a>
		</div>
	</div>
	
And... It's done.

## To-do

+ IE + Opera support
+ Buttons with active state
+ More animations 
+ More types of navigation
