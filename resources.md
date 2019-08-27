---
layout: resources
title: Resources
toc: false
---

# Resources

On this page you'll find links to all sorts of stuff that I have found useful, including tutorials, books, and general reading on R and Praat, statistics, software, corpora, design, and other stuff.

<br/>
## My handouts, tutorials, and workshops

### [R Workshops](/pages/r-workshops.html)

This is a series of workshops on how to use R which includes a variety of topics. I have included PDFs and additional information on each installment of this series.

### [Formant extraction tutorial](/blog/a-tutorial-on-extracting-formants-in-praat)

This tutorial walks you through writing a praat script that extracts formant measurements from vowels. If you've never worked with Praat scripting but want to work with vowels, this might be a good starting point.

### Vowel plots in R tutorials ([Part 1]({% post_url 2018-03-18-making-vowel-plots-in-r-part-1 %}) and [Part 2]({% post_url 2018-06-06-making-vowel-plots-in-r-part-2 %}))

This is a multi-part tutorial on how to make sort of the typical vowel plots in R. Part 1 shows plotting single-point measurements as scatter plots and serves as a mild introduction to `ggplot2`. Part 2 shows how to plot trajectories, both in the F1-F2 space and in a Praat-like time-Hz space, and is a bit of an introduction to `tidyverse` as well.

### Measuring vowel overlap in R ([Part 1](/blog/a-tutorial-in-calculating-vowel-overlap) and [Part 2](/blog/vowel-overlap-in-r-advanced-topics))

This is a two-part tutorial on calculating Pillai scores and Bhattacharyya's Affinity in R. The first covers what I consider the bare necessities, culminating custom R functions for each. The second is a bit more in-depth as it looks at ways to make the functions more robust, but it also shows some simple visualizations you can make with the output.

### [Make yourself googleable](downloads/161111-DigiLab-slides.pptx)

I'm no expert, but I have given a workshop on how grad students can increase their online presence and make themselves more googleable, based in large part to ImpactStory's fantastic 30-day challenge, which you can read [here](http://blog.impactstory.org/research-impact-challenge-ebook/).

### [Excel Workshop](/excel.html)

Last year I gave a workshop on Excel and ended producing a long handout, that goes from the very basics to relatively tricky techniques. The link above will take you to a blog post that summarizes the workshop, and you can also find the handout itself.

<!--
### MANOVA

In the study of vowel overlaps, we use the Pillai score, which is an output of the MANOVA test. Well what is the MANOVA test anyway? In this extended post (forthcoming), I'll go into detail about the math behind the test and, more importantly for linguists, the assumptions that your data should meet before running it.
-->

<br/>
## R Resources

Here is a list of resources I've found for R. I've gone through some of them and others are on my to-do list. These are in no particular order. 

### General R Coding

* The website for [Tidyverse](https://www.tidyverse.org) is a great go-to place for learning how to use `dplyr`, `tidyr`, and many other packages.

* *[R for Data Science](http://r4ds.had.co.nz/index.html)* by Garrett Grolemund & Hadley Wickham is a fantastic overview of tidyverse functions. 

* *[Intro to Tidyverse](http://varianceexplained.org/r/intro-tidyverse/)* by David Robinson. 

* *[Advanced R](https://adv-r.hadley.nz)* by Hadley Wickham with the [solutions](https://bookdown.org/Tazinho/Advanced-R-Solutions/) by Malte Grosser, Henning Bumann, Peter Hurford & Robert Krzyzanowski.

* *[R Packages](http://r-pkgs.had.co.nz)* by Hadley Wickham.

* *[Hands-On Programming with R](https://d1b10bmlvqabco.cloudfront.net/attach/ighbo26t3ua52t/igp9099yy4v10/igz7vp4w5su9/OReilly_HandsOn_Programming_with_R_2014.pdf)* by Garrett Grolemund & Hadley Wickham for writing functions and simulations. Haven't read it, but it looks good.

* *[r-statistics.co](http://r-statistics.co)* by Selva Prabhakaran which has great tutorials on R itself, ggplot2, and advanced statistical modeling.

* [*Tidymodels*](https://www.tidyverse.org/articles/2018/08/tidymodels-0-0-1/) is like the Tidyverse suite of packages, but it's meant for better handling of many statistical models. Also see it's [GitHub](https://github.com/tidymodels/tidymodels) page.

* *[Learn to purrr](http://www.rebeccabarter.com/blog/2019-08-19_purrr/)* by [Rebecca Barter](http://www.rebeccabarter.com) is the tutorial on purrr that I wish I had.

* *[Modern R with the Tidyverse](https://b-rodrigues.github.io/modern_R/)* by Bruno Rodriguez is a work in progress, but it's another free eBook that shows R and the Tidyverse.

### Working with Text

* *[Text Mining with R](http://tidytextmining.com)* by Julia Silge & David Robinson. Haven't read it, but it looks great.

* *[Handling Strings with R](http://www.gastonsanchez.com/r4strings/)* by Gaston Sanchez.

* *[Visualizing text data with ggplot2](https://github.com/ColinFay/conf/blob/master/2017-11-budapest/fay_colin_text_data_ggplot2.pdf?utm_content=buffer56bdc&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)* by Colin Fay. 

* If you use the CMU Pronouncing Dictionary, you should look at the new *[phon](https://coolbutuseless.github.io/2018/12/03/phon-a-package-for-rhymes-etc/)* package. It makes the whole thing searchable and easy to find rhymes. Personally, this'll make it a lot easier to find potential words for a word list.  

* The [ggtext package](https://github.com/clauswilke/ggtext) by [Claus O. Wilke](https://serialmentor.com/blog/) makes it a lot easier to work with text if you want to add a little bit of rich text to your plots.

### Working with Twitter

* *[21 Recipes for Mining Twitter Data with rtweet](https://rud.is/books/21-recipes/)* by Bob Rudis is a tutorial that illustrates how to extract and do a whole bunch of stuff with Twitter data in R.

* *[R Ready to Map](https://github.com/momiji15/apptomap/tree/master/R%20Ready%20to%20Map)* is a tutorial by [Dorris Scott](https://dscott.netlify.com) that starts off using the rtweet package to extract some Twitter data, shows you how to map it, and then walks you through creating an interactive RMarkdown document that integrates leaflet maps and plots.

### RMarkdown and Bookdown

* *[Elegant, flexible, and fast dynamic report generation with R](https://yihui.name/knitr/)* by Yihui Xie is a great resource for RMarkdown.

* [*R Markdown: The Definitive Guide*](https://bookdown.org/yihui/rmarkdown/) Yihui Xie, J. J. Allaire, and Garrett Grolemund is the comprehensive guide to R Markdown and Bookdown. 

* *[bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)* by Yihui Xie. See an introduction to Bookdown by RStudio [here](https://www.rstudio.com/resources/webinars/introducing-bookdown/).

* If your love for Zotero is what's preventing you from using RMarkdown, never fear! *[Zotero hacks: unlimited synced storage and its smooth use with rmarkdown](https://ikashnitsky.github.io/2019/zotero/)* by [Ilya Kashnitsky](https://ikashnitsky.github.io) is the perfect guide to getting those two integrated.

### GIS and Spatial Stuff

* *[Maps and Data Visualisations with R](http://spatial.ly/r/)* by [James Cheshire](http://spatial.ly/about/) is a treasure trove of tutorials on doing a whole bunch of maps in R.

* *[An Introduction to Spatial Analysis in R](http://www.seascapemodels.org/rstats/rspatial/2015/06/22/R_Spatial_course.html)* by [Chris Brown](http://www.seascapemodels.org).

* *[Spatial Data Science](https://keen-swartz-3146c4.netlify.com)* by [Edzer Pebesma](https://www.uni-muenster.de/Geoinformatics/en/institute/staff/index.php/119/Edzer_Pebesma) and [Roger Bivand](https://www.nhh.no/en/employees/faculty/roger-bivand/).

* *[Spatial and Spatioteporal Data Analysis in R](https://github.com/edzer/User2019)*, a workshop [Edzer Pebesma](https://www.uni-muenster.de/Geoinformatics/en/institute/staff/index.php/119/Edzer_Pebesma), [Roger Bivand](https://www.nhh.no/en/employees/faculty/roger-bivand/), and Angela Li at the useR! 2019 conference on Jul 9, 2019.

* *[Geocomputation with R](https://geocompr.robinlovelace.net)* by Robin Lovelace, Jakub Nowosad, and Jannes Muenchow.

* I get all my shape files from the [National Historical Geographic Information System (NHGIS) website](https://www.nhgis.org). 

* And because I haven't quite gotten the hang of it yet in R, I do all my mapmaking using the [QGIS](https://qgis.org/en/site/), the open-source, Mac-friendly, and free alternative to [ArcGIS](https://www.arcgis.com/index.html). Shout-out to [@mjduever](https://twitter.com/mjduever) of UGA Libraries for teaching me everything I know about GIS.

### Working with Census Data

* *[A Guide to Working with US Census Data in R](https://rconsortium.github.io/censusguide/)* by Ari Lamstein and Logan Powell is a nice, brief guide to census data and some places to go if you want to work with it in R.

* The [tidycensus](https://walkerke.github.io/tidycensus/) package by [Kyle Walker](http://personal.tcu.edu/kylewalker/) looks really slick and makes it easy to work with census data within the Tidyverse framework. This blog post, *[Burden of roof: revisiting housing costs with tidycensus](https://austinwehrwein.com/data-visualization/housing/)*, by [Austin Wehrwein](https://austinwehrwein.com) is a walkthrough of a real-world application with tidycensus.





<br/>
## Data Visualization

### Books

* *[ggplot2](http://www.springer.com/us/book/9783319242750)* by Hadley Wickham is a comprehensive resource for learning all the ins and outs of ggplot2. Version 3 is due in 2020, but you can look through what's been written so far [here](http://ggplot2-book.org).

* [*Data Visualization: A Practical Introduction*](http://socviz.co) by [Kieran Healy](kieranhealy.org). I haven't had the time to look through it, but this books looks quite good. It covers data prep, basic plots, visualizing statistical models, maps, and a whole bunch of other stuff. 

* [*Fundamentals of Data Visualization*](https://serialmentor.com/dataviz/) by [Claus O. Wilke](https://integrativebio.utexas.edu/component/cobalt/item/7-integrative-biology/237-wilke-claus-o?Itemid=1224) is still in preview mode, but it is "meant as a guide to making visualizations that accurately reflect the data, tell a story, and look professional." 

* *[Interactive web-based data visualization with R, plotly, and shiny](https://plotly-r.com)* by [Carson Sievert](https://cpsievert.me) is another free online book on data visualizatio in in R. This has a good focus on interactivity since it involves [plotly](https://plot.ly) and [Shiny](https://shiny.rstudio.com).

* *[Mastering Shiny](https://mastering-shiny.org)* by Hadley Wickham is under development and will be released late 2020. I'm looking forward to this comprehensive book on Winston Chang's [shiny](https://shiny.rstudio.com) package a lot actually, but in the meantime though you and I can peruse the online version for free.

### Colors

* The [`scion`](https://www.data-imaginist.com/2018/scico-and-the-colour-conundrum/) package has a bunch of colorblind-safe, perceptually uniform, ggplot2-friendly color palettes for use in visuals. Very cool.

* The [color brewer website](http://colorbrewer2.org), while best for maps, offers great color palettes that are colorblind and sometimes also printer-safe. The have native integration with `ggplot2` with the `scale_[color|fill]_ [brewer|distiller]` [functions](https://ggplot2.tidyverse.org/reference/scale_brewer.html). 

* Paul Tol has come up with some [additional color themes](https://personal.sron.nl/~pault/), which you can access with `scale_color_ptol` in the [`ggthemes`](https://www.rdocumentation.org/packages/ggthemes/versions/3.5.0) package.

* If you want to make your own discrete color scale in R, definitely check out [Garrick Aden-Buie](https://www.garrickadenbuie.com)'s tutorial, *[Custom Discrete Color Scales for ggplot2](https://www.garrickadenbuie.com/blog/custom-discrete-color-scales-for-ggplot2/)*. 


### Animation

* Thomas Lin Pedersen's [gganimate](https://gganimate.com) package has now made it possible to make really cool animations in R. Sometimes you want to add a bit of pizzazz to your presentation, but other times animation really is the best way to visualize something. Either way, this package will help you out a lot.

### Rayshader

* Definitely check out [Tyler Morgan-Wall's](https://www.tylermw.com) [rayshader](https://www.rayshader.com) package. It makes it pretty simple to make absolutely *stunning* 3D images of your data in R. You can make 3D maps if you have spatial data, but you can also turn any boring ggplot2 plot into a 3D work of art. Seriously, go try it out.

* [Lego World Map - Rayshader Walkthrough](https://arthurwelle.github.io/RayshaderWalkthrough/index.html) by [Arthur Welle](https://twitter.com/ArthurWelle) is an awesome walkthrough on rayshader and maps made out of virtual Legos. It's a lot of fun.

### Making better plots

* Edward Tufte is a statistician known for his series of four books that focus on best practices in the presentation of data:  [*The Visual Display of Quantitative Information*](https://www.edwardtufte.com/tufte/books_vdqi), [*Envisioning Information*](https://www.edwardtufte.com/tufte/books_ei), [*Visual Explanations*](https://www.edwardtufte.com/tufte/books_visex), and [*Beautiful Evidence*](https://www.edwardtufte.com/tufte/books_be). I read them over several months on the bus and they are very cool. As a practical application of them, [this page](http://motioninsocial.com/tufte/) by Lukasz Piwek shows how to implement many of these visualizations in R. You can also use `ggthemes` to get some of this implementation. 

* Joey Cherdarchuk of [Darkhorse Analytics](https://www.darkhorseanalytics.com) has put together some really succinct presentations on how to simplify things you might put in a paper like [maps](https://www.darkhorseanalytics.com/blog/data-looks-better-naked-maps-edition), [charts](https://www.darkhorseanalytics.com/blog/salvaging-the-pie), [tables](https://www.darkhorseanalytics.com/blog/clear-off-the-table), and [reducing the data to ink ratio](https://www.darkhorseanalytics.com/blog/data-looks-better-naked).

### Miscellany

* The [R Graph Gallary](https://www.r-graph-gallery.com) has hundreds of plots, with code, illustrating what the plots are typically used for and different variants of the same plot. Very cool.

* My friend [Andres Karjus](https://andreskarjus.github.io) has given several workshops on wide range of data visualization topics, collectively called *[aRt of the figure: explore and visualize your data using R](https://andreskarjus.github.io/artofthefigure/)*. You should definitely explore his github and check out his materials.

* This [blog post](https://www.jessesadler.com/post/network-analysis-with-r/) by Jesse Sadler is a great tutorial on how to use R to visualize network data.

* Plotting special characters or unique fonts can be tricky. [Yixuan Qiu](https://statr.me)'s tutorial *[showtext: Using Fonts More Easily in R Graphs](https://cran.rstudio.com/web/packages/showtext/vignettes/introduction.html)* can help you with that.

* [George Bailey's](http://www-users.york.ac.uk/~gb1055/) excelent workshop materials for visualizing vowel formant data can be found [here](http://www-users.york.ac.uk/~gb1055/sociophonetics_workshop/index.html).



<br/>
## Statistics Resources

### General Statistics Knowledge

* The American Statistical Association, which is essentially the statistics equivalent in scope and prestige as the the Linguistic Society of America, put out a [statement on *p*-values](https://amstat.tandfonline.com/doi/full/10.1080/00031305.2016.1154108#.WzA-Wi2ZPOR) in 2016. In March of 2019, they followed up with a monster 43-article special issue, *Statistical Inference in the 21st Century: A World Beyond p < 0.05*, wherein they recommend that the expression "statistically significant" be abandoned. This has potential to  be a pivot point in the field of statistics. Why should a linguist care? Well, the first article in that issue says "If you use statistics in research, business, or policymaking but are not a statistician, these articles were indeed written with YOU in mind." If you use statistics in your research, it might be worth reading through at least the first article of this issue.

* The book *[Modern Dive: An Introduction to Statistical and Data Sciences via R](https://moderndive.com)* by Chester Ismay and Albert Y. Kim is a free eBook available that teachest the basics of R and statistics. See [Andrew Heiss's post](https://www.andrewheiss.com/blog/2018/12/05/test-any-hypothesis/) about this book for more information.

* *[Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing](https://www.autodeskresearch.com/publications/samestats)* by Justin Matejka and George Fitzmaurice. This went viral in some circles and shows that you can get the exact same summary statistics with wildly different distributions. Very cool. 

* Here's a [BuzzFeed article](https://www.buzzfeed.com/stephaniemlee/brian-wansink-cornell-p-hacking?utm_term=.rkMwm8D0J#.ffAq3aVye) by Stephanie M. Lee about a researcher who made the news because of his unbelieveable amount of *p*-hacking and using "statistics" to lie about his data.

### Linear mixed-effects models

* [Bodo Winter's](http://www.bodowinter.com/index.html) [mixed-effects modeling tutorials](http://www.bodowinter.com/tutorials.html) are the best resource I've found on using these in linguistics research. It's a two-part tutorial, so be sure to look through both of them. 

* [Mixed-Effects Regression Models in Linguistics](https://www.springer.com/us/book/9783319698281), edited by Dirk Speelman, Kris Heylen, & Dirk Geeraerts and published by Springer is an entire book on mixed-effects models, specifically for linguists. 

* [Michael Clark's](https://m-clark.github.io) post called [Shrinkage in Mixed Effects Models](https://m-clark.github.io/posts/2019-05-14-shrinkage-in-mixed-models/) has some beautiful illustrations that demonstrate shirnkage. In fact, he has written [a much larger document](https://m-clark.github.io/mixed-models-with-R/) explaining what mixed-effects models and how to run them in R.

* *[Mixed Modeling as a Foreign Language](http://thestudyofthehousehold.com/2018/02/28/2018-02-28-formulae-are-a-lot-like-french-slang/)*, a blog post by Andrew McDonald, first off is a good explanation of what mixed modeling is all about. But more importantly, it makes the point that "if you only partly understand the words you are using, you *will* humiliate yourself eventually." In other words, it's important to know what you're doing when you use statistics, and if you don't, maybe you should reconsider before you do something wrong.

### GAM(M)s

My dissertation makes heavy use of generalized additive mixed-effects models (GAMMs). Here are some resources that I used to help learn about these.

* *[Generalised Additive Mixed Models for Dynamic Analysis in Linguistics: A Practical Introduction](https://arxiv.org/pdf/1703.05339.pdf)* by Márton Sóskuthy.

* *[How to analyze linguistic change using mixed models, Growth Curve Analysis and Generalized Additive Modeling](https://academic.oup.com/jole/article/1/1/7/2281883)* by [Bodo Winter](http://www.bodowinter.com) and [Martijn Wieling](http://www.martijnwieling.nl) is a tutorial on using GAMs---with one *M*---and Growth Curve Analysis.

* *[Analyzing dynamic phonetic data using generalized additive mixed modeling: A tutorial focusing on articulatory differences between L1 and L2 speakers of English](https://www.sciencedirect.com/science/article/pii/S0095447017301377?via%3Dihub)* is another tutorial by [Martijn Wieling](http://www.martijnwieling.nl) in the Journal of Phonetics.

* In fact, [Martijn Wieling](http://www.martijnwieling.nl) has the slides for a graduate course in statistical methods, including GAMMs, avilable on his [website](http://www.martijnwieling.nl/statistics.php). 

* *[Studying Pronunciation Changes with gamms](http://jofrhwld.github.io/papers/edinbr_gamm/)* by Josef Fruehwald.

* *[Overview GAMM analysis of time series data](http://jacolienvanrij.com/Tutorials/GAMM.html)* by Jacolien van Rij. I haven't had time to go through this one yet, but it's on my todo list. Actually [all of her tutorials](http://www.jacolienvanrij.com/cv.html) look great.  

* *[tidymv: Tidy Model Visualisation](https://github.com/stefanocoretta/tidymv)* is an R package by [Stefano Coretta](https://stefanocoretta.github.io) that lets you visualize GAMMs using tidyverse-friendly code.

* *[GAMs in R](https://noamross.github.io/gams-in-r-course/)* by [Noam Ross](https://www.ecohealthalliance.org/personnel/dr-noam-ross) is a free interactive course on GAMs in R.

* Since model objects can get huge, you might want to try [Joyce Cahoon's](https://jcahoon.netlify.com/#about) [butcher](https://jcahoon.netlify.com/post/2019/08/08/model-butcher/) package to reduce the size of those giant objects. 

### Other Models

I know there are other types of models out there but I haven't had the opportunity to use them. Here are some resources I've found that might be good for me down the road.

* *[15 Types of Regression You Should Know](https://www.listendata.com/2018/03/regression-analysis.html#.WrqjTxC-HWE.twitter)* is a post on the blog *Listen Data* that is a nice overview of different kinds of regression and how to implement them in R.

* [Introduction to Generalized Linear Models](http://statmath.wu.ac.at/courses/heather_turner/) by [Heather Turner](http://www.heatherturner.net/)

* [Course materials](https://github.com/hturner/gnm-half-day-course) for the generalized nonlinear models (GNM) half-day course at the useR! 2019 conference by [Heather Turner](http://www.heatherturner.net/). Here's her [full-day version](https://github.com/hturner/gnm-day-course) from Zurich R Course series. 

### Miscelleny

* This workshop, *[Dimension reduction with R](http://rpubs.com/Saskia/520216)*, by [Saskia Freytag](https://twitter.com/trashystats) shows different methods for dimension reduction, weighs their pros and cons, and includes examples and visuals of their applications. Pretty useful.

* If you use statistical modeling in your research, the [`report`](https://github.com/easystats/report/blob/master/README.md) package is a useful tool to convert your model into human-readable prose. 


<br/>
## Praat Resources

* [Will Styler's](http://savethevowels.org/will/) Praat tutorial is probably the most thorough I've seen. The PDF can be found [here](http://savethevowels.org/praat/UsingPraatforLinguisticResearchLatest.pdf) but don't forget to look at the [page](http://savethevowels.org/praat/) it comes from which has more information about it. 

* *[Phonetics on Speed: Praat Scripting Tutorial](http://praatscripting.lingphon.net)* by Jörg Mayer is what I find myself coming back to again and again.

* *[SpeCT - The Speech Corpus Toolkit for Praat](https://lennes.github.io/spect/)* is a collection of well-documented Praat scripts written by [Mietta Lennes](http://orcid.org/0000-0003-4735-3017). I often find my way to this page when I need help for a specific task in Praat and incorporate some of the code in these scripts into my own.

* [University of Washington Phonetics Lab](https://depts.washington.edu/phonlab/resources.htm) has a bunch of tutorials and scripts.

* And I've written a [tutorial](/blog/a-tutorial-on-extracting-foramnts-in-praat) on writing a script for basic automatic formant extraction. 


<br/>
## Working with audio

There are three main steps for processing audio: transcription, forced alignment, and formant extraction. 

### Automatic Transcription

There is software available that you can use to transcribe in like Praat, [Transcriber](http://trans.sourceforge.net/en/presentation.php), and [ELAN](https://tla.mpi.nl/tools/tla-tools/elan/). But here are some tools I've seen that do automatic transcription. 

* [CLO<sub>x</sub>](https://clox.ling.washington.edu/index.html) is a new automatic transcriber available from the University of Washington. It's a web-based service that uses Microsoft Bing's Speech Recognition system to transcribe your audio. It's estimated that a sociolinguistic interview can be transcribed in a fifth the time as a manual transcription. The great news is that it's available for several languages!

* [DARLA](http://darla.dartmouth.edu) is actually a whole collection of tools available through a web interface from Dartmouth University. It can transcribe, align, and extract formants from your (English) audio files all in one go. For automatic transcription, you can use their own in-house system by using the "Completely Automated" method. They admit the transcriptions won't be perfect, but they provide a handy tool for manual correcting.

* [OH-Portal](https://www.phonetik.uni-muenchen.de/apps/oh-portal/) is by the [Institute of Phonetics and Speech Processing](https://www.en.phonetik.uni-muenchen.de/index.html). It works on several languages, and on clean lab data, it's a little faster to run this and correct the transcription than it is to do a transcription from scratch. Runs entirely through the web browser, so you don't have to download anything.

### Forced Aligners

I've got a lot of audio that I need to process, so a crucial part of all that is force aligning the text to the audio. Smart people have come up with free software to do this. Here's a list of the ones I've seen.

* [DARLA](http://darla.dartmouth.edu), avilable from Dartmouth University, is the one I've used the most. It can transcribe, align, and extract formants from your (English) audio files all in one go. Previously, its forced aligner is built using Prosody-Lab but now uses the Montreal Forced Aligner (see below).

* The [Montreal Forced Aligner](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) is a relatively new one that I heard about for the first time at the 2017 LSA conference. It is fundamentally different than other ones in that it uses a software called Kaldi. It's easy to set up and install and I've used it on my own data. The benefit of this over DARLA is that it's on your own computer so you don't have to wait for files to upload. And you can process files in bulk. 

* [FAVE](https://github.com/JoFrhwld/FAVE) is probably the most well-known forced aligner. It's open source and you can download it on your own computer from [Joe Fruehwald's Github page](https://github.com/JoFrhwld). Or if you'd prefer, you can UPenn's their [web interface](http://fave.ling.upenn.edu) instead.

* [Prosodylab-Aligner](http://prosodylab.org/tools/aligner/) is, according to their website, "a set of Python and shell scripts for performing automated alignment of text to audio of speech using Hidden Markov Models." This is a software available through McGill University that actually allows you to train your own acoustic model (*e.g.* on a non-English audio corpus). I haven't used it yet, but if I ever need to process non-English audio, this'll be my go-to. 

* [SPPAS](http://www.sppas.org/index.html) is a software package with several functions including forced alignment in several languages. Of the aligners you can download to your computer, this might be one of the easier ones to use. 

* [WebMAUS](http://clarin.phonetik.uni-muenchen.de/BASWebServices/#/services) is another web interface with multiple functions including a forced aligner for several languages.

* [Gentle](https://lowerquality.com/gentle/) advertises itself as a "robust yet lenient forced aligner built on Kaldi." It's easy to download and use and produces what appear to be very good word-level alignments of a provided transcript. It even ignored the interviewer's voice in the file I tried. The output is a .csv file, so I'm not sure how to turn that into a TextGrid, and if you need phoneme-level acoustic measurements, a word-level transcription isn't going to work.

### Formant Extractors

* [FAVE-Extract](https://github.com/JoFrhwld/FAVE/wiki/FAVE-extract) is the gold-standard that tons of people use.

* If you want to do write a script yourself, I've written a [tutorial](/blog/a-tutorial-on-extracting-foramnts-in-praat) on writing a script for basic automatic formant extraction. 

<br/>
## Corpora

For whatever reason, sometimes it's nice to uses data that already exists rather than collect your own. Here are just a few of the sites I've seen for downloading audio for (potential) linguistic research.

### Audio Corpora

* [CORAAL](https://oraal.uoregon.edu/coraal) is the Corpus of Regional African American English, the first public corpus of African American Language. You can download the audio and transcriptions in their entirety [here](http://lingtools.uoregon.edu/coraal/) or search and browse the corpus [from the website](http://lingtools.uoregon.edu/coraal/explorer/). 

* The [Linguistic Atlas Project](http://www.lap.uga.edu) is an important work for American dialectology. Early linguists interviewed thousands of people from across the country, mostly between the 1930s and the 1980s. If you've heard of the Linguistic Atlas of New England (LANE), the Linguistic Atlas of the Middle Atlantic States (LAMSAS), or the Linguistic Atlas of the Gulf States (LAGS), these are all under the umbrella of the Linguistic Atlas Project and serve as a baseline from which contemporary data compared against to study language change in real time. Many of the recordings are available to download online (for those that were recorded after portable technology existed, so around 1950 or later). There arne't too many full transcriptions yet, but there are scans of handwritten transcriptions of key words available to download.  

* The [Dictionary of American Regional English (DARE)](http://dare.wisc.edu) recently made [all of their audio](https://uwdc.library.wisc.edu/collections/AmerLangs/) available online. This is a nice collection of older recordings from all over the country. 

* The [International Dialects of English Archive (IDEA)](https://www.dialectsarchive.com) has a nice collection of over 1000 short audio clips featuring basically every variety of English (native and non-native) you can think of. It's designed with voice actors in mind, but it can still be used for linguistic analysis. 

* [StoryCorps](https://storycorps.org) has tons of recorded interviews available for download. I've seen audio from this site used a couple times for linguistic analysis. 

* The Library of Congress hosts thousands of [recorded interviews](https://www.loc.gov/audio/?fa=subject:interviews). I don't recall seeing these used in linguistic research, but some of them are older and could be good for something.


### Text Corpora

* [COCA](https://corpus.byu.edu/coca/), [COHA](https://corpus.byu.edu/coha/), and [many others](https://corpus.byu.edu) are all created by Mark Davies at Brigham Young University. These are said to be the gold standard when it comes to balanced, large corpora. 

* Jason Baumbartner has done the legwork to make [the entirety of Reddit](https://files.pushshift.io/reddit/) available for download. I worked with this data when he first released it in 2015, and it was about a 50-*billion* word corpus back then. Reddit has grown tremendously even since then so you're looking at some truly big data. Super cool. 

<br/>
## Typography, Web Design, and CSS

I enjoy reading and attempting to implement good typography into my website. Here are some resources that I have found helpful for that.

### Beautiful Websites

I designed this website more or less from scratch, so I can appreciate the work others put into their own academic sites. Here are some examples of beautiful websites that I have found that I really like.

* [Kieran Healy](https://kieranhealy.org) has one of the beautiful academic websites I've ever seen. I created this category on this page just so I could include his page on here. Wow.

* [Practical Typography](https://practicaltypography.com) by Matthew Butterick is was my gateway into typography. My font selection and many other little details on my site (slides, posters, CV, etc.) were influenced by this book. 

### CSS

* If you enjoy the work of Edward Tufte and would like to incorporate some of his design principles into your website, you'll be interested in Tufte CSS by [Dave Liepmann](https://www.daveliepmann.com). If you're interested in your RMarkdown files rendering in a Tufte-style (like [this](https://bookdown.org/yihui/bookdown-demo3/2-intro.html)), there are ways to do that too, which you can read in [chapter 3 of *bookdown*](https://bookdown.org/yihui/bookdown/html.html#tufte-style) by Yihui Xie or [chapter 6 of *R Markdown*](https://rstudio.github.io/tufte/), by Yihui Xie, J. J. Allaire, and Garrett Grolemund (*cf.* [this](https://rstudio.github.io/tufte/)).


<br/>
## Miscellaneous

Just random stuff that doesn't fit elsewhere.

* [The great American word mapper](https://qz.com/862325/the-great-american-word-mapper/#int/words=dinner_supper&smoothing=3) is an interactive tool put together by Diansheng Guo, [Jack Grieve](https://sites.google.com/view/grievejw), and [Andrea Nini](https://andreanini.com) that lets you see regional trends in how words are used on Twitter.

* *[Collecting, organizing, and citing scientific literature: an intro to Zotero](http://ideophone.org/slides-for-a-hands-on-zotero-workshop/)* is a great tutorial on how to use Zotero by Mark Dingemanse. Zotero is a fantastic tool for, well, collecting, organizing, and citing scientific literature and I'm not exaggerating when I say that I could not be in academics without it.

* [Pink Trombone](http://dood.al/pinktrombone/) is an interesting site that has a interactive simulator of the vocal tract. You can click around and make different vowels and consonants. Pretty fun resource for teaching how speech works.

* [Vulgar: A Language Generator](https://www.vulgarlang.com) is a site that automatically creates a new conlang, based on parameters that you specify. The free web version allows you to add whatever vowels and consonants you'd like to include, and it'll create a full language: a language name; IPA chart for vowels and consonants; phonotactics; phonological rules; and paradigms for nominal morphology, definite and indefinite articles, personal pronouns, and verb conjugations; derivational morphology; and a lexicon of over 200 words. For $19 you can download the software and get a lexicon of 2000 words, derivational words, random semantic overlaps with natural languages, and the ability to customize orthography, syllable structure, and phonological rules. In addition to just being kinda fun, this is a super useful resource for creating homework assignments for students.

* [IPA Phonetics](https://itunes.apple.com/us/app/ipa-phonetics/id869642260?mt=8) is an iPhone app has what they call an "elaborated" IPA chart with lots of extra places and manners of articulation, complete with audio clips of all the sounds. You can play a game where it'll play a sound and you can guess what you heard. It's just fun to see things like a voiced uvular fricative (ɢʁ) or a dentolabial fricative [θ̼] on an IPA chart. Credits to University of Victoria linguistics and John Esling's "Phonetic Notation" (chapter 18 of the Handbook of Phonetic Sciences, 2nd ed.).

* [The EMU-webApp](https://ips-lmu.github.io/EMU-webApp/) "is a fully fledged browser-based labeling and correction tool that offers a multitude of labeling and visualization features." I haven't given this enough time to learn to use it properly, but it seems very helpful.

* [Jonhannes Haushofer's CV of Failures](https://www.princeton.edu/~joha/Johannes_Haushofer_CV_of_Failures.pdf). Other people have written this more elegantly than I could, but sometimes it's nice to see that other academics fail too. You're not going to get into all the conferences you apply for, your papers are sometimes going to be rejected, and you're definitely not getting all the funding you apply for. I find it therapeutic to put together a CV of failures like his researcher did and to keep it updated and formatted just as would a regular CV. Don't let impostor syndrome get in the way by thinking others haven't failed too.

* Kieran Healey's *[The Plain Person’s Guide to Plain Text Social Science](http://plain-text.co)* is an entire book on an aspect of productivity that I've only thought about occasionally: what kind of software should you do your work? Before you get too entrenched in your workflow, it's good to consider what your options are. 