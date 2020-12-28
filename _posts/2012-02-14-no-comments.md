---
layout: post
title:  "No comment(s)...?"
date:   2012-02-14
categories: [coding, css]
tags: [coding, css, comments]
---

```// Why comment lines in your code are so important, or are they?```

I’ve always appreciated clean code and good comments, but I have to admit I can be a messy _code commentator_.

This post is a promise to myself: I will comment my code in a better way.

What way, though?

Although programming languages can be very different I believe they have one thing in common: if they are not well organised, they are hard to read.
This includes the way developers write and lay out the code and their comments to it.

After reading few articles online (see list at the bottom of this post), I came up with this top 7 checklist, which is basically a list of how to avoid my bad habits at coding and commenting.

In order to achieve the goal to radically improve my coding abilities I’ll try to follow my own advice and I’ll be more than happy to hear your say!

<ul>
    <li>Separate blocks of code with comments<br>
<pre>
/* =Structure ------------------- */
body { padding: 0 2em; }
/* =Header ------------------- */
#site-title { width: 40%; margin: 0 0 0 165px; }
</pre>
    </li>
    <li>Comment while you edit</li>
    <li>Delete the commented lines of code (guilty!)<br>
<pre>
background: #fff;
// maring-right: 2em; < DELETE ME!
Use TODO while prototyping (and remove it as soon as it’s done!)
.three-columns {
  // TODO > define the 3 columns style
}
</pre>
    </li>
    <li>Make code as self explanatory as possible (that I do, yay!)</li>
    <li>Edit your comments if you edit your code</li>
    <li>Avoid obvious comments<br>
<pre>
.game-results {
  margin: 1.5em; // add margin around box < no kidding
}
</pre>
    </li>
</ul>

<h2>List of interesting articles on the matter</h2>
<ul>
    <li><a href="//www.devtopics.com/13-tips-to-comment-your-code/">13 Tips to Comment Your Code</a></li>
    <li>And here is the original… if you fancy some Spanish <a href="//www.variablenotfound.com/2007/12/13-consejos-para-comentar-tu-cdigo.html">13 Consejos para comentar tu c&oacute;digo</a></li>
    <li><a href="//apdevblog.com/comments-in-code/">Don’t comment your code!</a></li>
    <li><a href="//codeutopia.net/blog/2009/10/15/is-commenting-your-code-useless/">Is commenting your code useless?</a></li>
</ul>
<p>Oh and happy <a href="//en.wikipedia.org/wiki/Valentine%27s_Day">Saint Valentine’s Day</a> to those who celebrate it.</p>