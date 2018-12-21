---
layout: page
title: lightning talks on pragmatic testing
---
{% include JB/setup %}

Pragmatic Testing is a series of ignite-style lightning talks I've been presenting
at [San Diego Python](http://www.meetup.com/pythonsd) meetup. The objective is to
document approaches to dealing with common situations a developer might encounter
when attempting to test a piece of software.

The ideas I'm communicating here are not new and not mine. For the most I've learned
these from more experienced engineers I've worked with. Significant inspiration (read:
material) is taken (read: stolen) from Google's
[Testing on the Toilet](http://googletesting.blogspot.com/search/label/TotT)
blog, the [Pragmatic Programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer),
and Martin Fowler's [Refactoring](http://refactoring.com/). Various images and such are
used without attribution or permission.

### the talks:

<ul class="posts">
  {% for post in site.posts reversed %}
    {% if post.title != 'template' %}
      <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
  <li><a href="{{ BASE_PATH }}/template">template</a></li>
</ul>

