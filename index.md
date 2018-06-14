---
layout: default
---

<!-- Main ask -->
<h1>What's up with <b>your</b> relationship with money?</h1>
<ul>
  <li>Does money affect your relationships with your partner, friends, and family?</li>
  <li>Do you avoid looking at your bank account balance? Do you say a little prayer when you hand over your credit card to the cashier?</li>
  <li>Does money affect your relationship with yourself?</li>
</ul>

<p>I used to be mystified by personal finances and budgeting, getting myself into and out of debt for most of my young adult life. I hated the uncertainty, and I was so stressed all the time! I felt guilty that I couldn’t harness my money to do what <b>I</b> wanted. I was capable in so many areas, why couldn’t I work responsibly with money?</p>

<p>About four years ago, I ran across a budgeting technique called Envelope Budgeting. It clicked, and since then I have worked hard, made mistakes, and learned techniques for paying off debt, saving for my goals, and even saving for retirement. But that isn’t the most important thing I’ve learned. The most important thing is that I have discovered how to find peace and joy in my financial life. I now have serenity when I look at my bank accounts, and feel joy when I look at my budget. And I can help you find the same peace and joy in your finances!
</p>
<p>
You deserve to have a good relationship with money!
</p>

<h1>Featured Article</h1>
<article id="featured-post">
  {% for post in site.posts limit:1 %}
    {% if post.excerpt %}
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <summary class="byline">
        {{ post.author }} - 
        {{ post.date | date: "%-m/%-d/%y"}}
      </summary>
      <img class="featured-image" src="{{ site.url }}/assets/images/{{ post.img }}" />

      {{ post.excerpt }}
      <a class="button reversed readmore" href="{{ post.url }}#read-more">more...</a>
    {% endif %}
  {% endfor %}
</article>

<h2>About the author</h2>

{% include bio-marketing.md %}

<a class=" button reversed readmore" href="about.html">more...</a>