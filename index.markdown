---
layout: default
---

<div class="home-page">
  <section class="home-intro" aria-labelledby="home-intro-heading">
    <div class="profile-container">
      <div class="profile-photo-wrap">
        <img class="profile-image" src="{{ '/assets/images/Website.jpg' | relative_url }}" alt="Portrait of Niloufar Amiri" width="200" decoding="async">
      </div>
      <div class="profile-text">
        <h1 class="home-hero-title" id="home-intro-heading">About Me</h1>
        <p>I am a researcher at the Robotics, Mechatronics and Automation Laboratory (RMAL) at Toronto Metropolitan University, working on autonomous hybrid robots that integrate rigid and soft components. My research focuses on understanding the complex interactions between different modules of the robot and controlling their motion through visual feedback.</p>
        <p>Addressing these challenges requires a strong foundation in continuum mechanics and advanced control theory. With a background in mechanical engineering, I have hands-on experience developing experimental robotic platforms, designing physical simulators, and implementing novel control algorithms at different levels.</p>
        <div class="home-research-tags" aria-label="Research interests">
          <span>Continuum Robotics</span>
          <span>Aerial Manipulation</span>
          <span>Visual Servoing</span>
        </div>
      </div>
    </div>
  </section>

  <section class="home-section home-opportunity-card" aria-labelledby="home-opportunity-title">
    <div class="home-opportunity-topline">
      <span class="home-opportunity-label">Research opportunity</span>
    </div>
    <h2 id="home-opportunity-title">Volunteer Research Assistant — Bio-Inspired Soft Robotics</h2>
    <p>Join a hands-on research project at RMAL, Toronto Metropolitan University, involving robot prototyping, experimental testing, and data analysis.</p>
    <div class="home-opportunity-bottomline">
      <span>Undergraduate students · 10 hours/week · 3 months</span>
      <a href="{{ '/opportunities/' | relative_url }}">View opportunity <span aria-hidden="true">↗</span></a>
    </div>
  </section>

  <section class="home-section home-works-section" aria-labelledby="home-works-title">
    <div class="home-section-heading">
      <div>
        <h2 id="home-works-title">Selected Works</h2>
      </div>
      <a class="home-section-link" href="{{ '/publications/' | relative_url }}">All publications <span aria-hidden="true">↗</span></a>
    </div>

    <div class="home-post-list">
    {% for post in site.posts %}
      <article class="post-card">
        <div class="post-thumbnail" aria-hidden="true">
          {{ post.excerpt }}
        </div>
        <div class="post-info">
          <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
          <a class="post-read-more" href="{{ post.url | relative_url }}">Explore this work <span aria-hidden="true">↗</span></a>
        </div>
      </article>
    {% endfor %}
    </div>
  </section>

  <section class="home-section home-connect-section" aria-labelledby="home-connect-title">
    <div class="home-section-heading">
      <div>
        <h2 id="home-connect-title">Connect with Me</h2>
      </div>
    </div>
    <nav class="connect-links" aria-label="Professional and research profiles">
  <a class="connect-link" href="https://www.linkedin.com/in/niloufar-amiri" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn, opens in a new tab">
    <span class="connect-top">
      <span class="connect-icon" aria-hidden="true">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" focusable="false">
          <rect x="2.5" y="2.5" width="19" height="19" rx="3"/>
          <path d="M7.5 10.5v7M7.5 7.5v.2M12 17.5v-7h0v1.2c.7-1 1.6-1.4 2.7-1.4 1.8 0 2.8 1.2 2.8 3.1v4.3M12 13.8v3.7"/>
        </svg>
      </span>
      <span class="connect-arrow" aria-hidden="true">↗</span>
    </span>
    <span class="connect-name">LinkedIn</span>
    <span class="connect-description">Professional profile</span>
  </a>

  <a class="connect-link" href="https://scholar.google.ca/citations?user=kEDzfXMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer" aria-label="Google Scholar, opens in a new tab">
    <span class="connect-top">
      <span class="connect-icon" aria-hidden="true">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" focusable="false">
          <path d="M2.5 9 12 4l9.5 5-9.5 5-9.5-5Z"/>
          <path d="M6.5 11.5V16c3.5 3.1 7.5 3.1 11 0v-4.5M21.5 9v6"/>
        </svg>
      </span>
      <span class="connect-arrow" aria-hidden="true">↗</span>
    </span>
    <span class="connect-name">Google Scholar</span>
    <span class="connect-description">Publications &amp; citations</span>
  </a>

  <a class="connect-link" href="https://www.researchgate.net/profile/Niloufar-Amiri-3?ev=hdr_xprf" target="_blank" rel="noopener noreferrer" aria-label="ResearchGate, opens in a new tab">
    <span class="connect-top">
      <span class="connect-icon" aria-hidden="true">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" focusable="false">
          <circle cx="6" cy="7" r="2.5"/>
          <circle cx="18" cy="7" r="2.5"/>
          <circle cx="12" cy="18" r="2.5"/>
          <path d="m8.4 8.2 2.5 7.3M15.6 8.2l-2.5 7.3M8.5 7h7"/>
        </svg>
      </span>
      <span class="connect-arrow" aria-hidden="true">↗</span>
    </span>
    <span class="connect-name">ResearchGate</span>
    <span class="connect-description">Research network</span>
  </a>

  <a class="connect-link" href="https://www.torontomu.ca/rmal" target="_blank" rel="noopener noreferrer" aria-label="RMAL Website, opens in a new tab">
    <span class="connect-top">
      <span class="connect-icon" aria-hidden="true">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" focusable="false">
          <rect x="4" y="7" width="16" height="13" rx="3"/>
          <path d="M12 3v4M10 3h4M8 12h.01M16 12h.01M8 16c2.2 1.3 5.8 1.3 8 0M2 11v5M22 11v5"/>
        </svg>
      </span>
      <span class="connect-arrow" aria-hidden="true">↗</span>
    </span>
    <span class="connect-name">RMAL Website</span>
    <span class="connect-description">Research laboratory</span>
  </a>
</nav>
  </section>
</div>
