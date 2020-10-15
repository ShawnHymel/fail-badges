---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{%- for post in site.posts -%}
<a href="{{ post.url | relative_url }}"><img width="200" height="200" src="{{ site.baseurl }}/badges/{{ post.image }}" alt="{{ post.name }}" title="{{ post.description }}" /></a>
{%- endfor -%}
