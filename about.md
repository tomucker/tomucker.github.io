---
layout: page
title: About
---

{% comment %}
  This inserts the "about" photo and text from `_config.yml`.
  You can edit it there (jekyll needs restart!) or remove it and provide your own photo/text.
  Don't forget to add the `me` class to the photo, like this: `![alt](src){:.me}`.
{% endcomment %}

{% if site.author.photo %}
  ![{{ site.author.name }}]({{ site.author.photo }}){:.me}
{% endif %}

{{ site.author.about }}

I can be found where the people are few and drinks many. In love with [data](http://johncoene.github.io/projects/) and argument. 

Influenced by Thomas Jefferson, Thomas Paine, Adam Smith, Friedrich Hayek, Chritopher Hitchens, Frédéric Bastiat, and Nassim Nicholas Taleb.

***

## Links

* R Programming [project vault](http://johncoene.github.io/projects).
* [Resume](http://johncoene.github.io/projects)
