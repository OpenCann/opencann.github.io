---
layout: page
title: About
permalink: /about/
---

Welcome to OpenCann. The goal of this project is to develop a platform/ecosystem to enable the automation, and optimization, of cannabis cultivation. Everything that we develop will be open-source, and will be done in such a manner that anyone with the time, interest, and funds can build their very own system at home. At least to begin with, we will be focused on a small-scale cultivation platform; something that could be built by a competent individual with some knowledge of computer programming/hardware (python, Raspberry Pi, basic wiring, etc.).

This project is inspired by the [MIT Media Lab Open Agriculture Initiative (OpenAg)](http://openag.media.mit.edu/). The OpenAg infrastructure will enable this project to focus on our own domain specific challenges. Rather than building a platform from scratch, we will rely upon the foundation that has been developed by the folks over at OpenAg. This will enable us to focus on refining higher level processes, and systems, that will (hopefully) in turn benefit the broader agricultural community as we all learn, develop, and grow together.

#### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
