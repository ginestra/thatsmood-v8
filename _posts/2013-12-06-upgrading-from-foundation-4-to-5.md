---
layout: post
title:  "Upgrading from Foundation 4 to 5"
date:   2013-12-06
categories: [foundation, upgrade]
tags: [foundation, upgrade, development]
---

I thought I’d share this in case another half designer half front-end developer runs into the same issues I had.
Unfortunately I wasn’t so smart to record my process step by step, so some info might be missing. But here is a recollection of what I remember doing when updating from Foundation 4 to Foundation 5.

I’m currently working on few different projects using Foundation 4.
One is fairly recent and I thought it was worth upgrading it to [Foundation 5](//foundation.zurb.com/).
Not least because this is the version I’m going to use when the next project comes along. A good chance to start familiarising with it.

When I thought about upgrading I was well aware that I needed to run projects in F4 as well as projects in F5… at the same time.

Let me say that don’t know Ruby, I’m new to Foundation and I only recently started using the shell/terminal consistently because of SASS. So, I’m no expert and most of the times I am not sure what’s going on ‘behind the scenes’. Stackoverflow is a lifesaver when I get stuck. [This is the post](//stackoverflow.com/questions/5059196/how-to-update-my-version-of-ruby-from-terminal) that pointed me in the right direction from the start.

So RVM let’s you run different versions of Ruby simultaneously.

```
\curl -L https://get.rvm.io | bash -s stable --ruby=1.9.3
```

To be specific I installed 1.8.7 for my older project and 2.0.0 for the one I needed to upgrade.

```
rvm install 1.8.7
rvm install 2.0.0
```

You can also set which one you want to run by default.

```
rvm --default use 2.0.0
```

Then I upgraded from Foundation 4 to 5 following [the official docs](//foundation.zurb.com/docs/upgrading.html).

I remember installing rubygems for v 1.8.7 (when I tried to recompile a .scss file in F4 the first time after the upgrade I run into an error pointing out I was missing rubygems).

```
rvm rubygems 1.8.7
```

## Issues

Once reinstalled `zurb-foundation` for projects running in F4 and `foundation` for project running F5, new projects worked fine.
Not so much for existing ones (whether upgraded or not): I had to manually change the link to the js components in my base.html template to point to the `bower_components` folder.

Not a big deal to be honest and it might well be that I have forgotten some steps in the procedure that would have fixed this from the start (maybe I didn’t recompile, can’t remember!).

Although messy and _patchy_, I hope you can find some useful information if you’re in the process of upgrading to Foundation 5 and/or run Foundation 4 and 5 simultaneously.

Also, if you have found a cleaner way to manage projects in this sort of scenario, please let me know by commenting below! Thanks. 🙂