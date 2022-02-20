---
layout: page
title: Other Blogs
permalink: /other-blogs/
---

There are a bunch of other blogs people have made/kept for their meta recoveries, and I thought it would be useful to keep a list here so they're easy to find all in one place. I'm also happy to add individual pages to store people's writing and/or photos, if they don't want to make their own blog. I'm currently working on getting permission from folks to link their blogs here, so for now, here are two examples of what it would look like:

- [Meta w/ Meltzer](https://themeltzerclinic.com/ftm-surgeries-procedures/) - this is a link to Meltzer's site, just as an example of what it would look like to link to another blog here
{% for local_blog in site.other_local_blogs %}
- [{{local_blog.title}}]({{local_blog.url}}) - this is an example page to show what it would look like if someone wanted to submit their own writing (with or without photos) to be hosted here on this site, so they don't have to create their own wordpress or blogger site
{% endfor %}
