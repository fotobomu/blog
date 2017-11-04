---
layout: post
title:  "Rebuilding an old project from the ground up"
author: "Geoff"
---

Back in 2012 I made a website for a client, Shawna Citron, a Psycho-Educational Consultant. The website itself was very simple: text-based static pages that conveyed the required information (i.e. about Shawna’s consultancy, her assessment practice, and contact details). I built the website using WordPress, but it was not responsive as I admittedly did not know about the Bootstrap framework back then.

<img src="https://raw.githubusercontent.com/fotobomu/blog/gh-pages/_assets/_images/_shawna/shawna-before.png" alt="Before Image">
_This is what Shawna's website used to look like. We all had to start somewhere, right? <a href="http://shawnacitron.com/">You can view the old website here</a>, but be warned, it's not pretty._

Since I have embarked on an adventure to strengthen my coding skills in earnest, I wanted to revisit Shawna’s website and rebuild it from the ground up. I took a mindful approach to the redesign: the information needed to be conveyed in a readable but engaging way.

<img src="https://raw.githubusercontent.com/fotobomu/blog/gh-pages/_assets/_images/_shawna/shawna-after.png" alt="After Image">
_Behold! Shawna's website after the rebuild. <a href="https://fotobomu.github.io/shawna-citron/" target="_blank">View it live</a>._

## Aesthetics

I wanted to keep things attractive yet simple. I chose a limited palate consisting of yellow/orange as the primary color, black text in the body, and grey boxes/horizontal rules. The main photo in the header was provided by Unsplash, photographed by Joanna Kosinska.

## Content Arrangement

Placing all the content on a single page (divided using sections) was a must. There was no reason to have separate pages for such a simple and light-weight website. However, I still added a navigation at the top that will collapse when viewed on mobile or when the window size is reduced.

On the original website the homepage has an unordered list of behaviors that a concerned parent may notice about their child. For the redesign, I used cards from the Bootstrap framework along with icons from Font Awesome. In doing so, the page feels more visually-balanced than it was before.

## Accessibility

Testimonials were provided by Shawna as scanned PDFs and images from her clients. On the original website they were displayed as images with no alt text applied (*gasp*). I know, this was poor practice on my part. But I have since learned to do far better, especially having worked directly with the Ontario Government in Web Accessibility. It was a main priority to take these testimonials and convert them to be readable. I used Bootstrap’s block quotes for this purpose.

## Areas of Improvement

I’m a firm believer that projects are iterative. Although this new website for Shawna is a huge jump from what it was before, there are still opportunities to improve the site. As I learn JavaScript I’d like to inject more functionality, such as having the cards highlight as you hover over them.

