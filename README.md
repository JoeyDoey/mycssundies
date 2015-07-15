# myCSSundies

myCSSundies are a minimal collection of CSS classes and utilities that speed up prototyping and building-out of  responsive websites. 

Keep in mind that these are _my_ undies. You likely have a pair of your own (god, i hope you do!) but in case you don't&mdash;maybe it's laundry day&mdash;these will get you up and running in no time.


## What's in it?

```
undies/
├── _undies.scss
├── _boilerplate.scss
├── _brand.scss
├── _buttons.scss
├── _forms.scss
├── _grid.scss
├── _helper-classes.scss
├── _mixins.scss
├── _settings.scss
└── _typography.scss
```

## Assumptions

myCSSundies are a collection of prefix-free classes, mixins, helpers, etc so the assumption is that a post-css solution like [Autoprefixer](https://github.com/postcss/autoprefixer) is in use. 

There's the assumption that there's style-normalization (hopefully not total CSS reset) somewhere in the mix already.


## How to use

Grab the `undies` directory and drop it into whatever your pre-processed CSS directory is.
Then import the undies themselves before anything else, like so:

`@import 'undies/undies';`

Note: The main `_undies.scss` partial already imports everything else within the `undies` directory.

Next up, take a look at `undies/_settings.scss`. That's where site-wide variables, etc are defined. 
Here, you can define background color, text color, link colors, fonts (serif, sans, etc).


That's it!


## But why?
Speed and efficiency are virtues and inarguable pillars of good prototyping.

You want to prototype fast, fast, fast but also well! You want to quickly but also efficiently test if an idea works and polish the iterations that show promise. Fast and efficiently.

That does **NOT** need to end at prototyping. For love of good design, and all that is good, we should strive to make front-end dev resemble prototyping: fast and efficient.


## Thanks

Between the one end of the spectrum where we have full-featured front-end frameworks like [Bootstrap](http://getbootstrap.com/) and [Foundation](http://foundation.zurb.com/), there exists a hugely opinionated and vast wasteland before you get to (still opinionated, but agreeably minimal) boilerplate-approaches like [Skeleton](http://getskeleton.com).

I've happily yoinked and purloined aspects of each approach to arrive at myCSSundies.


## Acknowledgements

myCSSundies is a lil project by [Joe Nyaggah](http://nyaggah.com) 
