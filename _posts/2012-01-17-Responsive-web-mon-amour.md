---
layout: post
title:  "Responsive web, mon amour"
description: "A 2012 account on my approach to responsive web design. Old, inaccurate, but the heart is in the right place."
date:   2012-01-17
categories: responsive-web
tags: [responsive web, media queries]
---
_One for all and all for one... stylesheet!_

Recently I have been developing few websites (including this one) with mobiles in mind.
More and more often users are accessing websites through all sort of devices, desktops, laptops, mobiles, tablets.

The first approach back in the time when CSS wasn't yet the magic and powerful tool that is today, was to develop two different websites: one for standard screens and one for mobile phones. Javascript was handy to detect the users' device type and point it to the right URL.
This technique is still in use and it's pretty useful in several occasions, such as offering products and services limited to specific device users. It also has the advantage to let the user download only what he needs: no extra CSS, no extra queries to pick the right size of images, etc.

That said, with CSS3 and the <a href="http://www.w3.org/TR/css3-mediaqueries/">@media queries</a> the joy of writing a stylesheet for a fluid and slick website has increased exponentially.

The idea that your layout moves and adapt before the user's eyes is fascinating.

As you always do, you will decide what's more important, what deserves the top space and what can be sacrificed and will go `visibility: hidden;`.

What I love about responsive web design is that you will worry a lot less about pulling out the right content, as it will be decided once (and for all) at the beginning of the project and displayed via CSS only. No need to interrogate your database for once.

Sure it will require more attention to details while writing your stylesheet and a lot more ahead thinking when designing the layout, but less maintenance once the website will live its own life.

If you want to know more about responsive web design (RWD) then I'd suggest this <a href="http://thinkvitamin.com/design/beginners-guide-to-responsive-web-design/">blog post</a> by <a href="https://twitter.com/nickrp">Nick Pettit</a>, one of my favourite tutorial wizard at Carsonified!

Feel free to share your thoughts below!