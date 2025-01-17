---
title: RStudio shortcuts for laptop productivity
author: Nate Day
date: '2019-11-02'
slug: rstudio-shortcuts-for-laptop-productivity
categories:
  - RStudio
tags:
  - keyboad-shortcuts
---

I spent last week working in train cars, coffee shops, and libraries. My to-do list was mostly data analysis, so I was a little worried about shrinking my workstation workflow to just my 13" laptop. The reduced screen real-estate and lack of a mouse, motivated me to experiment a lot with RStudio's keyboard shortcuts. These are the six that I found myself using the most.

### Zoom Plots

<kbd class="item-cat">Control</kbd> + <kbd class="item-cat">Shift</kbd> + <kbd class="item-cat">6</kbd>

<video height = "320" width = "100%" autoplay loop name = "Switch editor tabs"
  src =/post/2019-11-02-rstudio-shortcuts-for-laptop-productivity_files/blog_zoom-plot.mov>
</video>

**My favorite shortcut of the bunch**

By far the *biggest* pane of working on a small screen for me is plotting. Trying to inspect even midly complex plots on 1/4 of of 13" is a bad time. And if you use any `plot()` based graphics, you will be seeing the "figure margins too large" error message a lot.

Repeating this shorcut shrinks panels back to their prior sizes. Also worth mentioning, this *does not* move your cursor. So if you just ran into a fatal `plot` margin error in the Console, you just zoom then <kbd class="item-cat">u-arrow</kbd>. + <kbd class="item-cat">Return</kbd> to rerun and dodge the fatal margin error.</kbd>

### Focus to:

Learning to navitage RStudio with less mouse helps even at a desk workstation, and I felt it become even more valuable when all I had was the trackpad. These are the "Big 3" re-focusers, that I use all the time.

<video height = "320" width = "100%" autoplay loop name = "Switch editor tabs"
  src =/post/2019-11-02-rstudio-shortcuts-for-laptop-productivity_files/blog_big3.mov>
</video>

#### Console

<kbd class="item-cat">Control</kbd> + <kbd class="item-cat">2</kbd>

Moving the active cursor to the Console is great for all things interactive.

#### Editor

<kbd class="item-cat">Control</kbd> + <kbd class="item-cat">1</kbd>

Of course you'll have to move back. Remembering the "one, two" pattern for was helpful.

#### Terminal

<kbd class="item-cat">Option</kbd> + <kbd class="item-cat">Shift</kbd> + <kbd class="item-cat">T</kbd>

This one was harder for me to remember becasue it wasn't in the <kbd class="item-cat">Control</kbd> + <kbd class="item-cat">#</kbd> pattern.  But I use the `git` CLI a lot, so I had to learn it.

### Switch between Editor tabs

<kbd class="item-cat">Control</kbd> + <kbd class="item-cat">Option</kbd> + <kbd class="item-cat">l/r arrows</kbd>

<video height = "320" width = "100%" autoplay loop name = "Switch editor tabs"
  src = /post/2019-11-02-rstudio-shortcuts-for-laptop-productivity_files/blog_switch-editor.mov>
</video>

This is very very useful for switching between R scripts or `View()` windows.

### Show all panels

<kbd class="item-cat">Control</kbd> + <kbd class="item-cat">Shift</kbd> + <kbd class="item-cat">0</kbd>

<video height = "320" width = "100%" autoplay loop name = "Switch editor tabs"
  src = /post/2019-11-02-rstudio-shortcuts-for-laptop-productivity_files/blog_reset.mov>
</video>

I found this most useful after I'd hit the wrong Zoom shortcut by mistake, it was effectivly my IDE reset switch.

### Conclusion

Now that I'm back to my normal workstation, I'm still using all of these shortcuts. It does require a lot of conscious effort at the begining to use the shortcuts and not bail out to the trackpad. But it's totally worth it, just after the one week of trying I can feel my muscle memory is improving.

You can see all of RStudios available shortcuts for yourself with yet another keyboard shortcut <kbd class="item-cat">Option</kbd> + <kbd class="item-cat">Shift</kbd> + <kbd class="item-cat">K</kbd>.

The screen screen recordings in this post are made with [KeyCastr](https://github.com/keycastr/keycastr/blob/master/README.md) which is also a great tool for teaching code. Thanks to Jeff Boichuk for sharing!
