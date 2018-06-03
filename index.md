---
title: HMNDLX
menu_order: 0
layout: default
---

# Home

Generally regulators use a combination of these basic forms of regulation. Combining forms of regulation is called hybrid regulation. For example, U.K. regulators (e.g. Ofgem) combine elements of rate of return regulation and price cap regulation to create their form of RPI - X regulation.

![person.png](/uploads/person.png)

## Products

<div class="products">
{% for product in site.products %}
<div class="product__item">
<img src="{{ product.image }}">
{{ product.title }}
</div>
{% endfor %}
</div>

## Blog

<div class="blog">
{% for post in site.posts %}
<a href="{{ post.url | absolute_url }}">{{ post.title }}</a>
{% endfor %}
</div>

## Team

<div class="products">
{% for person in site.people %}
<div class="product__item">
<img src="{{ person.image }}">
<h3>{{ person.name }}</h3>
<p>{{ person.title }}</p>
</div>
{% endfor %}
</div>