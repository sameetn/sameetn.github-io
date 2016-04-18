---
layout: post
title: "Practical DevOps"
date: 2016-02-10 22:00:00
description: Practical DevOps
comments: false
---

Okay... Okay...I admit it !!! There is a lot of information floating all over the net about DevOps be it with books, articles, blogs, tutorials etc. One thing I did notice as I got about implementing it at the couple of places that I worked is that folks had a different explanation of what DevOps really is. I am by no means an expert on this but I personally prefer the following definition:

```
DevOps is a cultural change within the organization promoting a faster, easier interaction between the development team(s) and the operations team(s). It is neither a set of tools nor a framework and is not limited to automated and continuous delivery/deployments.
```

This is intentionally a very broad statement. It means that for any initiative to succeed within the organization, the two teams must work together with minimal processes and no bureaucracies throughout the entire development, deployment and release lifecycle.

Having said that as I searched I have been able to find articles targeting good approaches in specific areas of a lifecycle like development, build and deployment etc., but I have not found one that ties all of them together using the collaborative working principle which is essential to the successful practice of DevOps and why I started to write this post as a practical implementation of the end to end lifecycle.

This guide will be done as a series of articles as opposed to one monolithic article. The product lifecycle that we shall cover will consist of the following steps:

* Source Control setup
* Local development environment
* Deployment environments setup
* Delivery pipeline for the application
* Additional applications with all of the above

** Your own lifecycle might be a little more complicated than this but you can add/subtract as you see fit **
