---
layout: home
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
## Connect with Me

- 🔗 [LinkedIn](https://www.linkedin.com/in/niloufar-amiri)
- 📚 [Google Scholar](https://scholar.google.ca/citations?user=kEDzfXMAAAAJ&hl=en)
- 💻 [ResearchGate](https://www.researchgate.net/profile/Niloufar-Amiri-3?ev=hdr_xprf)
- 🤖 [RMAL Website](https://www.torontomu.ca/rmal)

---

## Selected Works

{% for post in site.posts %}
  <article style="padding: 20px; border-radius: 12px; box-shadow: 0 2px 8px rgba(162, 217, 231, 0.1); margin-bottom: 30px; background-color: #fff;">
    <h2 style="margin-top: 0;">
      <a href="{{ post.url | relative_url }}" style="text-decoration: none; color: #333;">
        {{ post.title }}
      </a>
    </h2>
    <p style="color: #888; font-size: 0.9em; margin-top: -10px;">{{ post.date | date: "%B %d, %Y" }}</p>
    <div style="margin-top: 10px;">
      {{ post.excerpt }}
    </div>
  </article>
{% endfor %}
