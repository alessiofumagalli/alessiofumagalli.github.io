---
layout: single
title: "Alessio Fumagalli"
author_profile: false
---

<style>
  .home-hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 2rem;
    margin-top: 0.75rem;
    margin-bottom: 0.5rem;
  }

  .home-hero-text {
    flex: 1 1 65%;
  }

  .home-hero-image {
    flex: 0 0 220px;
    text-align: right;
  }

  .home-hero-image img {
    width: 220px;
    max-width: 100%;
    height: auto;
    border-radius: 10px;
  }

  .home-affiliation {
    margin-top: 0;
    margin-bottom: 0.8rem;
  }

  .home-actions {
    margin-top: 1rem;
  }

  @media (max-width: 768px) {
    .home-hero {
      flex-direction: column-reverse;
      align-items: flex-start;
      gap: 1rem;
    }

    .home-hero-image {
      text-align: left;
    }
  }
</style>

<div class="home-hero">
  <div class="home-hero-text">
    <p class="home-affiliation"><a href="https://www.mate.polimi.it/">Department of Mathematics</a>, <a href="https://www.polimi.it/en">Politecnico di Milano</a></p>
    <p>Welcome to my academic homepage. Here you can find my curriculum vitae, research profile, and education activities.</p>
    <p class="home-actions">
      <a class="btn btn--primary" href="/assets/files/cv.pdf">Download CV (PDF)</a>
      <a class="btn btn--info" href="/research/">View Research</a>
    </p>
  </div>
  <div class="home-hero-image">
    <img src="/assets/images/profile.jpg" alt="Profile picture of Alessio Fumagalli" />
  </div>
</div>
