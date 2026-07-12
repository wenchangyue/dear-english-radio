---
layout: default
title: English listening, one level and one story at a time
description: >-
  Dear English Radio publishes CEFR-aligned English conversations and stories
  with reviewed transcripts, simple definitions, questions, and sources.
---

# Letters, stories and voices for English learners

Dear English Radio is a listening room for people who want to understand and
speak English with more confidence. Before the internet, learners listened to
radio programs with care and wrote letters with their questions. We bring that
patient spirit to clear, modern English conversations and stories.

Every lesson has one estimated CEFR level and one main topic. There are no
translations. Listen for meaning, notice natural rhythm and useful phrases,
then answer a question or retell the idea in your own words.

[Visit Dear English Radio on YouTube](https://www.youtube.com/@dearenglishradio){:.primary-link}

## Episode companions

{% if site.episodes.size > 0 %}
<div class="episode-list">
{% assign sorted_episodes = site.episodes | sort: "date" | reverse %}
{% for ep in sorted_episodes %}
  <article class="episode-card">
    <p class="eyebrow">{{ ep.cefr_level }} · {{ ep.topic }}</p>
    <h2><a href="{{ ep.url | relative_url }}">{{ ep.title }}</a></h2>
    <p>{{ ep.description }}</p>
  </article>
{% endfor %}
</div>
{% else %}
_Episode companions will appear here as lessons are released._
{% endif %}

## How to use a lesson

1. Listen once for the main idea.
2. Listen again and follow the captions.
3. Notice useful phrases, rhythm and weak forms.
4. Close the text and retell the idea in your own words.
5. Check the transcript and try again later.

Listen. Notice. Speak.

