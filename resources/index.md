---
layout: resources
title: Resources
toc: false
---

# Resources

On this page you'll find links to all sorts of stuff that I have found useful, including software, tutorials, books, general reading on R, statistics, Praat, and other stuff.


<br/>
## My handouts, tutorials, and workshops

### [R Workshops](/pages/r-workshops.html)

I'm currently giving a series of workshops on how to use R which will include a variety of topics. I have included PDFs and additional information on each installment of this series.

### [Formant extraction tutorial](/blog/a-tutorial-on-extracting-formants-in-praat)

This tutorial walks you through writing a praat script that extracts formant measurements from vowels. If you've never worked with Praat scripting but want to work with vowels, this might be a good starting point.

### Vowel plots in R tutorials

This is a multi-part tutorial on how to make sort of the typical vowel plots in R. [Part 1]({% post_url 2018-03-18-making-vowel-plots-in-r-part-1 %}) shows plotting single-point measurements as scatter plots and serves as a mild introduction to `ggplot2`. [Part 2]({% post_url 2018-06-06-making-vowel-plots-in-r-part-2 %}) shows how to plot trajectories, both in the F1-F2 space and in a Praat-like time-Hz space, and is a bit of an introduction to `tidyverse` as well.

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

### Data Visualization

* *[ggplot2](http://www.springer.com/us/book/9783319242750)* by Hadley Wickham is a comprehensive resource for learning all the ins and outs of ggplot2.

* The *[scion](https://www.data-imaginist.com/2018/scico-and-the-colour-conundrum/)* package has a bunch of colorblind-safe, perceptually uniform, ggplot2-friendly color palettes for use in visuals. Very cool.

* The [color brewer website](http://colorbrewer2.org), while best for maps, offers great color palettes that are colorblind and sometimes also printer-safe. The have native integration with `ggplot2` with the `scale_[color|fill]_[brewer|distiller]` [functions](https://ggplot2.tidyverse.org/reference/scale_brewer.html). 

* This [blog post](https://www.jessesadler.com/post/network-analysis-with-r/) by Jesse Sadler is a great tutorial on how to use R to visualize network data.

* Edward Tufte is a statistician known for his series of four books that focus on best practices in the presentation of data:  [*The Visual Display of Quantitative Information*](https://www.edwardtufte.com/tufte/books_vdqi), [*Envisioning Information*](https://www.edwardtufte.com/tufte/books_ei), [*Visual Explanations*](https://www.edwardtufte.com/tufte/books_visex), and [*Beautiful Evidence*](https://www.edwardtufte.com/tufte/books_be). I haven't read them, but have thumbed through them and they look very cool. As a practical application of them, [this page](http://motioninsocial.com/tufte/) by Lukasz Piwek shows how to implement many of these visualizations in R.

### Working with Text

* *[Text Mining with R](http://tidytextmining.com)* by Julia Silge & David Robinson. Haven't read it, but it looks great.

* *[Handling Strings with R](http://www.gastonsanchez.com/r4strings/)* by Gaston Sanchez.

* *[Visualizing text data with ggplot2](https://github.com/ColinFay/conf/blob/master/2017-11-budapest/fay_colin_text_data_ggplot2.pdf?utm_content=buffer56bdc&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)* by Colin Fay. 


### RMarkdown and Bookdown

* *[Elegant, flexible, and fast dynamic report generation with R](https://yihui.name/knitr/)* by Yihui Xie is a great resource for RMarkdown.

* [*R Markdown: The Definitive Guide*](https://bookdown.org/yihui/rmarkdown/) Yihui Xie, J. J. Allaire, and Garrett Grolemund is the comprehensive guide to R Markdown and Bookdown. 

* *[bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)* by Yihui Xie. See an introduction to Bookdown by RStudio [here](https://www.rstudio.com/resources/webinars/introducing-bookdown/).


<br/>
## Statistics Resources

### General Statistics Knowledge

* The American Statistical Association, which is essentially the statistics equivalent in scope and prestige as the the Linguistic Society of America, put out a [statement on *p*-values](https://amstat.tandfonline.com/doi/full/10.1080/00031305.2016.1154108#.WzA-Wi2ZPOR). It is brief and written in accessible language and in my opinoin should be required reading if you ever use or interpret *p*-values in your research. 

* *[Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing](https://www.autodeskresearch.com/publications/samestats)* by Justin Matejka and George Fitzmaurice. This went viral in some circles and shows that you can get the exact same summary statistics with wildly different distributions. Very cool. 

* *[15 Types of Regression You Should Know](https://www.listendata.com/2018/03/regression-analysis.html#.WrqjTxC-HWE.twitter) is a post on the blog *Listen Data* that is a nice overview of different kinds of regression and how to implement them in R.

* *[Mixed Modeling as a Foreign Language](http://thestudyofthehousehold.com/2018/02/28/2018-02-28-formulae-are-a-lot-like-french-slang/)*, a blog post by Andrew McDonald, first off is a good explanation of what mixed modeling is all about. But more importantly, it makes the point that "if you only partly understand the words you are using, you *will* humiliate yourself eventually." In other words, it's important to know what you're doing when you use statistics, and if you don't, maybe you should reconsider before you do something wrong.

* Here's a [BuzzFeed article](https://www.buzzfeed.com/stephaniemlee/brian-wansink-cornell-p-hacking?utm_term=.rkMwm8D0J#.ffAq3aVye) by Stephanie M. Lee about a researcher who made the news because of his unbelieveable amount of *p*-hacking and using "statistics" to lie about his data.

### How-Tos and Tutorials

* *[Studying Pronunciation Changes with gamms](http://jofrhwld.github.io/papers/edinbr_gamm/)* by Josef Fruehwald.

* *[Generalised Additive Mixed Models for Dynamic Analysis in Linguistics: A Practical Introduction](https://arxiv.org/pdf/1703.05339.pdf)* by Márton Sóskuthy.

* *[Overview GAMM analysis of time series data](http://jacolienvanrij.com/Tutorials/GAMM.html)* by Jacolien van Rij. I haven't had time to go through this one yet, but it's on my todo list. Actually [all of her tutorials](http://www.jacolienvanrij.com/cv.html) look great.  

* *[tidymv: Tidy Model Visualisation](https://github.com/stefanocoretta/tidymv)* is an R package by [Stefano Coretta](https://stefanocoretta.github.io) that lets you visualize GAMMs using tidyverse-friendly code.

<!--
[//]: # ## Quantitative People
[//]: # * [Josef Fruehwald](https://jofrhwld.github.io)
[//]: # * [Daniel Ezra Johnson](http://www.danielezrajohnson.com)
[//]: # * [Bradley T. Rentz](https://rentzb.github.io/#talks)
[//]: # * [Margaret E. L. Renwick](http://faculty.franklin.uga.edu/mrenwick/)
-->

<br/>
## Praat Resources

* [Will Styler's](http://savethevowels.org/will/) Praat tutorial is probably the most thorough I've seen. The PDF can be found [here](http://savethevowels.org/praat/UsingPraatforLinguisticResearchLatest.pdf) but don't forget to look at the [page](http://savethevowels.org/praat/) it comes from which has more information about it. 

* [Phonetics on Speed: Praat Scripting Tutorial](http://praatscripting.lingphon.net)* by Jörg Mayer is what I find myself coming back to again and again.

* [University of Washington Phonetics Lab](https://depts.washington.edu/phonlab/resources.htm) has tutorials and scripts.

* And I've written a [tutorial](/blog/a-tutorial-on-extracting-foramnts-in-praat) on writing a script for basic automatic formant extraction. 


<br/>
## Forced Aligners

### [DARLA](http://darla.dartmouth.edu)

This is my personal favorite. It's actually a whole collection of tools available through a web interface from Dartmouth University. It can transcribe, align, and extract formants from your (English) audio files all in one go. Previously, its forced aligner is built using Prosody-Lab but now uses the Montreal Forced Aligner (see below).

### [FAVE](https://github.com/JoFrhwld/FAVE)

This probably the most well-known forced aligner. It's open source and you can download it on your own computer from [Joe Fruehwald's Github page](https://github.com/JoFrhwld). Or if you'd prefer, you can UPenn's their [web interface](http://fave.ling.upenn.edu) instead.

### [Montreal Forced Aligner](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner)

This is a new forced aligner that I heard about for the first time at the 2017 LSA conference. It is fundamentally different than other ones in that it uses a software called Kaldi. I don't know much beyond that and I haven't used it yet (though I intend to soon).

### [Prosodylab-Aligner](http://prosodylab.org/tools/aligner/)

According to their website, this "is a set of Python and shell scripts for performing automated alignment of text to audio of speech using Hidden Markov Models." This is a software available through McGill University that actually allows you to train your own acoustic model (*e.g.* on a non-English audio corpus). I haven't done ths yet, but I've been meaning to start.

### [SPPAS](http://www.sppas.org/index.html)

This is a software package with several functions including forced alignment in several languages. Of the aligners you can download to your computer, this might be one of the easier ones to use. 

### [WebMAUS](http://clarin.phonetik.uni-muenchen.de/BASWebServices/#/services)

This is another web interface with multiple functions including a forced aligner for several languages.

### [Gentle](https://lowerquality.com/gentle/)

This advertises itself as a "robust yet lenient forced aligner built on Kaldi." It's easy to download and use and produces what appear to be very good word-level alignments of a provided transcript. It even ignored the interviewer's voice in the file I tried. The output is a .csv file, so I'm not sure how to turn that into a TextGrid, and if you need phoneme-level acoustic measurements, a word-level transcription isn't going to work. 


<br/>
## Miscellaneous

### [The great American word mapper](https://qz.com/862325/the-great-american-word-mapper/#int/words=dinner_supper&smoothing=3)

An interactive tool put together by Diansheng Guo, [Jack Grieve](https://sites.google.com/view/grievejw), and [Andrea Nini](https://andreanini.com) that lets you see regional trends in how words are used on Twitter.

### [Collecting, organizing, and citing scientific literature: an intro to Zotero](http://ideophone.org/slides-for-a-hands-on-zotero-workshop/)

Zotero is a fantastic tool for, well, collecting, organizing, and citing scientific literature. This is a great tutorial by Mark Dingemanse on the software and how to use it. I'm not exaggerating when I say that I literally could not write a paper if it weren't for Zotero. 

### [Pink Trombone](http://dood.al/pinktrombone/)

This is an interesting site that has a interactive simulator of the vocal tract. You can click around and make different vowels and consonants. Pretty fun resource for teaching how speech works.

### [Vulgar: A Language Generator](https://www.vulgarlang.com)

This site automatically creates a new conlang, based on parameters that you specify. The free web version allows you to add whatever vowels and consonants you'd like to include, and it'll create a full language: a language name; IPA chart for vowels and consonants; phonotactics; phonological rules; and paradigms for nominal morphology, definite and indefinite articles, personal pronouns, and verb conjugations; derivational morphology; and a lexicon of over 200 words. For $19 you can download the software and get a lexicon of 2000 words, derivational words, random semantic overlaps with natural languages, and the ability to customize orthography, syllable structure, and phonological rules. In addition to just being kinda fun, this is a super useful resource for creating homework assignments for students.

### [IPA Phonetics](https://itunes.apple.com/us/app/ipa-phonetics/id869642260?mt=8)

This iPhone app has what they call an "elaborated" IPA chart with lots of extra places and manners of articulation, complete with audio clips of all the sounds. You can play a game where it'll play a sound and you can guess what you heard. It's just fun to see things like a voiced uvular fricative (ɢʁ) or a dentolabial fricative [θ̼] on an IPA chart. Credits to University of Victoria linguistics and John Esling's "Phonetic Notation" (chapter 18 of the Handbook of Phonetic Sciences, 2nd ed.).

### [The EMU-webApp](https://ips-lmu.github.io/EMU-webApp/)

"The EMU-webApp is a fully fledged browser-based labeling and correction tool that offers a multitude of labeling and visualization features." I haven't given this enough time to learn to use it properly, but it seems very helpful.

### [Jonhannes Haushofer's CV of Failures](https://www.princeton.edu/~joha/Johannes_Haushofer_CV_of_Failures.pdf)

Other people have written this more elegantly than I could, but sometimes it's nice to see that other academics fail too. You're not going to get into all the conferences you apply for, your papers are sometimes going to be rejected, and you're definitely not getting all the funding you apply for. I find it therapeutic to put together a CV of failures like his researcher did and to keep it updated and formatted just as would a regular CV. Don't let impostor syndrome get in the way by thinking others haven't failed too.