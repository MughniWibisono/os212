---
permalink: /ABOUT/
---

# About

Hi! I'm Mughni Wibisono-, currently I study at the University of Indonesia and major in computer science.
This is my github page, I know it's not much but feel free to explore !

<br>
# More Information

<ul><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub Page" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub" %}
    <a href="{{ https://github.com/MughniWibisono/os212 }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li></ul><br>

# Qapla!



