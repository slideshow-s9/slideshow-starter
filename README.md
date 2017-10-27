# Slide Show Quick Starter Kit

Write your own talks in plain text (with Markdown).

## What's included?

- A first sample talk (see [`sample1.text`](sample1.text)) 
- A second sample talk (see [`sample2.text`](sample2.text)) incl. some macros/helpers e.g. `left`, `right`, `step`, etc.


## Step 0: Setup Templates Packs & Plugins 

Use the Slide Show (S9) command line tool to download (fetch) the template pack and plugin helpers:

```
$ slideshow install s6blank        # fetch s6 blank template pack
$ slideshow install plugins        # fetch (standard) plugin helpers
```

To double check what template packs and plugins you have installed try:

```
$ slideshow list
```


## Build Instructions

Use the Slide Show (S9) command line tool to build
a web page (e.g. `sample1.html` or `sample2.html`)
that is an all-in-one-page handout and a live slide show all at once.

```
$ slideshow build sample1.text -t s6blank

=> Preparing slideshow 'sample1.html'...
=> Done.
```

That's it. Open up your slide show `sample1.html` or `sample2.html` in your browser
(Firefox, Chrome, Opera, Safari, Edge and others) and hit F11 to switch into full screen projection
and hit the space bar or the right arrow, down arrow or page down key to flip through your slides.



## License

The slide show quick starter kit is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [wwwmake mailing list/forum](http://groups.google.com/group/wwwmake). Thanks.


