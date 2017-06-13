---
title       : "How I stopped trying to remember the rules."
author      : "Jake Bowers" 
date        : "13 June 2017"
subtitle    : "...in statistics." 
job         : OES Nugget of Knowledge 2017
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

<!-- This uses the http://slidify.org/ package for R markdown because I thought I'd have R in it -->

<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## In statistics each rule is general but each design is specific

**Some recent questions:**

- "How many observations do I need to use logit with this data set?"

- "If I use robust standard errors with these data will my confidence intervals be ok?"

- "Don't I have to control for education and income in my linear model analysis of this randomized experiment?"

- "Isn't the wild bootstrap better than robust cluster standard errors or multilevel models for this design?"

---

## In statistics each rule is general but each design is specific **so drive decision with design.**

 
 > - **How** did I do the design? If I repeated the design, and I knew the truth, how often would my proposed behavior mislead me and my audiences? 
 
 > - **Corollary 1:** If I know *why* I made the design in this way, I can fine tune my choices. How does the **substantive** output from my proposed action advance the policy or theory goals that drove the design? (i.e. Regardless of misleading standard errors, p-values or confidence intervals: Do I want the kind of weighting implied by a multilevel model? Do I want to summarize my experiment in terms of differences in potential log-odds? Or differences of means or proportions?)

 > - **Corollary 2:** If the design was _not_ randomized, what I am thinking about when I calculate a standard error or a p-value (both require some notion of "it could have been otherwise")? This mental design can stand in for actual design. (i.e. If we had an experiment in this case, what would have been randomized and thus repeatable?)






