---
layout: single
author_profile: true
author: "Gidi Marcus"
title:  "Your blog/site hacked again? had enough with your 3rd party dependency? – we implement a content system you can trust!"
tags: [Blog,Website,static site,Jekyll]
---

At Hydro IT, when building a company front page, blog or any content system we usually recommend a “static” web page based on Jekyll.
There’re a few reasons for it, but the main ones are security, data and service ownership, performance, scalability and cost (it can even be free). 

## What is a “dynamic” site?
Most content or blogging systems uses a database system at the backend to store content. When a user accesses a webpage, it gets built by the server especially for that user – that what make the site being “Dynamic”. The components used for this process are also the ones that usually get hacked or becomes the performance and scalability bottlenecks.

## So what is that “static” site you recommend? 
In a “static” site approach instead of building the pages per-user-request using the database, we will be writing content to a simple text file (called MD), and will be using a back-end process to re-build the site upon any change to these files, and save the results so it ready to be served to the user immediately a plain HTML page.

Some will read this and immediately respond that this is “old school”, but it’s actually the opposite – this is “going back to basics” and eliminating redundant components that are the main security and scalability issues of today websites – but doing so in a modern and standardised way.

## How is the static page built?
As mentioned, we are deploying an open-source content management system called Jekyll, you can see [Here](https://jekyllrb.com/showcase/) examples to many enterprises and government sites built on this technology.
The different text files (MD files and config files) are saved in the site folder. Upon uploading them to a Jekyll-compatible code repository provider (such GitHub) or running a command locally, the site get built in less than a minute and pushed automatedly or manually to a hosting provider ready to be served.

## Where can it be hosted?
We will most likely start by recommending hosing it in GitHub, it’s free, provide 1GB of storage and up to 100GB bandwidth a month, it comes with a built-in “Let’s encrypt” SSL certificate with automatic renewal service, It has version control, user delegation with 2FA and more.
If the free option exhausted or not fit-for-purpose, we can front it with free or paid for CDN service, or offload it to scalable GitHub integrated service like Azure Pipeline, AWS CodeBuild or Google Cloud Build – or even all three for high availability.

## What can’t we do with it?
Since there is no database at the backend, we can’t store any user content or data with it, can’t process sales transaction (in a built-in way) and we can’t block or really hide any content from users – the entire site is technically open to everyone. Having said that, there’s many 3rd party tools – some already integrated in Jekyll to provides some services, such comments, user statistics, social media sharing functionality and others… and you can always link to an external system or plug-in to do these tasks while keeping your front page highly available, fast performing and secure. One more thing you don’t get with it is a built-in reach text editor, instead, you’ll be editing text files in a format called MarkDown (MD), which is very similar to how Wikipedia pages are written. You can see the example of this page MD file [here](https://raw.githubusercontent.com/MGidi/gidi.hydroit.co.uk/master/_posts/2020-01-08-Jekyll-website-deplyment-service.md). We promise – it’s much easier than it first seems. There some software available to help with it, and tools to migrate and even live integrate with WordPress.

## Why others not offering this service, and what the added value Hydro IT bring?
It’s much more common to see providers offering WordPress or WIX sites, there’s two reasons for it:
First – it’s the standard, it comes with an easy editor that content admins know and comfortable with.
Second – it’s more profitable - it billed along with a monthly hosting, maintenance and ad-hoc support.
With Jekyll and the integration service we provide – the site is yours from day 1. We do not hold any key, password or information for it – we just have access to a free GitHub repository you own, and to the domain register site. Both are access that you can revoke at any time.
We will also not charge you any annual or monthly fee, but only charge per request and time invested in building or changing the site.

## Who will design the site?
Jekyll has hundreds of themes - free and paid for, you can browse them through the [Jekyll official site](https://jekyllrb.com/resources/). And we can help with customising the functionality, and to liaise with a graphic designer to edit the design itself or to create a complete new one. 

### If you want to read more about the Jekyll philosophy - [click here](https://jekyllrb.com/philosophy/)
