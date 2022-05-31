---
layout: project_post
title: Wedding Website (VueJS exploration)
preview: images/wedding_cover.png
category: project
---

I'm getting married!! I'll also be joining Embark soon. I thought I'd explore some of their stack since they use an interesting mix of Express+Handlebars+VueJS before joining. Here's some of my exploration!
<!--more-->

[![nguyenandyang.com]({{site.url}}/images/wedding_cover.png)](nguyenandyang.com)

This was my second time building a personal website [see the HOA post!](http://tday.github.io/project/2016/06/15/edson-park.html)

I learned a lot since my first time between Barkly and other hacks I had put together. I quickly sketched up the page. Anna and I also went out and took engagement photos so we plenty of content. I wanted it to be simple with a clean design that was mobile responsive.

Top lessons learned:
1. Handlebars+VueJS is not a common mix. There's some hacks you need to put together to get it working together. This helps me understand the limits of this architecture as I keep the technical roadmap in mind.
2. Handleebars is pretty dead simple to use and easy to get going!
3. SSR is not dead despite the huge trend towards SPAs. I had forgotten the purpose of SSR until handlebars, but I can totally see why Embark made have usen it given they have data heavy models and several public facing pages for SEO.
