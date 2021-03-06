# Scroll Box

> Lightweight solution for scrolling content on mobile device.

> Inspired by [ScrollFix](https://github.com/joelambert/ScrollFix).

ScrollFix's original documentation is below (probably not applicable to this project):

***

> ### ScrollFix
> 
> ScrollFix is a small script that *partially* works around the most common issue with using iOS5's `overflow: scroll` for fullscreen web apps.
> 
> The newly support `overflow:scroll` is a great addition and works well except under the following conditions:
> 
> - The scroll area is at the top and the user tries to scroll up
> - The scroll area is at the bottom and the user tries to scroll down.
> 
> In a native app, you'd expect the content to rubber band but in Safari the whole page is scrolled instead. Under occasions where you've deliberately hidden the browser chrome, this interaction can bring it back into view.
> 
> ScrollFix works around this by manually offsetting the `scrollTop` value to one away from the limit at either extreme, which causes the browser to use rubber banding rather than passing the event up the DOM tree.
> 
> ### How to use
> 
> Setup a scrollable section:
> 
> ```html
> <div class="scrollable" id="scrollable">
> 	<ul>
> 		<li>List Item</li>
> 		<li>List Item</li>
> 		<li>List Item</li>
> 		<li>List Item</li>
> 		<li>List Item</li>
> 		<li>List Item</li>
> 	</ul>
> </div>
> ```
> 
> Then call the following code on the area that has the `overflow: scroll` property:
> 
> ```js
> var scrollable = document.getElementById("scrollable");
> new ScrollFix(scrollable);
> ```

***

## License

[MIT License](http://www.opensource.org/licenses/mit-license.php)
