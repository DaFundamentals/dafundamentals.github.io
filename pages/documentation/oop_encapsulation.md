---
title:  Encapsulation
tags: [oop]
keywords: navigation tabs, hide sections, tabbers, interface tabs
last_updated: January 14, 2016
summary: "Grouping data (variables) and code acting on the data (methods/functions) as a single object or unit."
sidebar: documentation_sidebar
permalink: oop_encapsulation.html
folder: documentation
---

**Encapsulation** makes it possible to separate an objects implementation from its behavior to restrict access to its internal data. This restriction allows certain details of an objects behavior to be hidden. It allows us to create a “black box” and protects an objects internal state from corruption by its clients.

Rather then having a bike with all its pieces scattered, we are grouping everything together in one class.

**Advantages:**

* Makes it easy to model real-world entities
* Controls the way data is accessed or modified
* Easier maintainability
* Flexible
* Reusable
* Reduces coupling of modules and increase cohesion inside a module because all piece of one thing are encapsulated in one place.

----------

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
      class Person
        attr_reader :name, :age

        def initialize(name, age)
          @name = name
          @age = age
        end

        def set_name(name)
          @name = name
        end

        def set_age(age)
          @age = age
        end
      end
    </code>
  </pre>
</div>

  <div role="tabpanel" class="tab-pane" id="java">
    <pre>
      <code>
      public class Person {
       private String name;
       private int age;

       public int getAge() {
          return age;
       }

       public String getName() {
          return name;
       }

       public void setAge( int newAge) {
          age = newAge;
       }

       public void setName(String newName) {
          name = newName;
       }
      }
      </code>
    </pre>
  </div>

  <div role="tabpanel" class="tab-pane" id="python">
    <pre>
      <code>
      class Person:
        def __init__(self, name, age):
          self.name = name
          self.age = age

      </code>
    </pre>
  </div>
</div>
