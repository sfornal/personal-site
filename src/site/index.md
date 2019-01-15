---
title: Stephen Fornal
subtitle: Just a guy who makes websites and knows a lot of useless information
layout: layouts/base.njk
---


## Who Am I?

I'm the Manager of  Web Developer for [Tarrant County College](https://www.tccd.edu), a public college in Fort Worth, TX, with over 50,000 students and six campuses. We're one of the largest colleges in the U.S., and we have a commitment to maintaining and accessible and high performance web site.

I like to cook, read, drink beer, run, and play &amp; [host](http://www.pgtrivia.com) pub trivia.

## Recent Posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> &mdash;
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay }}</time>
  </li>
{%- endfor -%}
</ul>

## Find Me on Social Media

* [Facebook]()
* [Twitter]()
* [Instagram]()