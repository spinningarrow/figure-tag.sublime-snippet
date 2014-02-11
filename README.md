# Figure Tag (Sublime Snippet)

A snippet for Sublime Text that inserts the HTML `<figure>` tag. I use this to insert images on [my blog][blog] since GitHub Pages doesn't allow Jekyll plugins.

The snippet generates the following code:

    <figure>
		<a rel="lightbox" href="">
			<img src="" alt="">
		</a>
		<figcaption></figcaption>
	</figure>
	
It can be invoked by entering `fig` followed by the `TAB` key.
	
Since the `href` for the anchor tag and the image source are usually the same, both are updated at the same time. Pressing `TAB` successively moves the cursor to the `alt` attribute followed by the `<figcaption>`.

[blog]: https://github.com/spinningarrow/spinningarrow.github.io