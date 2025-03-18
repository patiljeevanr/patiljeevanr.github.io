---
layout: default
title: "Home"
---

<div class="container">

  <section id="about" class="card">
      <h2>About</h2>
      <p>Software Engineer passionate about Java, Go, Couchbase, and distributed systems.</p>
  </section>

  <section id="projects" class="card">
      <h2>Projects</h2>
          <ul>
              {% for project in site.projects limit:3 %}
                  <li><a href="{{ project.url }}">{{ project.title }}</a></li>
              {% endfor %}
          </ul>
      <p><a href="/projects">View All Projects</a></p>
  </section>

  <section id="blog" class="card">
      <h2>Blog</h2>
      <p>Explore my thoughts on technology and personal experiences.</p>
      <ul>
          <li><a href="blog/tech">Tech Blogs</a></li>
          <li><a href="blog/personal">Personal Blogs</a></li>
      </ul>
  </section>

  <section id="contact" class="card">
      <h2>Contact</h2>
      <p>Reach me via <a href="mailto:patiljeevanr@gmail.com">Email</a> | <a href="https://www.linkedin.com/in/patiljeevanr/">LinkedIn</a></p>
  </section>

</div>
