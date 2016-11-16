# jekyll-timeline

This is a small group of html and css includes for Jekyll that lets you create a beautiful timeline. It doesn't have any dependencies or require any plugins so it works great with out-of-the box Jekyll on GitHub Pages. I've tested it on Jekyll `3.3.0` and I'm personally motivated to make sure it stays functional with the [version GitHub uses](https://pages.github.com/versions/).

## Use Cases

This wasn't built to stagger overlapping timeframes, so it works best for use cases that are naturally non-overlapping, such as:

* Places you and your family have lived
* Heads of state like presidents and other world leaders
* Vehicles you've owned
* Major technology releases by manufacturer
* Star Trek Seasons, Ships, and Captains
* Star Wars films

## Examples

Printable Resume Timeline ([live](http://simple.gy/resume/pretty)):

<a href="http://simple.gy/resume/pretty">
<img src="https://cloud.githubusercontent.com/assets/548809/20337440/62388d9c-ab8e-11e6-83ba-6d3526e2f969.png"/>
</a>


## Key Benefits

* No Jeykll plugins needed (this is why you can use it with GitHub Pages)
* No JavaScript at all, so it's easy to customize
* Prints almost pixel perfect (webkit only. Thanks to [`-webkit-print-color-adjust`](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-print-color-adjust))

## Limitations

* No JavaScript at all, so UI interactions are limited (but you can easily add the behaviors you want)
* Timeline is always vertical
* Timeline always has most recent at the top
* No overlapping times (you can, but they aren't visually handled. They just occlude one another)
* Works on a 1mo granulary, so if your timeline spans 100s of years the hash marks may get too dense, and if it only spans a year or so the hash marks are too sparse. 

## Similar Projects

* [timeline-jekyll-theme](https://github.com/kirbyt/timeline-jekyll-theme) is a whole site theme rather than a reusable component. Might be a good fit if you like the vertical bubble style and have sparse events.
