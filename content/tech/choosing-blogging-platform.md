---
title: "Comparing Blogging Platforms: Gatsby, Ghost, Hugo, Hashnode"
date: 2023-08-25T13:18:34+05:30
draft: false
---

After months of exploring various tools, I finally settled down on a tool and started my blog. This article covers my experience using various tools and hopefully, my experience will help you choose your blogging platform more quickly.

## Gatsby

Since Gatsby was popular for its fast page load speed and SEO capabilities decided to give it a try. I found a theme that I liked, cloned that repo and tried to build it locally myself. But couldn't build it due to multiple npm dependency installation issues. That repo wasn't updated and maintained for a long time, which was probably causing the issue. I tried fixing it myself but somehow couldn't.

I went online and found a recent fork of the theme that had fixed the npm issue, so I forked that repo, added my data, deployed it and finally the website was up and running. Even though the website was a simple one-page portfolio, I was amazed at why I would get npm issues while creating a simple static website.

This was probably due to the fault of the theme and not Gatsby itself, but I decided I wanted to go away from js related frameworks and try something else.

## Ghost

As I started searching for alternatives, I stumbled upon [Karan Sharma's blog](https://mrkaran.dev/), built using [Ghost](https://ghost.org/). The simplicity and elegance of the blog immediately caught my attention. Intrigued, I decided to try out Ghost. I must say, it's an incredible SaaS tool. Extremely user-friendly, quick, and packed with a multitude of features but... It's a paid platform.

As I was still in the exploration phase and unsure about my commitment towards maintaining a blog, I decided not to invest in Ghost at that point. There was an option to self-host Ghost, but I wanted an even simpler option.

## Hugo

So, I finally turned my focus towards Hugo, a platform I had long been eyeing. Found a nice theme: [hugo-blog-awesome](https://github.com/hugo-sid/hugo-blog-awesome). The build time was extremely fast, and since it's a static site generator, performance was great. But modifying Hugo's theme to your exact needs means cloning the theme in your repo and kind of creating a fork of the theme. You have to maintain that fork as the bug fixes and features added to the original theme won't reflect in your repo.

The blog is available here: [https://vedant-mhatre.github.io](https://vedant-mhatre.github.io/)

As I didn't want to go through the entire effort of tweaking the theme, managing CDN for storing the large images I would use in my blog, and implementing a search function (which searched the post content and not just the title and tags) because this theme didn't provide it, I decided to try out something else.

## Hashnode

Finally found Hashnode which had multiple features, perfectly suited to my needs:

1. Good search button, which searches the text of the post as well
2. Caching by default for everything, especially images
3. Nice & simple web editor (didn't want to edit markdown files)
4. Every article is shared with Hashnode's dev community (Bonus)
5. In-house newsletter service (Bonus)

Also, there were option managed options like [dev.to](https://dev.to/) and [Medium](https://medium.com/), but I wanted my articles to be free to read for everyone, didn't want annoying paywalls/ads and wanted to have a blog on my personal domain, hence I didn't try them out.

## Conclusion

I am going to use Hashnode as my primary blog and have [the hugo blog](https://vedant-mhatre.github.io) as my backup, but won't be actively maintaining and improving it.

Let's see how this new blog turns out and subscribe to my [newsletter](https://vedant-mhatre.hashnode.dev/newsletter) to stay updated!
