---
layout: post
title:  "futurevisions: My first R package!"
date:   2020-02-11 11:53:00 -0400
tags: [Data Viz, Github, R, Side Projects]
---

Today I released my first complete, functional, R package! It's called futurevisions and it's available on [my github](https://github.com/JoeyStanley/futurevisions). It's just a little one that contains about 20 different color palettes. I've had the idea to work on it for a few months and this week, I decided to go ahead and do it! The rest of this post is the README file for that package and explains the posters the palettes were based on, installation, usage, the list of palettes, and some background.

## Introduction

The color palettes are based on NASA's [Visions of the Future](https://www.jpl.nasa.gov/visions-of-the-future/) poster series, which were produced through NASA's Jet Propulsion Laboratory through the California Institute of Technology. They are retro-future-style posters depecting humans visiting other planets, moons, and exo-planets. In their words, 

> Imagination is our window into the future. At NASA/JPL we strive to be bold in advancing the edge of possibility so that someday, with the help of new generations of innovators and explorers, these visions of the future can become a reality. As you look through these images of imaginative travel destinations, remember that you can be an architect of the future.

The posters are available for download for free. You can get them as PDFs or as 20x30 inch TIFF files. 

## Demo

You can install the package through [my github](https://github.com/JoeyStanley/futurevisions). The library imports `ggplot2`, so if there are problems, make sure you have `ggplot2` installed already. (I'm not good at testing things so if there is trouble, let me know.)

``` r
devtools::install_github("JoeyStanley/futurevisions")
```

You can then load it like a normal R package.

``` r
library(futurevisions)
```

The main two functions are `futurevisions`, which returns a list of colors, and `show_palette`, which produces a simple image using `ggplot2` to highlight the colors. For example, here is the palette called `mars`.

``` r
show_palette("mars")
```

<img width = "85%" src="/images/plots/futurevisions/mars.png">

``` r
futurevisions("mars")
```

    ## [1] "#DB3A2F" "#EAB33A" "#275D8E" "#902A57" "#F7EBD3" "#0B0C0B"

This can be easily used within `ggplot2` using `scale_color_manual`:

``` r
ggplot(mpg, aes(cty, hwy, color = factor(cyl))) +
  geom_jitter() +
  scale_color_manual(values = futurevisions("mars"))
```

<img width = "85%" src="/images/plots/futurevisions/sample_plot.png">

### Note on color selection

This is not a rigorous samping of colors. I picked a few colors from each poster that I felt were represtentative. They may not necessarily be colorblind-friendly. When using these palettes in data visualization, take care to ensure that your data is not misrepresented.

## List of palettes

### Gradient

These are palettes that may lend themselves better to more gradient purposes.

``` r
show_palette("ceres")
```

<img width = "85%" src="/images/plots/futurevisions/ceres.png">

``` r
show_palette("europa")
```

<img width = "85%" src="/images/plots/futurevisions/europa.png">

``` r
show_palette("titan")
```

<img width = "85%" src="/images/plots/futurevisions/titan.png">

``` r
show_palette("cancri")
```

<img width = "85%" src="/images/plots/futurevisions/cancri.png">

``` r
show_palette("pso")
```

<img width = "85%" src="/images/plots/futurevisions/pso.png">

### Diverging

These are palettes that may lend themselves more to highlighting deviations from a center point.

``` r
show_palette("earth")
```

<img width = "85%" src="/images/plots/futurevisions/earth.png">

``` r
show_palette("enceladus")
```

<img width = "85%" src="/images/plots/futurevisions/enceladus.png">

``` r
show_palette("kepler186")
```

<img width = "85%" src="/images/plots/futurevisions/kepler186.png">

``` r
show_palette("atomic_clock")
```

<img width = "85%" src="/images/plots/futurevisions/atomic_clock.png">

### Categorical

These are palettes that may lend themselves more to purposes where each color is a stand-alone entity with no meaningful order.

``` r
show_palette("venus")
```

<img width = "85%" src="/images/plots/futurevisions/venus.png">

``` r
show_palette("mars")
```

<img width = "85%" src="/images/plots/futurevisions/mars.png">

``` r
show_palette("jupiter")
```

<img width = "85%" src="/images/plots/futurevisions/jupiter.png">

``` r
show_palette("hd")
```

<img width = "85%" src="/images/plots/futurevisions/hd.png">

``` r
show_palette("kepler16b")
```

<img width = "85%" src="/images/plots/futurevisions/kepler16b.png">

``` r
show_palette("pegasi")
```

<img width = "85%" src="/images/plots/futurevisions/pegasi.png">

``` r
show_palette("trappest")
```

<img width = "85%" src="/images/plots/futurevisions/trappest.png">

``` r
show_palette("grand_tour")
```

<img width = "85%" src="/images/plots/futurevisions/grand_tour.png">

``` r
show_palette("atomic_red")
```

<img width = "85%" src="/images/plots/futurevisions/atomic_red.png">

``` r
show_palette("atomic_blue")
```

<img width = "85%" src="/images/plots/futurevisions/atomic_blue.png">

``` r
show_palette("atomic_orange")
```

<img width = "85%" src="/images/plots/futurevisions/atomic_orange.png">


## Background

A portion of the 3rd floor of the Main Library at the University of Georgia has been designed to be evocative of the 1950s when the library was first built. It has some retro-style furniture in a nice study room. It also has some of these Visions of the Future posters hanging up in the hallway. I walk down that hallway every day since the linguistics books, the [DigiLab](https://digi.uga.edu), the best study room on campus, and my personal carrell are all on that floor. 

In fall 2019 I put together [a series of workshops](http://joeystanley.com/pages/dataviz) on data visualization. [One of them](http://joeystanley.com/downloads/191023-color.pdf) was devoted to color, and in preparations for it, I saw that people have made color palettes based on all sorts of things: [Wes Anderson movies](https://www.designcontest.com/blog/inspiration-gallery-wes-anderson-color-palettes/), [Skittles](http://alyssafrazee.com/2014/03/06/RSkittleBrewer.html), [Pokemon](http://pokepalettes.com), you name it. I had the idea that the posters on that floor might make for some fun color palettes. 

I put off making the palettes themselves until now (February 2020). 