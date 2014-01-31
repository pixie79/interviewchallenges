---
layout: page
title: Tech interview / team challenges
tagline: Python, Ruby, Pig Challenges for interviews or teams
---
{% include JB/setup %}

Welcome to the growing source of tech challenges which can be used for interviews or as team and individual challenges. Most of these can be completed in a variety of different languages depending on the needs of the environment.

If anyone has any other challenges they would like to share please contact us and we can add them here. We do not post the answers to any of the challenges as this would spoil it for most people by allowing too much cheating or assistance. We do however publish the expected output so that people can tell if they have the right result. If anybody does need help then shout out on twitter using the hash tag #interviewchallenges.


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

