---
title: Introduction
sidebar: mydoc_sidebar
permalink: mydoc_introduction.html
folder: mydoc
---

## Why visualize?
We want to take advantage of the sense of sight, which can process visual information automatically and unconsciously (__preattentive processing__).

The opposite of preattentive processing is __attentive processing__, and it is higher-level cognitive processing that occurs in working memory. Attentive processing is conscious, sequential, and much slower.

Here's the basic principle - find the 5s:

<hr>
<div class="text-center" style="font-weight:bold">Attentive processing</div>
<div style="padding:0 20%"><span style="color: lightgrey;word-break:break-all">
012030772836389463103847647385647382738492827465346738292918282891827366574628374738382927658647839221929283283749275601
</span></div>

<br>

<div class="text-center" style="font-weight:bold">Preattentive processing</div>

<div style="padding:0 20%"><span style="color: lightgrey;word-break:break-all">
01203077283638946310384764738<span style="color: black">5</span>64738273849282746<span style="color: black">5</span>346738292918282891827366<span style="color: black">5</span>746283747383829276<span style="color: black">5</span>864783922192928328374927<span style="color: black">5</span>601
</span></div>
<hr>

## Which visualization to choose?
First, ask yourself these three questions:
1. What kind of data do I have?
  - Are the data spatial, or is there a network, etc.
  - What kind of variables am I dealing with? Are they categorical, ordered, etc.
2. Do I want to visualize this, and if so, why?
  - Is the reason for exploratory analysis, communicating results, etc.
3. What message am I trying to convey?
  - What visualization technique most effectively encodes my data?

### Search Space Metaphor
Trying to choose the right visualization, depends on our knowledge of all possible solutions that exists in the visualization space.

In the ideal scenario, we know a lot of possible solutions, consider many, try a few, and select a good solution at the end. In the less than ideal scenario, we have a limited set of visualizations we know, we consider a few, and select the only one we tried, which was a poor solution.


![Search Space](images/search-space.jpg "Search Space")

Hopefully, this documentation will not only help guide you to choose the best visualizations possible, but also serve to broaden your view of other visualizations you might not have known about or had not considered before.


If you are wondering about how to display your data, we assume that know the types of data you have (numerical: continuous or discrete, categorical or ordinal) and that you have a reason for creating the visualization. Knowing your data is important because visualizations for categorical data will be different that visualizations for continuous data. Having a reason is important because some visualizations will be better than other at displaying certain things (if you are trying to display trends, that is different that trying to display magnitudes of the values).

### Shared features

#### Marks

A mark is a basic graphical element in an image.
- 0-D, points
- 1-D, lines
- 2-D, area
- 3-D, volume (rarely used)

![Marks Diagram](images/marks-diagram.jpg "Marks Diagram")



#### Channels
Channels control the appearance of marks.

Examples of Channels:
- Horizontal position, vertical position, or both
- The tilt (slope)
- Hue (as opposed to saturation and brightness)

![Channels Diagram](images/channels.jpg "Channels Diagram")

{% include links.html %}
