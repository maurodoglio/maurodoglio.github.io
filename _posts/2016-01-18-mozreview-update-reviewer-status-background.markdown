---
published: true
layout: post
title: Mozreview update: reviewer status background
---
A number of people are confused by how we display the status of each review request in the commits table UI and how it relates to bugzilla flags. To make it clear who has reviewed and who is still waiting to review we decided to surround the reviewer name with a green background once the reviewer has given a ship-it.
![](http://i.imgur.com/uuE1CN5.jpg?2)
The background will still be green even if the reviewer gave a ship-it-then-fix-it (i.e. a ship-it with some open issues) in which case the overall commit status will be marked as yellow.
![](http://i.imgur.com/gDxfHId.png?3)