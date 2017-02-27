---
layout: post
title:  "R Packages"
date:   2016-12-16 20:22:00 -0400
tags: [how-to guides, methods, skills, statistics]
---
 
Much of my quantitative work and data analysis is done in R. I thought I'd create this page with a list of useful R packages that I use or that I should probably start using more. At the very least, this page will serve as a reminder to myself of how to do stuff, and it might help you too.



General Tools
--------------------

dplyr
==============

ggplot2
==============

There are many many resources out there regarding `ggplot2`. I can't, shouldn't, and frankly don't want to recreate what has been said already. 

I have found it useful to make a custom theme though. I like to have control over how my visualizations look, and I like it when they match the rest of my presentation theme. I also don't like it when I see visualizations in presentations that are clearly the default R theme.  

I discovered how to do this when I was looking at the code for `theme_bw()`. In case you haven't used it, if you add this function to your `ggplot()` command, it'll make a nice black and white theme for you, which I always found to be nice looking. (It's actually just one of several themes: see the help page at `?theme_bw` for other themes to try out.) Here's the code straight from R for convenience: 

~~~~~~
> theme_bw
function (base_size = 12, base_family = "") 
{
  theme_grey(base_size = base_size, base_family = base_family) %+replace% 
    theme(axis.text = element_text(size = rel(0.8)), 
    axis.ticks = element_line(colour = "black"), 
    legend.key = element_rect(colour = "grey80"), 
    panel.background = element_rect(fill = "white", colour = NA), 
    panel.border = element_rect(fill = NA, colour = "grey50"), 
    panel.grid.major = element_line(colour = "grey90", size = 0.2), 
    panel.grid.minor = element_line(colour = "grey98", size = 0.5), 
    strip.background = element_rect(fill = "grey80", colour = "grey50", 
                                    size = 0.2))
}
~~~~~~

When I was looking through the code, I figured out what was going on and through some trial and error, was able to make my own custom theme. So I'll try to explain it for you and you might find it useful too.

So the way this works is I create a function called `theme_joey()` that's based on `theme_bw()`. The following block does that, but it changes the typeface to a font I use called Avenir.

~~~~~~~
theme_joey <- function () { 
    theme_bw(base_size=12, base_family="Avenir")
}
~~~~~~~

Right now `theme_joey()` is just a copy of `theme_bw()`. What I want to do now is change just a few of the properties in this function. To do that, I use the `%+replace%` command, which, in all honesty, I have no idea how it works. What I want to replace are elements of the `theme()` function within `theme_bw()`, so I add that to the function:

~~~~~~~
theme_joey <- function () { 
    theme_bw(base_size=12, base_family="Avenir") %+replace% 
        theme(
            # change stuff here
        )
}
~~~~~~~

Now, I just need to specify which elements of `theme()` I want to change. This took some trial and error, a peek at the help in R, as well as the normal amount of googling. 

The first thing I wanted to to do was remove the background. I didn't want a white one, so take it out entirely:

~~~
panel.background  = element_blank(),
~~~

Then I wanted to change was the background to make it what I've seen described as "smokewhite". In all honesty, I'd prefer a transparent background so that the wherever I copy and paste the image into it'll always match, but I couldn't figure out how to do that. But here's how I specified the color: 

~~~
plot.background = element_rect(fill="gray96", colour=NA), 
~~~

The legend background and key was still white though, so I wanted to make those transparent. Somehow that works, so I just go with it:

~~~
legend.background = element_rect(fill="transparent", colour=NA),
legend.key        = element_rect(fill="transparent", colour=NA)
~~~

So if we put all these elements in the new theme, we get a fully functional customized theme:

~~~~~~~
theme_joey <- function () { 
    theme_bw(base_size=12, base_family="Avenir") %+replace% 
        theme(
            panel.background  = element_blank(),
            plot.background = element_rect(fill="gray96", colour=NA), 
            legend.background = element_rect(fill="transparent", colour=NA),
            legend.key = element_rect(fill="transparent", colour=NA)
        )
}
~~~~~~~

I put this at the top of my R scripts in the same chunk of code where I load my packages and read in my data. I can then just add `theme_joey()` to any `ggplot()` command and like magic all my plots match. It's pretty cool.

So here are some sample plots that show the differences between no theme, `theme_bw()`, and my new `theme_joey()`:

~~~~
# Sample data
df <- data.frame(gp = factor(rep(letters[1:3], each = 10)), y = rnorm(30), color=(rep(c("A", "B"), each=5)))
plot <- ggplot(df, aes(x = gp, y = y, color=color)) + geom_point()

plot + ggtitle("No theme")
~~~~
<img src="/images/plots/themes_plain.pdf" alt="Plot with no theme added" style="width: 30em;"/>

~~~~
plot + ggtitle("Black and White") + theme_bw()
~~~~
<img src="/images/plots/themes_bw.pdf" alt="Plot with black and white theme" style="width: 30em;"/>

~~~
plot + ggtitle("Custom Theme") + theme_joey()
~~~
<img src="/images/plots/themes_joey.pdf" alt="Plot with custom theme applied" style="width: 30em;"/>

Assuming your browser is rendering this webpage like mine is, the last plot should be the same background color as this webpage, and the font should match my header fonts. 

Note that some fonts require different settings if you want to export it as a pdf with `ggsave()`. You just need to add the argument `device=cairo_pdf` to it like so:

~~~
ggsave("themes_joey.pdf", device=cairo_pdf, width = 6, height = 6)
~~~

And that's it! Give it an hour or so and I think you can start to make a custom theme. I like having this because it'll start to add some continuity between my presentations and it shows that you have some R skills beyond the basics needed to make a plot.







plyr
==============

reshape2
==============

tidyr
==============


Linguistics Packages
--------------------

phonR
=============

vowels
=============

norm
=============

Rling
=============

languageR
=============




Statistics
--------------------

adehabitatHR
==============

cluster
==============

lattice
==============

lme4
==============

rms
==============

rpart
==============

sp
==============

Network Analysis
----------------

igraph
============

sna
============
