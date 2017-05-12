+++
template = "docs.html"
+++

# Welcome to Tera

Tera is an open-source template engine written in Rust based on Jinja2 and Django templates. It will feel familiar if you have
used Twig or Liquid as well.


```jinja2
<title>{% block title %}{% endblock %}</title>
<ul>
{% for user in users %}
  <li><a href="{{ user.url }}">{{ user.username }}</a></li>
{% endfor %}
</ul>
```

## Table of Contents

- [Getting started]()
- [Basic usage]()
    - [Extending another instance of Tera]()
    - [Reloading]()
    - [Auto-escaping]()
- [Template writer documentation]()
    - [Introduction]()
    - [Variables]()
    - [Comments]()
    - [Raw]()
    - [Set]()
    - [Conditionals]()
    - [Iteration]()
    - [Inheritance]()
    - [Macros]()
    - [Include]()
    - [Filters]()
    - [Tests]()
    - [Global functions]()
- [Changelog]()
