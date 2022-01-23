---
layout: post
title: "Free alternative to GSuite"
date: 2022-01-23 22:50:21 +0200
categories: services
---

Google closes GSuite and from now all accounts will be transferred to Google Workspace, and therefore will cease to be free. Many people used GSuite only because it was a free service and you could connect your own domain to it. Probably some of you have asked yourself what to do in this situation - buy a paid account or look for another solution.

If for some reason you don't want to pay for Workspace, I am here to help. You can look for other email provider that allows you to connect your own domain. I used to use Yandex mail - but some emails ended up in spam, so I gave up. This time I would like to use GMail so I decided to use an alias. I just need to put a contact on the website and it's nice if it's on the mayann.app domain. I know that if I answer an email, it will be from the GMail domain, but that is not so important to me.

This solution gives me all the advantages of GMail and I use my domain. This is definitely not a perfect solution, the message passes through additional servers, so someone can know the content of the email and we are addicted to this intermediary. However, this does not discourage me, initially I used [improvmx.com](https://improvmx.com/) and everything worked great, but after some time I decided to move to Cloudflare for two reasons - it is a large company, so there is less risk of a failure and I have everything in one place. Both sites are free, so you can try them out and choose a better solution.

Setting up [Cloudflare Email Routing](https://developers.cloudflare.com/email-routing/enable-email-routing) is easy. You enter the alias and the address to which the email will be redirected, and basically that's it.

![Cloudflare Email Routing page screenshot](/assets/images/cloudflare_email_routing.png)

This is an article from the series on how to maintain an indie startup at a minimum cost, in the next episode I will write how I keep a blog for free. Everything I write about is tested on my [random data generator](https://mayann.app) indie startup.

##### #shortAndToThePoint
