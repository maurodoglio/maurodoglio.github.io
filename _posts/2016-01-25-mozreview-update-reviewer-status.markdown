---
published: true
title: Mozreview update - reviewer status
layout: post
tags: [mozreview, ux]
---
A number of people are confused by how we display the status of each review request in the commits table UI and how it relates to bugzilla flags. On the review request page the reviewer name is now surrounded with a green background if the reviewer has given a ship-it. 

![](/public/images/uuE1CN5.jpg)

The background will still be green even if the reviewer gave a ship-it-then-fix-it (i.e. a ship-it with some open issues), in which case the overall commit status will be marked as yellow.

![](/public/images/gDxfHId.png)