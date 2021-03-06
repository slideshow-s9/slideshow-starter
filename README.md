# Slide Show (S9) Quick Starter Kit

Write your own talks in plain text with Markdown formatting conventions.


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

resulting in:

```
Installed plugins in search path
    [1] plugins/*.{txt.plugin,plugin.txt}
    [2] plugins/*/*.{txt.plugin,plugin.txt}
    [3] ~/.slideshow/plugins/*.{txt.plugin,plugin.txt}
    [4] ~/.slideshow/plugins/*/*.{txt.plugin,plugin.txt}
  include:
       analytics (~/.slideshow/plugins/analytics/analytics.txt.plugin)
        snippets (~/.slideshow/plugins/snippets/snippets.txt.plugin)
          tables (~/.slideshow/plugins/tables/tables.txt.plugin)

Installed template packs in search path
    [1] templates/*.txt
    [2] templates/*/*.txt
    [3] node_modules/*/*.txt
    [4] ~/.slideshow/templates/*.txt
    [5] ~/.slideshow/templates/*/*.txt
  include:
         s6blank (~/.slideshow/templates/s6blank/s6blank.txt)
```


## Build Instructions

Use the Slide Show (S9) command line tool to build
a web page (e.g. `sample1.html` or `sample2.html`)
that is an all-in-one-page handout and a live slide show all at once.

```
$ slideshow build sample1.text

=> Preparing slideshow 'sample1.html'...
=> Done.
```

And one more time.

```
$ slideshow build sample2.text

=> Preparing slideshow 'sample2.html'...
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
