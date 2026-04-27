---
layout: page
title: about
permalink: /about/
nav: true
nav_order: 1
---

<style>
  .academic-home {
    max-width: 1120px;
    margin: 3.4rem auto 4.5rem auto;
    padding: 0 1.4rem;
  }

  .academic-layout {
    display: grid;
    grid-template-columns: 310px minmax(0, 1fr);
    gap: 4.2rem;
    align-items: start;
  }

  .profile-card {
    text-align: center;
    padding-top: 0.6rem;
  }

  .profile-card img {
    width: 235px;
    height: 235px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 1.55rem;
    box-shadow: 0 10px 28px rgba(0, 0, 0, 0.22);
  }

  .profile-card h1 {
    font-size: 2.15rem;
    font-weight: 400;
    line-height: 1.15;
    margin: 0 0 0.45rem 0;
    color: var(--global-text-color);
  }

  .profile-title {
    font-size: 1.08rem;
    color: var(--global-text-color-light);
    margin-bottom: 0.25rem;
  }

  .profile-affiliation {
    font-size: 1.08rem;
    color: var(--global-theme-color);
    margin-bottom: 1.35rem;
  }

  .profile-social {
    margin-top: 1.25rem;
  }

  .profile-social .social {
    text-align: center;
  }

  .profile-social .contact-icons {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 0.95rem;
    flex-wrap: wrap;
    line-height: 1;
    max-width: 285px;
    margin: 0 auto;
  }

  .profile-social .contact-icons a {
    margin: 0 !important;
    color: var(--global-theme-color) !important;
    transition: color 0.18s ease, transform 0.18s ease;
  }

  .profile-social .contact-icons a:hover {
    color: var(--global-hover-color) !important;
    transform: translateY(-2px);
  }

  .profile-social .contact-icons svg,
  .profile-social .contact-icons i {
    width: 2.05rem !important;
    height: 2.05rem !important;
    font-size: 2.05rem !important;
  }

  .profile-social .contact-note {
    display: none;
  }

  .bio-content {
    font-size: 1.06rem;
    line-height: 1.78;
    color: var(--global-text-color);
  }

  .bio-content p {
    margin-bottom: 1.25rem;
  }

  .bio-content a {
    color: var(--global-theme-color);
  }

  .info-grid {
    display: grid;
    grid-template-columns: 1fr 1.35fr;
    gap: 3.2rem;
    margin-top: 2.7rem;
  }

  .info-block h2 {
    font-size: 1.38rem;
    font-weight: 700;
    margin-bottom: 1rem;
    color: var(--global-text-color);
  }

  .info-block ul {
    padding-left: 1.25rem;
    line-height: 1.8;
    margin-bottom: 0;
  }

  .edu-item {
    display: grid;
    grid-template-columns: 28px 1fr;
    gap: 0.65rem;
    margin-bottom: 1.1rem;
  }

  .edu-item i {
    color: var(--global-theme-color);
    margin-top: 0.28rem;
  }

  .edu-item strong {
    display: block;
    font-weight: 600;
    color: var(--global-text-color);
  }

  .edu-item span {
    display: block;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
    margin-top: 0.12rem;
  }

  @media (max-width: 850px) {
    .academic-layout {
      grid-template-columns: 1fr;
      gap: 2.2rem;
    }

    .profile-card {
      padding-top: 0;
    }

    .info-grid {
      grid-template-columns: 1fr;
      gap: 1.6rem;
    }
  }
</style>

<div class="academic-home">
  <div class="academic-layout">

    <aside class="profile-card">
      <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Mahin Shahriar">

      <h1>Mahin Shahriar</h1>
      <div class="profile-title">Ph.D. Student, Electrical and Computer Engineering</div>
      <div class="profile-affiliation">New York University</div>

      <div class="profile-social">
        {% include social.liquid %}
      </div>
    </aside>

    <main class="bio-content">
      <p>
        I am currently a Ph.D. student in the Department of Electrical and Computer
        Engineering at New York University, working under the supervision of
        Prof. Yuzhang Lin. My research focuses on power distribution systems,
        low-voltage network visibility, smart metering, graph analytics, and
        learning-based voltage estimation.
      </p>

      <p>
        Before joining NYU, I completed my undergraduate studies in Electrical and
        Electronic Engineering at Bangladesh University of Engineering &amp; Technology.
        During that time, I worked under the guidance of Dr. Abdul Hasib Chowdhury on
        fault detection in transmission-line power-system networks, where I explored
        convolutional neural networks and computer vision methods for power-system
        monitoring.
      </p>

      <p>
        My current research investigates how sparse high-reporting-rate smart meters can
        be combined with existing advanced metering infrastructure to improve
        near-real-time voltage visibility in low-voltage distribution networks. I am
        particularly interested in strategic sensor placement, community detection,
        graph neural networks, and data-driven methods that can support reliable and
        intelligent operation of modern distribution grids.
      </p>

      <div class="info-grid">
        <section class="info-block">
          <h2>Interests</h2>
          <ul>
            <li>Power Distribution Systems</li>
            <li>Low-Voltage Network Visibility</li>
            <li>Smart Metering and AMI Data Analytics</li>
            <li>Graph Neural Networks</li>
            <li>AI-Assisted Power System Monitoring</li>
          </ul>
        </section>

        <section class="info-block">
          <h2>Education</h2>

          <div class="edu-item">
            <i class="fa-solid fa-graduation-cap"></i>
            <div>
              <strong>Ph.D. in Electrical and Computer Engineering</strong>
              <span>New York University, current</span>
            </div>
          </div>

          <div class="edu-item">
            <i class="fa-solid fa-graduation-cap"></i>
            <div>
              <strong>B.Sc. in Electrical and Electronic Engineering</strong>
              <span>Bangladesh University of Engineering &amp; Technology</span>
            </div>
          </div>
        </section>
      </div>
    </main>

  </div>
</div>
