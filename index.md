---
layout: page
title: Blog - Hobby - Profession
tagline: Nothing personal
---
{% include JB/setup %}


## My Blog

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Hobby

### Robotics

### OpenCV ![labeler](assets/img/haarselector-small.png)
* [OpenCV](href="http://opencv.org")
* [Object-labeler](https://github.com/peterborkuti/haarselector)

### Learning Machine Learning ![ml](assets/img/ml-small.png)
* [Andrew Ng](https://www.coursera.org/course/ml) 
* [Sebastian Thrun](https://www.udacity.com/course/cs373)
* [S. Thrun and Peter Norvig](https://www.udacity.com/course/cs271)

### Learning Electronics ![mitx](assets/img/mitx-cert-small.png)
* [Prof. Anant Agarval](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-002-circuits-and-electronics-spring-2007/)  

## Professional life

### Learning
![elte](assets/img/elte-small.gif)  ![bme](assets/img/bme-logo-small.png)![lpic1](assets/img/lpic1.png) ![lpic2](assets/img/lpic2.png) ![ocjp](assets/img/ocpjp.jpg)

### Working
* [php](http://www.matesz.hu)
* [java](http://www.liferay.com)
* [javascript](https://github.com/peterborkuti/other/JavaScriptBasics)
* [visit me on github](https://github.com/peterborkuti)
