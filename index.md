---
layout: page
---

# Welcome to Megan's Personal Website

Some cool things about me and what my website is about

## My Projects
List of projects that I have done

## My Experience
List of work/jobs


## Hello World!

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Tincidunt ornare massa eget egestas purus viverra. Morbi quis commodo odio aenean sed adipiscing diam donec adipiscing. Malesuada nunc vel risus commodo viverra maecenas accumsan lacus. Et malesuada fames ac turpis egestas maecenas. In nulla posuere sollicitudin aliquam ultrices sagittis. Rhoncus urna neque viverra justo nec ultrices dui. Eget nullam non nisi est. Nam at lectus urna duis convallis convallis tellus id interdum. Nec feugiat in fermentum posuere urna nec. Placerat orci nulla pellentesque dignissim enim sit amet venenatis. Duis ultricies lacus sed turpis tincidunt id aliquet. Aliquam ultrices sagittis orci a scelerisque purus semper eget. Ac placerat vestibulum lectus mauris ultrices. Odio euismod lacinia at quis risus.



## Another Section

![test]({{ site.baseurl }}/assets/img/i-rest.jpg)

Habitant morbi tristique senectus et netus et malesuada fames ac. Lectus quam id leo in vitae turpis massa. Molestie at elementum eu facilisis sed odio. Elementum sagittis vitae et leo duis. Duis convallis convallis tellus id interdum velit laoreet id. Auctor elit sed vulputate mi sit amet mauris commodo. Amet nulla facilisi morbi tempus. Turpis nunc eget lorem dolor sed viverra ipsum nunc aliquet. Amet tellus cras adipiscing enim eu. Cursus vitae congue mauris rhoncus aenean. Vitae et leo duis ut. Fermentum leo vel orci porta non pulvinar. Aliquam id diam maecenas ultricies mi eget mauris. Turpis in eu mi bibendum neque egestas. Scelerisque fermentum dui faucibus in ornare. Tincidunt tortor aliquam nulla facilisi. Quam viverra orci sagittis eu volutpat odio.

## Recent Blog Posts

{% for post in site.posts limit:3 %}
<article class="post" style="min-height: 0rem">
  <div class="post-content">
    <h2 class="post-title"><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h2>
    <!-- <p>{{ post.content | strip_html | truncatewords: 15 }}</p> -->
    <span class="post-date">{{post.date | date: '%Y, %b %d'}}</span>
  </div>
</article>
{% endfor %}