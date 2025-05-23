layout: home
title: ""
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
    <p>I'm a Ph.D. candidate at Georgia Tech working at the intersection of machine learning, materials informatics, and simulation advised by <a href="https://ramprasad.mse.gatech.edu/" target="_blank">Prof. Rampi Ramprasad</a>. My research focuses on building data-driven systems that can reason about molecular & physical structures, predict properties, and guide scientific discovery through automation.</p>

  </div>
</div>

---

<div class="work-visual-section">
  <h2>Visual Overview of My Work</h2>
  <img src="{{ '/assets/images/work_viz.jpg' | relative_url }}" alt="Visual overview of Ayush Jain's work" class="work-visual-image">
</div>

---

## Current Work

### Autonomous Labs for Materials Design  
Designing closed-loop platforms that combine ML models with automated synthesis and characterization to accelerate the discovery and optimization of polymer materials.

### Generative Modeling for Complex Polymer Structures  
Developing latent space gaussian flow matching models to predict realistic atomic-level polymer conformations under structural and stochastic constraints.

### Physics-Informed Techniques for Materials Informatics  
Incorporating physical priors, graph representations, and empirical equations into ML pipelines to improve model interpretability and scientific reliability.

To learn more view my [Publications](/publications).

---

<div class="contact-section">
  <h2>Contact</h2>
  <p>Feel free to reach out on <a href="https://www.linkedin.com/in/j-ayush" target="_blank">LinkedIn</a> or email me at <a href="mailto:ayush.jain@gatech.edu">ayush.jain@gatech.edu</a>.</p>
</div>

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
  
  .button-container {
    text-align: center;
    margin: 2em 0;
  }
  
  .view-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #3498db;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s;
  }
  
  .view-button:hover {
    background-color: #2980b9;
    text-decoration: none;
    color: white;
  }
  
  .contact-section {
    background-color: #f8f9fa;
    padding: 2em;
    border-radius: 8px;
    text-align: center;
    margin-bottom: 2em;
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
  
  .work-visual-section {
    text-align: center;
    margin: 2em 0 2em 0;
  }
  .work-visual-section h2 {
    margin-bottom: 1em;
    color: #2c3e50;
  }
  .work-visual-image {
    max-width: 90%;
    height: auto;
    border-radius: 12px;
    box-shadow: 0 4px 16px rgba(0,0,0,0.12);
    border: 2px solid #e0e0e0;
  }
</style>
