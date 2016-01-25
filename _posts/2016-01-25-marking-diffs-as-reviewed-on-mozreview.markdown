---
published: true
title: Marking diffs as reviewed on mozreview
layout: post
---
Like other code review tools out there, MozReview now allows you to mark a single diff as reviewed.
A new button has been added to the top-right corner of each diff. This button, initially grey and labelled 'not reviewed', will turn green when clicked and its label will switch to 'reviewed'.

Here is an example of a diff not yet reviewed

![](http://i.imgur.com/0szhd4Y.png)

and here is how it looks like when you click on the `not reviewed` button

![](http://i.imgur.com/bdGA47j.png)

The ability to mark diffs as reviewed opens new possibilities up:

 * display a counter of files yet to be review ([bug 1233597](https://bugzilla.mozilla.org/show_bug.cgi?id=1233597))
 * add a 'what's next to review' link that the user can click to go the the next yet to be reviewed diff ([bug 1242457](https://bugzilla.mozilla.org/show_bug.cgi?id=1242457))
 * let the user opt-in to give a direct ship-it when all the diffs in a commit are reviewed and there are no open issues ([bug 1237634](https://bugzilla.mozilla.org/show_bug.cgi?id=1237634))

If you think one of those features would really make you more productive please let us know on [the mozreview irc channel](irc://irc.mozilla.org/#mozreview) or [twitter](https://twitter.com/_mozreview) so that we can prioritize it accordingly