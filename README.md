AdLibber
========

A JQuery Plugin for setting randomized words or phrases on your site.

Sometimes it's fun to randomize adjectives on your site. Keep things fresh with either 'Cool', 'Awesome', 'Radical' appearing randomly for each page reload of your site.

The usage is simple. First wrap your word or words in a <span> or other inline element.

HTML:

```
<p>Check out my <span id="swap-me">Cool</span> site!</p>
```

JS:

```
$(document).ready( function () {
$('#your-inline-element').adLibber(['Awesome','Great','Stellar']);
}
```
The Alternates will swap in randomly each time the page loads!

This is a JS plugin, after all, so you probably won't want to use this for important content with SEO or usability considerations. Enjoy!