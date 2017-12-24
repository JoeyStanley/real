---
layout: resources
title: Resources
toc: false
---

# Resources

This page is mostly under construction still but will eventually be a central place for all things useful for other linguists. It'll  list software I've found useful, book recommendations, and links to resources I've developed and other helpful pages I write. For now, I can list a couple things. 


<br/>
## My handouts

### [R Workshops](/pages/r-workshops.html)

I'm currently giving a series of workshops on how to use R which will include a variety of topics. I have included PDFs and additional information on each installment of this series.

### [Excel Workshop](/excel.html)

I recently gave a workshop on Microsoft Excel in the main library at UGA. It was very well-attended and included graduate students and faculty from a variety of areas in the humanities and social sciences. I normally wouldn't link to just a blog post, but this one does do a good job at summarizing the main points and has the content available for download.

<!--
### MANOVA

In the study of vowel overlaps, we use the Pillai score, which is an output of the MANOVA test. Well what is the MANOVA test anyway? In this extended post (forthcoming), I'll go into detail about the math behind the test and, more importantly for linguists, the assumptions that your data should meet before running it.
-->

<br/>
## R Resources

Here is a list of resources I've found for R. I've gone through some of them and others are on my to-do list. These are in no particular order. 

* The website for [Tidyverse](https://www.tidyverse.org) is a great go-to place for learning how to use `dplyr`, `tidyr`, and many other packages.

* *[R for Data Science](http://r4ds.had.co.nz/index.html)* by Garrett Grolemund & Hadley Wickham is a fantastic overview of tidyverse functions. 

* *[Intro to Tidyverse](http://varianceexplained.org/r/intro-tidyverse/)* by David Robinson. 

* *[Advanced R](https://adv-r.hadley.nz)* by Hadley Wickham with the [solutions](https://bookdown.org/Tazinho/Advanced-R-Solutions/) by Malte Grosser, Henning Bumann, Peter Hurford & Robert Krzyzanowski.

* *[R Packages](http://r-pkgs.had.co.nz)* by Hadley Wickham.

* *[Hands-On Programming with R](https://d1b10bmlvqabco.cloudfront.net/attach/ighbo26t3ua52t/igp9099yy4v10/igz7vp4w5su9/OReilly_HandsOn_Programming_with_R_2014.pdf)* by Garrett Grolemund & Hadley Wickham for writing functions and simulations. Haven't read it, but it looks good.

* *[ggplot2](http://www.springer.com/us/book/9783319242750)* by Hadley Wickham is a comprehensive resource for learning all the ins and outs of ggplot2.

* *[Text Mining with R](http://tidytextmining.com)* by Julia Silge & David Robinson. Haven't read it, but it looks great.

* *[Elegant, flexible, and fast dynamic report generation with R](https://yihui.name/knitr/)* by Yihui Xie is a great resource for RMarkdown.

* *[bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)* by Yihui Xie. See an introduction to Bookdown by RStudio [here](https://www.rstudio.com/resources/webinars/introducing-bookdown/).

* *[Visualizing text data with ggplot2](https://github.com/ColinFay/conf/blob/master/2017-11-budapest/fay_colin_text_data_ggplot2.pdf?utm_content=buffer56bdc&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)* by Colin Fay. 

<br/>
## Statistics Resources

* *[Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing](https://www.autodeskresearch.com/publications/samestats)* by Justin Matejka and George Fitzmaurice. This went viral in some circles and shows that you can get the exact same summary statistics with wildly different distributions. Very cool. 

* *[Studying Pronunciation Changes with gamms](http://jofrhwld.github.io/papers/edinbr_gamm/)* by Josef Fruehwald.

* *[Generalised Additive Mixed Models for Dynamic Analysis in Linguistics: A Practical Introduction](https://arxiv.org/pdf/1703.05339.pdf)* by Márton Sóskuthy.

* *[Overview GAMM analysis of time series data](http://jacolienvanrij.com/Tutorials/GAMM.html)* by Jacolien van Rij. I haven't had time to go through this one yet, but it's on my todo list. Actually [all of her tutorials](http://www.jacolienvanrij.com/cv.html) look great.  


[//]: # ## Quantitative People
[//]: # * [Josef Fruehwald](https://jofrhwld.github.io)
[//]: # * [Daniel Ezra Johnson](http://www.danielezrajohnson.com)
[//]: # * [Bradley T. Rentz](https://rentzb.github.io/#talks)
[//]: # * [Margaret E. L. Renwick](http://faculty.franklin.uga.edu/mrenwick/)

<br/>
## Praat Resources

[Will Styler's](http://savethevowels.org/will/) Praat tutorial is probably the most thorough I've seen. The PDF can be found [here](http://savethevowels.org/praat/UsingPraatforLinguisticResearchLatest.pdf) but don't forget to look at the [page](http://savethevowels.org/praat/) it comes from which has more information about it. 

*[Phonetics on Speed: Praat Scripting Tutorial](http://praatscripting.lingphon.net)* by Jörg Mayer is what I find myself coming back to again and again.

[University of Washington Phonetics Lab](https://depts.washington.edu/phonlab/resources.htm) has tutorials and scripts.

And I've written a [tutorial](/blog/a-tutorial-on-extracting-foramnts-in-praat) on writing a script for basic automatic formant extraction. 


<br/>
## Forced Aligners

### [DARLA](http://darla.dartmouth.edu)

This is my personal favorite. It's actually a whole collection of tools available through a web interface from Dartmouth University. It can transcribe, align, and extract formants from your (English) audio files all in one go. Its forced aligner is built using Prosody-Lab (see below) and is pretty good in my experience. 

### [FAVE](https://github.com/JoFrhwld/FAVE)

This probably the most well-known forced aligner. It's open source and you can download it on your own computer from [Joe Fruehwald's Github page](https://github.com/JoFrhwld). Or if you'd prefer, you can UPenn's their [web interface](http://fave.ling.upenn.edu) instead.

### [Prosodylab-Aligner](http://prosodylab.org/tools/aligner/)

According to their website, this "is a set of Python and shell scripts for performing automated alignment of text to audio of speech using Hidden Markov Models." This is a software available through McGill University that actually allows you to train your own acoustic model (*e.g.* on a non-English audio corpus). I haven't done ths yet, but I've been meaning to start.

### [Montreal Forced Aligner](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner)

This is a new forced aligner that I heard about for the first time at the 2017 LSA conference. It is fundamentally different than other ones in that it uses a software called Kaldi. I don't know much beyond that and I haven't used it yet (though I intend to soon).

### [SPPAS](http://www.sppas.org/index.html)

This is a software package with several functions including forced alignment in several languages. Of the aligners you can download to your computer, this might be one of the easier ones to use. 

### [WebMAUS](http://clarin.phonetik.uni-muenchen.de/BASWebServices/#/services)

This is another web interface with multiple functions including a forced aligner for several languages.


<br/>
## Miscellaneous


### [Pink Trombone](http://dood.al/pinktrombone/)

This is an interesting site that has a interactive simulator of the vocal tract. You can click around and make different vowels and consonants. Pretty fun resource for teaching how speech works.

### [Vulgar: A Language Generator](https://www.vulgarlang.com)

This site automatically creates a new conlang, based on parameters that you specify. The free web version allows you to add whatever vowels and consonants you'd like to include, and it'll create a full language: a language name; IPA chart for vowels and consonants; phonotactics; phonological rules; and paradigms for nominal morphology, definite and indefinite articles, personal pronouns, and verb conjugations; derivational morphology; and a lexicon of over 200 words. For $19 you can download the software and get a lexicon of 2000 words, derivational words, random semantic overlaps with natural languages, and the ability to customize orthography, syllable structure, and phonological rules. In addition to just being kinda fun, this is a super useful resource for creating homework assignments for students.

### [IPA Phonetics](https://itunes.apple.com/us/app/ipa-phonetics/id869642260?mt=8)

This iPhone app has what they call an "elaborated" IPA chart with lots of extra places and manners of articulation, complete with audio clips of all the sounds. You can play a game where it'll play a sound and you can guess what you heard. It's just fun to see things like a voiced uvular fricative (ɢʁ) or a dentolabial fricative [θ̼] on an IPA chart. Credits to University of Victoria linguistics and John Esling's "Phonetic Notation" (chapter 18 of the Handbook of Phonetic Sciences, 2nd ed.).