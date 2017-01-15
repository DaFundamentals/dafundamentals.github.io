---
title:  Data Abstraction
tags: [oop]
keywords: navigation tabs, hide sections, tabbers, interface tabs
last_updated: January 14, 2016
summary: "Data Abstraction"
sidebar: documentation_sidebar
permalink: data_abstraction.html
folder: documentation
---

### Data Abstraction
some words go here

## Functionality to implement

One piece of functionality I'd like to implement is the ability to set site-wide nav tab options. For example, if the user always chooses PHP instead of Java in the code samples, it would be great to set this option site-wide by default. However, this functionality isn't yet coded.

{% include links.html %}

## Code Examples

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a class="noCrossRef" href="#profile" data-toggle="tab">Ruby</a></li>
    <li><a class="noCrossRef" href="#java" data-toggle="tab">Java</a></li>
    <li><a class="noCrossRef" href="#python" data-toggle="tab">Python</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="profile" markdown="1">
## Ruby
  <p>Ruby Stuff</p>
</div>

  <div role="tabpanel" class="tab-pane" id="java">
      <h2>Java</h2>
      <p>
        Java Stuff
      </p>
  </div>

  <div role="tabpanel" class="tab-pane" id="python">
      <h2>Python</h2>
      <p>
        Python Stuff
      </p>
  </div>
</div>
