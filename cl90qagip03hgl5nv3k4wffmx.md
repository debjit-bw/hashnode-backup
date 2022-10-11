# 6 lessons from coding and deploying my portfolio in under 30 mins

# TL;DR

Go look: [debjit.dev](https://debjit.dev) (. ❛ ᴗ ❛.)

# Why the urgency?

After buying the domain, I initially redirected it to a quick and easy Wix site. Since I was on the free plan, there was the Wix branding at the top. Worse, they didn't let me hook up my custom domain.

Now I always have a bunch of planned projects and learning missions going on. I was busy with two other projects when I saw a mild increase of visitors to my [debjit.dev homepage](https://debjit.dev)

Last week I put up my domain's link up on a bunch of socials, and I saw a mild increase in the traffic. The 302 redirect combined with it taking visitors outside my domain was getting too much to handle.

# Initial scramble

My initial plan was to build a whole web app using React. But as the situations unfolded, I was willing to settle for another quick and easy solution. I decided to go with classic HTML, CSS, JS. They never disappoint.

I didn't have time to build a whole site from scratch. I will do that, but later. When some of my current priorities are done and dusted. I rummaged through some template sites on GitHub. They were either disappointing, had bad design, or the code was not free.

I thought about using Figma or Canva and then exporting it to HTML. But that won't be responsive. I decided to use some WYSIWYG html editor to do it quick, and was almost about to start, until...

# I searched on YouTube

And [this video](https://www.youtube.com/watch?v=u-RLu_8kwA0) came up. As you can see, the title is `How to Create & Host a Portfolio in 10 minutes with GitHub pages!` and the video duration is `13+` minutes. So, scam.

Not really, it gave me the perfect idea and resources to work with. [html5up.net](https://html5up.net/) has a variety of very basic templates, and I totally forgot about [GitHub Pages](https://pages.github.com/). Else, I would have gone for something like Firebase Hosting, but with GitHub pages, a lot of burden was reduced.

# Settling with the technologies

* Tech: Simple HTML, CSS, JS
* Template: [Spectral](https://html5up.net/spectral)
* Hosting: GitHub Pages

# Editing the template

Now comes the main part. What I want my portfolio to look like. I want my latest blog post or major project to take the center stage. So the main page background and image needs to be changed to that. For this, I wanted to use the DALL·E 2 post. But that hasn't been published at the time of writing this. So I will just go with the [very first blog](https://blog.debjit.dev/so-i-really-begin-writing).

# This is time taking

Writing details about every single thing I did to make the site is both time consuming, and boring. Rather, I'd list out what I learnt from the experience. Sort of a lessons journal, what this blog is always meant to be.

## 1. Never start from scratch

As a developer, when you are searching for a template, and aren't finding one, you will be tempted to write the whole project from scratch. Never listen to it. Even if some project is mildly ~ barely similar, fork/copy it and go from there. Don't steal code. Only copy if it's open sourced, and give the proper attributions.

This makes things much faster, especially for a site. That's because writing and perfecting CSS styles or JS animations is very time consuming o frame from inception. Modifying an existing script is a lot easier.

## 2. Speaking of CSS

It's a mess. The spiderwebs of `before`s, `hover`s, `.` & `>` notations and an unending thread of indentations will take a serious toll on your mental health if you are not careful enough.

Not once, and not just twice has it happened to me that just changing padding in one place messed up the alignment of entire groups of elements. Finding which particular CSS attribute affects which nested element is a feat in itself.

Soon, after plenty trial and error of finding attributes, I gave up manually searching. I simply opened it in Chrome and did inspect elements to find out the proper CSS tags. I started writing custom CSS after getting some idea from Stack Overflow.

Generally I learn things as I go, seeing codes and through trial and error, before reading the technicalities on how they work. CSS is one of those fields in which I wouldn't recommend taking that approach.

## 3. Use services where you can connect your own domain

Using your own domain has several benefits. First, you get to keep all the SEO. Second, you get to use it however you wish, can deploy as many revisions as necessary. The autonomy of using a custom domain is hard to compete with.

It also adds authenticity when people see the address bar. It's easier to discover, memorable and acts as  your personal brand. That's one of the big reasons I did not start blogging on dev.to, and the same reason for shifting over from a Wix site to simple HTML page on my own domain.

## 4. Compress your assets

When I first deployed the site, it felt great. But when I shared it with some friends, they complained that it was taking an extremely long time to load. Again, this problem didn't happen to me...until I visited the site in an incognito tab.

One of the images I used on the banners was 1.78 MB in size.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664727192941/B8tEfnwDr.png align="left")

I didn't feel the extra load time because it was either loading from local, or Chrome cached it on first load. These kinds of hidden bottlenecks can leave a bad impression on site visitors and can affect your page rankings on search engines.

## 5. Less design is more design

I am not a designer. Far from, in fact. But of course I can have an opinion about it on the internet.（︶^︶）

The initial template had bright colors and several elements cluttering the viewport. Once I changed elements into dark shades and removed the extra clutter, things began to look much better.

The art of design isn't what more to add. It's often figuring out everything you can remove to keep only the things you care about the most.

Speaking of design, don't ignore mobile visitors to your site. Keep it responsive so that it adapts to laptop and mobile screens. We have become mobile-first, and even Google demotes sites on mobile browsers which aren't mobile friendly.

## 6. Set up CI/CD, you won't regret it

GitHub Pages has its own CI/CD pipeline built in. So I can commit and push changes, and GitHub will automatically build and deploy my site.

In case you are not using GitHub Pages, it would be a worthy investment to create a CI/CD pipeline using Travis CI, Circle CI or some other tool. It reduces the burden by magnitudes, and makes deployments as easy as simply committing your changes.

## 7. Register your domain on the Google Search Console

It manages indexing the contents of your page, and showing it on search results. If you want your portfolio to come up first, when people search your name on Google, you should request indexing of your page on the [Google Search Console](https://search.google.com/search-console).

It also comes with several other helpful tools, such as measuring your website loading time and how you can improve it, etc.

# Happy making

I think that covers most of my struggles while making my portfolio. I would be more than happy if this is useful even to just 1 person.