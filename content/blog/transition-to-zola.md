+++
title = "Transition to Zola"
date = 2021-02-24
+++

Summary: The site has been transitioned from Jekyll to Zola, read about the decision here!
<!-- more -->

Hello! If by some miracle you saw my site in the past couple of months, you'll notice that it looks quite different now, and that it maybe doesn't look quite so refined. I actually agree, but I think this is going to be better for my development of this site in the future. I've transitioned the site from [Jekyll](https://jekyllrb.com/) to [Zola](https://www.getzola.org/) because I don't want to install Ruby, a language which I have never used on each machine that I want to work on. As a plus, Zola and Tera, the templating language that Zola uses, are both written in Rust, a language that I have been interested in for months. If I come across bugs or missing features, I'll have an excuse to finally learn Rust for good and add some contributions.

The downside is that Zola is nowhere near as popular as Jekyll, so documentation and resources are far more scarce as well. The documentation on the official site is good enough for most things I want to do anyway, though, and I've found that the live reloading feature actually works better than on Jekyll. 

I will sorely miss the robust themes that were provided by the Jekyll community, though, as almost all of the Zola themes I've found have been lackluster (what is that red header text??). In the end, though, those kinds of things are customizable, unlike the naming requirements on pages that Jekyll forces you to use. Each page needs to begin with a date, which doesn't work great in an editor sidebar, since there's a good chance the full title will end up being cut off in the narrow column of space.

Overall, Zola feels much more straightforward to use when compared to Jekyll because it's just an executable and doesn't use the Ruby development pipeline, which I'm not familiar with. I wanted to make this change early so that there wouldn't be much content that I'd have to transfer over. Who knows, maybe I'll end up switching back if trying to get the front-end design ends up being too frustrating to get right, but for now I'll stick with Zola.