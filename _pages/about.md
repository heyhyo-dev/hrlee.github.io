---
title: "Hi! I'm heyhyo👋🏻"
permalink: /about/
layout: single
comments: false
---

<style>
  .profile-wrapper {
    margin-top: 1.5rem;

    /* 기본: 왼쪽 정렬 (PC) */
    display: flex;
    flex-direction: column;
    align-items: flex-start;
  }

  .profile-image {
    width: 100%;
    max-width: 420px;
    border-radius: 14px;
    box-shadow: 0 4px 14px rgba(0,0,0,0.12);
  }

  .info-card {
    margin-top: 1.8rem;
    padding: 1.3rem 1.6rem;
    border-radius: 12px;
    background: #ffffff;
    box-shadow: 0 3px 12px rgba(0,0,0,0.08);
    max-width: 420px;
    width: 100%;
  }

  .info-item {
    display: flex;
    align-items: center;
    margin-bottom: 0.8rem;
    font-size: 1rem;
  }

  .info-item i {
    margin-right: 10px;
    font-size: 1.1rem;
    width: 20px;
  }

  .info-item:last-child {
    margin-bottom: 0;
  }

  /* 모바일에서는 자연스럽게 중앙 정렬 */
  @media (max-width: 768px) {
    .profile-wrapper {
      align-items: center;
      text-align: center;
    }
    .info-item {
      justify-content: center;
    }
  }
</style>

<div class="profile-wrapper">

  <img 
    src="/assets/images/Kiki.jpeg" 
    alt="about_meee" 
    class="profile-image"
  />

  <div class="info-card">
    <div class="info-item">
      <i class="fas fa-map-marker-alt"></i> Seoul, Korea
    </div>

    <div class="info-item">
      <i class="fab fa-github"></i>
      <a href="https://github.com/heyhyo-dev" target="_blank">
        github.com/heyhyo-dev
      </a>
    </div>

    <div class="info-item">
      <i class="fas fa-envelope"></i>
      <a href="mailto:hrleesap@gmail.com">hrleesap@gmail.com</a>
    </div>
  </div>

</div>
