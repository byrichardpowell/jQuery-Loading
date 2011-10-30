#jQuery Loading

jQuery loading is a plugin that allows you toggle a loading state on any element. Its useful for AJAX heavy sites where you wish to prevent interaction whilst an AJAX request is in progress.

##Features
You can pass in a class and loading text. The class will be added to the loading div (along side a default class) and the text will be positioned next to the loading span.

##How do I style it?
Edit the css, or style a new class. The plugin creates the following markup with any class you pass in added to the loading div:


`<div class="loading">
	<span class="icon"></span>
	loading message goes here
</div>`


[Heres the demo page](http://byrichardpowell.github.com/jQuery-Loading/)