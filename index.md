---
layout: home
title: Home
---

<style>
  .post-title {
    display: none;
  }

  .home-layout {
    display: grid;
    grid-template-columns: 320px minmax(0, 1fr);
    align-items: start;
    gap: 2.5rem;
    width: 100%;
  }

  .home-layout img {
    width: 320px;
    max-width: 100%;
    height: auto;
    border-radius: 12px;
  }

  .home-intro p {
    margin-bottom: 1rem;
  }

  @media (max-width: 800px) {
    .home-layout {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="home-layout">
  <img
    src="assets/images/profile.jpg"
    alt="Charlotte's profile photo"
  />

  <div class="home-intro">
    <h1>Charlotte McGinty</h1>
    <p>I am the Geospatial Analyst in the <a href="https://biodiversity-futures-lab.github.io/" target="_blank">Biodiversity Futures Lab</a> at the Natural History Museum in London. My work focuses on developing and applying geospatial workflows to support global biodiversity research.</p>  
    
    <p>My work focuses on processing and analysing large-scale spatial datasets, working with land use and land cover data, and producing reproducible data products that help improve our understanding of biodiversity change in a human-dominated world.</p>

    <p>Before joining the Museum, I worked across a variety of analytical and geospatial roles in the UK Civil Service at Natural England and the Department for Environment, Food and Rural Affairs (Defra), spanning spatial data management, GIS, species licensing, and agricultural statistics.</p>

    <p>I have a background in biology, geography, and environmental science. I completed a BSc in Biology and Geography at the University of St Andrews and an MRes in Ecosystems and Environmental Change at Imperial College London. During my studies, I worked on projects exploring bumblebee populations across urban green spaces and investigating the effects of pesticide exposure and climate change on bumblebee foraging behaviour.</p>
  </div>
</div>
