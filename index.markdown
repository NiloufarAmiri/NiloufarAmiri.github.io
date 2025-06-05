---
layout: default
title: "Welcome / Bienvenue"
---

<div class="profile-container">
  <img class="profile-image" src="{{ site.baseurl }}/assets/images/Website.jpg" alt="My Photo" width="200">

  <div class="profile-text">
    <p>I am a PhD student at the Robotics, Mechatronics, and Automation Laboratory (RMAL) at Toronto Metropolitan University. My research focuses on dynamic modeling, vision-based control, design, and optimization of aerial continuum manipulators. I have a strong background in mechanical engineering, holding both a Master’s and a Bachelor’s degree in this exciting field.</p>

    <p>I am passionate about exploring new frontiers and addressing complex challenges in robotics and automation. I enjoy coding, thinking creatively, and continuously expanding my knowledge in computer vision and electrical hardware to make meaningful contributions to this interdisciplinary field.</p>
  </div>
</div>

---

## Connect with Me

- 🔗 [LinkedIn](https://www.linkedin.com/in/niloufar-amiri)
- 📚 [Google Scholar](https://scholar.google.ca/citations?user=kEDzfXMAAAAJ&hl=en)
- 💻 [ResearchGate](https://www.researchgate.net/profile/Niloufar-Amiri-3?ev=hdr_xprf)
- 🤖 [RMAL Website](https://www.torontomu.ca/rmal)

---

## Selected Works

{% for post in site.posts %}
  <article class="post-card">
    <h2>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>
    <p class="post-date">
      {{ post.date | date: "%B %d, %Y" }}
    </p>
  </article>
{% endfor %}
