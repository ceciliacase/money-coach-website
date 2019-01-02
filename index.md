---
layout: default
---

<!-- Main ask -->
<h1>How is your relationship with money?</h1>
<ul>
  <li>Does money affect your relationships with your partner, friends, and family?</li>
  <li>Do you avoid looking at your bank account balance? Do you say a little prayer when you hand over your credit card to the cashier?</li>
  <li>Does your money situation get in the way of having a successful business?</li>
</ul>

If you said yes to any of these questions, I can help you!

Knowing how to budget is only a small part of financial health. It is just as important to address the emotional aspect of money. Understanding your money story and your money past is what will help you heal your relationship with money, and help the most with putting in places the systems and techniques for good financial health.

Learning how to heal your relationship with money will transform budgeting into one of joy and alignment with your values. You can learn how to transform your chaotic financial situation into one of peace and joy, learn techniques to get out of the paycheck-to-paycheck cycle, and become debt-free, and establish lifelong habits and patterns that help your money stay in sync with your life and values!


You deserve to have a good relationship with money! Get started by scheduling your free session! {% include calendly.md class="button inline" %}

<!-- Articles -->
<h1>Featured Article</h1>
<article id="featured-post">
  {% for post in site.posts limit:1 %}
    {% if post.excerpt %}
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <summary class="byline">
        {{ post.author }} - 
        {{ post.date | date: "%-m/%-d/%y"}}
      </summary>
      <a class="featured-post-link" href="{{ post.url }}">
        <img class="featured-image" src="{{ site.url }}/assets/images/{{ post.img }}" />
        {{ post.excerpt }}
      </a>
      <a class="button inline" href="{{ post.url }}">more...</a>
    {% endif %}
  {% endfor %}
</article>

<h2>About Cecilia</h2>

{% include bio-marketing.md %}
