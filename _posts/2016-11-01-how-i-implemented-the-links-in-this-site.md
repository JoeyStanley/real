---
layout: post
title:  "How I Implemented the Links in this Site"
date:   2016-11-01 18:53:00 -0400
tags: [CSS, how-to guides, this site]
---

A while ago I stumbled across [Butterick's Practical Typography](http://practicaltypography.com). I've never been *that* into typography, but I do make sure my documents look good. I've yet to implement good typography into this webpage, but I did find a neat trick that I was able to implement.

Hyperlinks traditionally are in blue and underlined. Everyone's used to it though so we don't notice. In Butterick's book though he has linked text the same color and style as the rest of the page, but there's a little red circle after it, as if it was a link to a footnote or something. It's a pretty clever way to soften the look, but still get the point across that that particular text is a link.

I like to write stuff with links everywhere. I figure it might save people a google search if I just do it for them. On my CV, I link readers to the PDF and other documents, my co-authors' pages, and other pages that might be useful. The result though makes it look like Wikipedia, unless I can find a way to soften how links look.  

Thanks to some CSS skills I've been learning from Lynda.com, I've found out that I can add those little red circles by adding this to my `.css` file:

~~~~
a[href*="http"] {
	color: black;
}
a[href*="http"]:after {
	content: 'º';
	color: darkred;
}
~~~~

What the first block does is it targets just the `<a>` tags that contain an `href`, meaning they're an external link, and it changes the color to black, as opposed to the blue from an earlier block. From there, the `:after` selector in the next block puts text after the text in the tag every time. I may need to change some things later to make sure it does exactly what I want on all the pages, but it works for now.

I don't know if I'll keep it the way it is, but it does look a lot better than tons of blue underlined text.