HTML-Only Share Buttons
=======================

This is a derived work based on the original idea of [Gregory Schier](http://schier.co).

The point of this project is to come from this:

![before](assets/images/before.jpg)

(do you see any links like Twitter, Facebook?)

to this:

![after](assets/images/after.jpg)

What is missing in Gregory's otherwise excellent work is text context for links. They have no text labels, titles or alts. So if for some reason FontAwesome fails to load, or you are using screen reader or other assistive technology - you will see nothing (maybe a color will be a visual clue if you know [Brand Colors](http://brandcolors.net/)). And the stylesheets removed `outline` property from links - in example - while the outline is on original blog post.

See: [ https://github.com/gschier/html-share-buttons/issues/1](https://github.com/gschier/html-share-buttons/issues/1)

In addition the @reimertz `brand-colors` will be used via Bower to minimize custom CSS and use existing solutions via OSS.


Using @browser-sync?

```bash
browser-sync start --server --files "buttons.html" --startPath "./buttons.html"
```

@peterblazejewicz  
[Peter Blazejewicz](@peterblazejewicz)

---

Here are some social buttons that don't require any Javascript. Just HTML, CSS, and some Font Awesome icons.

[Blog post and tutorial](http://schier.co/blog/2014/10/22/pure-html-share-buttons.html)

![Social Sharing Buttons](http://schier.co/images/sharing.png?foo=bar)

### Contributors

 * Author: [Gregory Schier](http://schier.co)
