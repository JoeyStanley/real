---
layout: aside
title: Setup Instructions
redirect_from: 
    - "/setup"
---

# Setup Instructions

Thanks for your interest in one of my workshops. Please follow the steps below to get R and RStudio installed to your computer before the workshop starts. If you're having difficulty, please come a little early and I can help you out.

## Step 1: Get R installed

To download R, go to [https://cran.r-project.org/mirrors.html](https://cran.r-project.org/mirrors.html). This will take you to a list of CRAN mirrors. All these lists of sites are identical, they're just hosted on various servers across the world to handle the traffic. Just pick one near your current location and click on it. 

<img src="/images/screenshots/setup_mirrors_top.png" style="width: 85%;"/>
<img src="/images/screenshots/setup_mirrors_usa.png" style="width: 85%;"/>

From there, download the package appropriate for your computer. 

<img src="/images/screenshots/setup_download_both.png" style="width: 85%;"/>

Mac users will be taken to a screen where they'll give you various versions to choose from. At the time of writing, the latest package is 3.6.1, so go ahead and download that one and install it like any other piece of software. 

<img src="/images/screenshots/setup_mac.png" style="width: 85%;"/>

Windows users will have a link that says "install R for the first time" which will take them to the download page. You can then install R like normal.

<img src="/images/screenshots/setup_windows_first_time.png" style="width: 85%;"/>
<img src="/images/screenshots/setup_windows_download.png" style="width: 85%;"/>

I'm not entirely sure how to do it on a Linux, but I figure if you're using a Linux, you know what you're doing :)

## Step 2: Get RStudio installed

To download RStudio, go to [https://www.rstudio.com](https://www.rstudio.com) and click "Download" under RStudio. 

<img src="/images/screenshots/setup_rstudio.png" style="width: 85%;"/>

There are several intense versions of RStudio and we only need the free Desktop version, which is the one furthest to the left. Click the download button and then click on the link appropriate for your operating system.

<img src="/images/screenshots/setup_rstudio_top.png" style="width: 85%;"/>
<img src="/images/screenshots/setup_rstudio_both.png" style="width: 85%;"/>

## Step 3: Install some packages

Open RStudio. In the left-hand side, type the following commands and hit enter:

```
install.packages("tidyverse")
```

<img src="/images/screenshots/setup_install_packages.png" style="width: 100%;"/>

This will take a minute or so. This command installs a couple add-on packages that I frequently use in my workshops, including `ggplot2`, `dplyr`, `tidyr` and several others.

And that's it! See you at the workshop!

<br/>

<div class="nolink"><a href="/pages/r-workshops">« Back to the workshops page</a><div>