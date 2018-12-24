---
layout: post
title:  "Prevelar Raising Survey Results"
date:   2018-12-24 08:59:00 -0400
tags: [Side Projects]
---

In April and May this year, posted a survey to a bunch of different subreddits that asked people how they pronounced certain words. If you took the survey, THANK YOU! The number of responses I got was overwhelming and took *much* longer to analyze than I could have ever anticiapted. So, after many months, I'm finally happy to post the results for you. Hopefully you'll find them intersting.

TL;DR I asked a bunch of people how they pronounced words that rhyme with *bag* or *beg*. Basically, people from the northern US and Canadians tend to pronounce them with the same vowel as the word *bake*. Also, if you do though, it's less likely in longer words. 

# Background

In case you haven't noticed, not everyone speaks English the same way. And that's okay! Linguists like me study these differences between people and we can learn a lot about language and society when we do so.

The specific thing I was interested in was how people pronounce specific vowel sounds when they come before a *g*---linguists call this this "prevelar raising." A bunch of words in English, something like 84 of them, have this "agg" sound in them. Words like *bag*, *sag*, *flag*, *rag*, *dragon*, and *aggravate*. For shorthand, I'll refer to this group of words as the "<span style="font-variant:small-caps;">bag</span> words." Most English speakers from North America pronounce that vowel the same as a word like *back* (the "short *a*" sound). Well, as it turns out, there are some people that pronounce these words with the same sound as *bake* (the "long *a*" sound). I'll call this phenomenon *<span style="font-variant:small-caps;">bag</span>-raising*. Linguists have found that this <span style="font-variant:small-caps;">bag</span>-raising generally occurs in Canada and a lot of US states that border Canada. 

So then there's another set of about 60 words that have this "eg" sound in them, like *beg*, *egg*, *leg*, *keg*, *legacy*, and *integrity*. I'll call this group of words the "<span style="font-variant:small-caps;">beg</span> words." Most English speakers pronounce this with the same sound as *deck* ("short *e*" sound). But, some people (like me) pronounce some or all of these words with the same vowel as *bake* (the "long *a*" sound). But unlike <span style="font-variant:small-caps;">bag</span>, we don't really have a great idea of where in the country people do this. 

So what better way to find out than to ask several thousand people, right?

# How did I do this?

<span class="sidenote"><a href="https://ugeorgia.ca1.qualtrics.com/jfe/form/SV_2lqEd8yULAUDoQB">If you want to take the survey yourself, click here!</a></span>
So several months ago, I picked several dozen <span style="font-variant:small-caps;">bag</span> and <span style="font-variant:small-caps;">beg</span> words and created a survey that asked people how they pronounced each one. Basically, people saw a word and were asked whether it sounded more like *bake*, *deck*, or *back*. 

I then went to the subreddit dedicated to each US state and Canadian province and territory and asked the moderators if I could post a survey. Almost all of them said yes. So with a dedicated Reddit account ([/u/dialectologist](https://www.reddit.com/user/Dialectologist/)), I went ahead and posted it on about those 60 subreddits. 

And tons of people took the survey! Almost 7,000! And from these responses I got around 567,000 individual survey questions answered. This was like ten times more than what I expetected. Super cool.

When I was processing these responses though, I wanted to find a way to turn them into numbers. So what I did was every time people answered *bake*, that was a 1. Every time they answered *deck*, that was a 0. And every time they answered *back* I gave them a --1. I then took all the responses for a person's <span style="font-variant:small-caps;">beg</span> words and averaged them to get their "degree of <span style="font-variant:small-caps;">beg</span>-raising." Same thing for their <span style="font-variant:small-caps;">bag</span> words to calculate their "degree of <span style="font-variant:small-caps;">bag</span>-raising." I also turned it the other way and calculated each word's score by averaging all the responses across all people. 

So basically, I have three numbers now. For each person, I have their "degree of <span style="font-variant:small-caps;">beg</span>-raising" and their "degree of <span style="font-variant:small-caps;">bag</span>-raising." For each word, I now have how often that word was "raised."

Finally, to get people's location, I took the responses they wrote down on the question that asked "where are you from" and found the GPS coordinates of that city.

Now, on to the results!

# General Results

## **<span style="font-variant:small-caps;">bag</span>** words

I'll start with the <span style="font-variant:small-caps;">bag</span> words. As I said before, <span style="font-variant:small-caps;">bag</span>-raising generally occurs in Canada and in the northern US. Here's a map of what I found in my survey:

<a href = "/images/plots/ads2019_bag_raising_map.jpg" class = "nodot"><img width = "100%" src="/images/plots/ads2019_bag_raising_map.jpg"/></a>

In this map, darker, bigger circles represent people who had more <span style="font-variant:small-caps;">bag</span>-raising while smaller, white circles are for those that had less. So my survey results were pretty much what I expected based on existing linguistic research.

However, sometimes people had <span style="font-variant:small-caps;">bag</span>-raising on some words but not on others. Were there any sort of patterns? Here's a colorful plot that puts the <span style="font-variant:small-caps;">bag</span> in order of how much they were raised, with *Volkswagon* sounding like *bake* or *deck* the most often and *Mary Magdalene* the least. 

<a href = "/images/plots/bag_raising_plot.pdf" class = "nodot"><img width = "75%" src="/images/plots/bag_raising_plot.jpg"/></a>

In this chart, each word is on its own row. Within that row, the width of the red box is the number of people that indicated that they say that word with the same vowel as *bake*. Yellow is "somewhere between *bake* and *deck*". The small green ones are *deck* and the blue ones are *back*. Purple are where people said it had some other vowel. This chart shows that not all <span style="font-variant:small-caps;">bag</span> words are equally likely to be pronouced the same, but the difference between the *Volkswagon* at the top and *Mary Magdalene* at the bottom is admittedly not that huge. 

So now lets turn our attention to the <span style="font-variant:small-caps;">beg</span> words. 

## **<span style="font-variant:small-caps;">beg</span>** words

So <span style="font-variant:small-caps;">bag</span> words are cool and all, but a lot less research has been done on <span style="font-variant:small-caps;">beg</span> words. This was the main thing I wanted to find out: where do people have <span style="font-variant:small-caps;">beg</span>-raising and what <span style="font-variant:small-caps;">beg</span> words are more (or less) likely to be raised? 

To answer the first question, here are the results on a map:

<a href = "/images/plots/ads2019_beg_raising_map.jpg" class = "nodot"><img width = "100%" src="/images/plots/ads2019_beg_raising_map.jpg"/></a>

Again, darker, bigger circles represent people who said more <span style="font-variant:small-caps;">beg</span>-words had the same vowel as *bake* while smaller, white circles are for those that said it was more like *deck*. So this shows that you'll hear people pronouncing <span style="font-variant:small-caps;">beg</span> words like *bake* at least some of the time pretty much everywhere but the South. Linguists already kinda knew this happened in the Pacific Northwest, but the fact that it's in pretty much all Western and Midwestern states (especially in that stretch from Illinois to Pennsylvannia) was news to me.

Just as surprising was the following plot which shows how often <span style="font-variant:small-caps;">beg</span> words were raised:

<a href = "/images/plots/beg_raising_plot.pdf" class = "nodot"><img width = "75%" src="/images/plots/beg_raising_plot.jpg"/></a>

Here, we see that there's a major difference between the top and bottom of the chart. Okay so technically, words like *vague*, *pagen*, *plague*, and *fragrant* don't belong on this chart because pretty much everyone would pronounce them with a "long *a*" sound. I'll ignore this for now. But even between words that are spelled with *eg*, there's a big difference between them. A word like *segregate* is said with the same vowel as *bake* less than 10% of the time. But a word like *egg* is almost 20% and *omega* is almost 40%. And, if you look closely, most of the words towards the bottom all have consonats following the *g*---*integrity*, *segment*, *pregnant*. That's pretty interesting if you ask me.

## Both in one map

When you combine the two maps, you can start to see where one vowel is pronounced like *bake* and the other is not. Here, green areas are those that have <span style="font-variant:small-caps;">bag</span>-raising but not <span style="font-variant:small-caps;">beg</span>-raising and purple are areas with <span style="font-variant:small-caps;">beg</span>-raising without <span style="font-variant:small-caps;">bag</span>-raising. 

<a href = "/images/plots/ads2019_combined_map.jpg" class = "nodot"><img width = "100%" src="/images/plots/ads2019_combined_map.jpg"/></a>

Basically, the whole reason I did this survey was to produce this map. I wanted to see if there would be purple areas without green and green areas without purple. And there are!

# Conclusion

Again, if you took the survey, a *huge* thank you. I've had a lot of fun playing with this data, and it has been interesting to read the your comments on Reddit and in the survey. 

If you're a linguist and want to learn more, feel free to look at the poster I did at [NWAV](/NWAV47) this year and if you'll be at LSA you can see me present Friday morning in the ADS sessions.
