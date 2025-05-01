---
layout: home
---

<div style="text-align: center;">
  <h1 style="margin-bottom: 0.2em;">Welcome</h1>
  <p style="font-size: 1.2em; font-weight: 300;">
    I'm <strong>Ayush Jain</strong>, a researcher and engineer applying machine learning to solve complex problems in science and engineering.
  </p>
</div>

---

<div class="about-section">
  <div class="profile-container">
    <img src="{{ '/assets/images/pic.jpeg' | relative_url }}" alt="Ayush Jain" class="profile-image">
  </div>
  <div class="bio-container">
    <h2>About Me</h2>
    <p>I'm a Ph.D. candidate at Georgia Tech working at the intersection of machine learning, materials informatics, and simulation. My research focuses on building data-driven systems that can reason about molecular & physical structures, predict properties, and guide scientific discovery through automation.</p>
  </div>
</div>

---

## Current Work

### Autonomous Labs for Materials Design  
Designing closed-loop platforms that combine ML models with automated synthesis and characterization to accelerate the discovery and optimization of polymer materials.

### Generative Modeling for Complex Polymer Structures  
Developing deep generative models—including diffusion and flow-matching architectures—to predict realistic atomic-level polymer conformations under structural and stochastic constraints.

### Physics-Informed Techniques for Materials Informatics  
Incorporating physical priors, graph representations, and empirical equations into ML pipelines to improve model interpretability and scientific reliability.

To learn more view my [Publications](/publications).

---

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/j-ayush) or email me at [ayush.jain@gatech.edu](mailto:ayush.jain@gatech.edu).

<style>
  .about-section {
    display: flex;
    align-items: center;
    margin: 2em 0;
    gap: 30px;
  }
  
  .profile-container {
    flex: 0 0 auto;
  }
  
  .profile-image {
    width: 220px;
    height: auto;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    border: 4px solid white;
  }
  
  .bio-container {
    flex: 1;
  }
  
  .bio-container h2 {
    margin-top: 0;
  }
  
  /* Responsive layout - makes it stack on small screens */
  @media (max-width: 768px) {
    .about-section {
      flex-direction: column;
      text-align: center;
    }
    
    .profile-container {
      margin-bottom: 1.5em;
    }
  }
</style>
