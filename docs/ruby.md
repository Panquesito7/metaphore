---
layout: default
title: Ruby Metaphors
nav_order: 9
description: "This page contains any unsual ~~code snippets~~ metaphors from our Ruby Punk Member."
permalink: /ruby
---

# Ruby Metaphors

This page contains any unsual ~~code snippets~~ metaphors from our Ruby Punk Member.

[Create Ruby Story](https://github.com/StreetCommunityProgrammer/metaphore/issues/new?assignees=darkterminal%2Cmkubdev&labels=metaphore%2Cruby&template=create_ruby_story.yml&title=Your+Story+Title){:target="_blank" .btn .btn-purple}

## List of Metaphors
{% assign ruby = site.stories | where: "language", "ruby" %}
{% for metaphor in ruby %}
- [{{ metaphor.title }} by {{ metaphor.author }}]({{ metaphor.url | relative_url }})
{% else %}
  _The **Ruby** collection is empty. Did you have metaphor in Ruby? [Create my Ruby metaphor](https://github.com/StreetCommunityProgrammer/metaphore/issues/new?assignees=darkterminal%2Cmkubdev&labels=metaphore%2Cruby&template=create_ruby_story.yml&title=Your+Story+Title){:target="_blank"}_
{% endfor %}