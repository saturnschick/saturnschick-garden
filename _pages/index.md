---
layout: page
title: Home
id: home
permalink: /
---

# Witamy! 🍓🍒
# 🌙 About Me

## Welcome to my corner of the universe ✨

Welcome to my little corner of the universe. This is where I share everything I love, everything that sparks my interest, updates on my life, my thoughts, and basically whatever comes to mind.  

Expect lots of:  
- 📸 Photos  
- 🎵 Music I’m currently obsessed with  
- 💄 Skincare tips & all things girly  
- 🔮 Plenty of witchy vibes  

---

## My little first project 🌱

This space won’t be perfect—it’s my very first *project*, my initial step into creativity, and a way to channel the storms in my mind.  

---

## Scroll if you want, peek if you like 👀

If some things here don’t quite make sense to you, feel free to scroll on by! This isn’t necessarily for you, nor written with you in mind.  

But I’m offering you a glimpse—a peek into my world. It might not always make sense, but it makes perfect sense to me, and that’s all that matters because this is *my page*.

---

## I am the hero here 😎

Hahaha 😉

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p>

This digital garden template is free, open-source, and [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

The easiest way to get started is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
