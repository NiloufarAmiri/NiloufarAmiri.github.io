---
layout: minimal_home
title: "Welcome / Bienvenue"
---

<style>
  .profile-container {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 20px;
    flex-wrap: wrap;
  }

  .profile-image {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    flex-shrink: 0;
  }

  .profile-text {
    flex: 1;
    min-width: 250px;
    text-align: justify;
  }

  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column;
      align-items: flex-start;
    }

    .profile-image {
      width: 100%;
    }

    .profile-text {
      width: 100%;
    }
  }
</style>

<div class="profile-container">
  <img class="profile-image" src="{{ site.baseurl }}/assets/images/Website.jpg" alt="My Photo" width="200">

  <div class="profile-text">
    <p>I am a PhD student at the Robotics, Mechatronics, and Automation Laboratory (RMAL) at Toronto Metropolitan University. My research focuses on dynamic modeling, vision-based control, design, and optimization of aerial continuum manipulators. I have a strong background in mechanical engineering, holding both a Master’s and a Bachelor’s degree in this exciting field.</p>

    <p>I am passionate about exploring new frontiers and addressing complex challenges in robotics and automation. I enjoy coding, thinking creatively, and continuously expanding my knowledge in computer vision and electrical hardware to make meaningful contributions to this interdisciplinary field.</p>
  </div>
</div>


---

- 🔗 [LinkedIn](https://www.linkedin.com/in/niloufar-amiri)
- 📚 [Google Scholar](https://scholar.google.ca/citations?user=kEDzfXMAAAAJ&hl=en)
- 💻 [ResearchGate](https://www.researchgate.net/profile/Niloufar-Amiri-3?ev=hdr_xprf)
- 🤖 [RMAL Website](https://www.torontomu.ca/rmal)

---

{% for post in site.posts %}
  <div style="display: flex; align-items: center; gap: 20px; margin-bottom: 20px;">
    {{ post.excerpt }}
    <div>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </div>
  </div>
{% endfor %}

---