---
layout: default
title: "Welcome to RedMatter Ideas"
---
<ul>
  {% for post in site.posts %}
    <li>
      <h4 class="text-gray-400">{{ post.date | date: "%B %d, %Y" }}</h4>
      <h2 class="font-['concourse2']"><a href="{{ post.url }}" class="text-2xl font-medium text-blue-600 dark:text-blue-500 hover:underline">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>