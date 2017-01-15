---
title:  Encapsulation
tags: [oop]
keywords: navigation tabs, hide sections, tabbers, interface tabs
last_updated: January 14, 2016
summary: "Encapsulation"
sidebar: documentation_sidebar
permalink: encapsulation.html
folder: documentation
---


## Common uses

Navtabs are particularly useful for scenarios where you want to show a variety of options, such as code samples for Java, .NET, or PHP, on the same page.

While you could resort to single-source publishing to provide different outputs for each unique programming language or role, you could also use navtabs to allow users to select the content you want.

Navtabs are better for SEO since you avoid duplicate content and drive users to the same page.

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
