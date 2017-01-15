---
title:  Template
tags: [tag1]
keywords: navigation tabs, hide sections, tabbers, interface tabs
last_updated: January 14, 2016
summary: "Brief Summary"
sidebar: documentation_sidebar
permalink: template.html
folder: documentation
---


## Explanation

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.


## Code Examples

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a class="noCrossRef" href="#profile" data-toggle="tab">Ruby</a></li>
    <li><a class="noCrossRef" href="#java" data-toggle="tab">Java</a></li>
    <li><a class="noCrossRef" href="#python" data-toggle="tab">Python</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="ruby" markdown="1">

  <pre>
    <code>
      class Document
        attr_accessor :name

        def initialize(name)
          @name = name
        end

        def set_name(name)
          @name = name
        end
      end
    </code>
  </pre>
</div>

  <div role="tabpanel" class="tab-pane" id="java">
    <pre>
      <code>
      public class EncapTest {
       private String name;
       private String idNum;
       private int age;

       public int getAge() {
          return age;
       }

       public String getName() {
          return name;
       }

       public String getIdNum() {
          return idNum;
       }

       public void setAge( int newAge) {
          age = newAge;
       }

       public void setName(String newName) {
          name = newName;
       }

       public void setIdNum( String newId) {
          idNum = newId;
       }
      }
      </code>
    </pre>
  </div>

  <div role="tabpanel" class="tab-pane" id="python">
    <pre>
      <code>
      class Car:
        def __init__(self):
            self.__updateSoftware()

        def drive(self):
            print 'driving'

        def __updateSoftware(self):
            print 'updating software'
      </code>
    </pre>
  </div>
</div>
