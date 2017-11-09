---
layout: default
---


<h1>Featured Article</h1>
<article id="featured-post">
  {% for post in site.posts limit:1 %}
    {% if post.excerpt %}
      <h2>{{ post.title }}</h2>
      <summary class="byline">
        {{ post.author }} - 
        {{ post.date | date: "%-m/%-d/%y"}}
      </summary>
      {{ post.excerpt }}

      <a href="{{ post.url }}">read more...</a>
    {% endif %}
  {% endfor %}
</article>

<h2>About the author</h2>

{% include bio-marketing.md %}

[read more...](about.html)