---
layout: default
title: Vivien Ebert
---

<style>
  :root {
    --kit-green: #00876c;
    --kit-green-dark: #006652;
    --text-primary: #1f2937;
    --text-secondary: #4b5563;
    --bg-subtle: #f8fafc;
    --border-color: #e2e8f0;
  }

  /* Clean up default Minima chrome for a more academic look */
  .site-header {
    border-top: 4px solid var(--kit-green);
    border-bottom: 1px solid var(--border-color);
    background-color: #ffffff;
  }
  .site-title {
    font-family: "Georgia", "Times New Roman", serif;
    font-weight: 700 !important;
    color: var(--text-primary) !important;
    letter-spacing: -0.3px;
  }
  .site-footer {
    display: none;
  }

  .academic-container {
    max-width: 780px;
    margin: 1.5rem auto 3rem auto;
    color: var(--text-primary);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    line-height: 1.7;
  }

  /* Top Section: Picture & Affiliation Side-by-Side */
  .profile-header {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 2.5rem;
    padding-bottom: 2.25rem;
    border-bottom: 1px solid var(--border-color);
    margin-bottom: 2.25rem;
  }

  .profile-photo-wrapper {
    flex-shrink: 0;
  }

  .profile-photo {
    width: 190px;
    height: 190px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid var(--border-color);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    background-color: var(--bg-subtle);
  }

  .profile-affiliation h1 {
    font-family: "Georgia", "Times New Roman", serif;
    font-size: 2.1rem;
    font-weight: 700;
    margin: 0 0 0.4rem 0;
    color: var(--text-primary);
  }

  .profile-role {
    font-size: 1.15rem;
    font-weight: 600;
    color: var(--kit-green);
    margin-bottom: 0.75rem;
  }

  .affiliation-details {
    font-size: 1rem;
    color: var(--text-secondary);
    margin: 0;
    line-height: 1.6;
  }

  .affiliation-details a,
  .academic-section a {
    color: var(--kit-green);
    text-decoration: none;
    font-weight: 500;
    border-bottom: 1px solid transparent;
    transition: border-color 0.2s ease, color 0.2s ease;
  }

  .affiliation-details a:hover,
  .academic-section a:hover {
    color: var(--kit-green-dark);
    border-bottom-color: var(--kit-green-dark);
  }

  /* Content Sections Underneath */
  .academic-section {
    margin-bottom: 2.25rem;
  }

  .academic-section h2 {
    font-family: "Georgia", "Times New Roman", serif;
    font-size: 1.35rem;
    font-weight: 700;
    color: var(--text-primary);
    margin-bottom: 0.85rem;
    padding-bottom: 0.35rem;
    border-bottom: 2px solid var(--bg-subtle);
  }

  .academic-section p {
    margin-bottom: 0.85rem;
    color: var(--text-primary);
  }

  .interest-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-top: 1rem;
  }

  .interest-tag {
    background-color: var(--bg-subtle);
    border: 1px solid var(--border-color);
    color: var(--text-secondary);
    padding: 0.3rem 0.8rem;
    border-radius: 999px;
    font-size: 0.9rem;
    font-weight: 500;
  }

  /* Contact Box */
  .contact-card {
    background-color: var(--bg-subtle);
    border: 1px solid var(--border-color);
    border-left: 4px solid var(--kit-green);
    border-radius: 6px;
    padding: 1.25rem 1.5rem;
  }

  .contact-grid {
    display: grid;
    grid-template-columns: 95px 1fr;
    row-gap: 0.5rem;
    font-size: 0.98rem;
  }

  .contact-label {
    font-weight: 600;
    color: var(--text-secondary);
  }

  /* Bottom Links Section */
  .bottom-links-section {
    margin-top: 2.5rem;
    padding-top: 1.75rem;
    border-top: 1px solid var(--border-color);
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    align-items: center;
  }

  .btn-academic {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.6rem 1.2rem;
    border-radius: 6px;
    font-size: 0.95rem;
    font-weight: 600;
    text-decoration: none !important;
    transition: all 0.2s ease;
  }

  .btn-primary {
    background-color: var(--kit-green);
    color: #ffffff !important;
    border: 1px solid var(--kit-green);
  }

  .btn-primary:hover {
    background-color: var(--kit-green-dark);
    border-color: var(--kit-green-dark);
  }

  .btn-outline {
    background-color: #ffffff;
    color: var(--text-primary) !important;
    border: 1px solid var(--border-color);
  }

  .btn-outline:hover {
    border-color: var(--kit-green);
    color: var(--kit-green) !important;
    background-color: var(--bg-subtle);
  }

  /* Responsive adjustments for mobile screens */
  @media (max-width: 600px) {
    .profile-header {
      flex-direction: column;
      text-align: center;
      gap: 1.25rem;
    }
    .contact-grid {
      grid-template-columns: 1fr;
      row-gap: 0.2rem;
    }
    .contact-label {
      margin-top: 0.4rem;
    }
    .bottom-links-section {
      justify-content: center;
    }
  }
</style>

<div class="academic-container">

<div class="profile-header">
  <div class="profile-photo-wrapper">
    <img src="{{ '/assets/profile.jpg' | relative_url }}" alt="Vivien Ebert" class="profile-photo" />
  </div>
  <div class="profile-affiliation">
    <h1>Vivien Ebert</h1>
    <div class="profile-role">Doctoral Researcher</div>
    <p class="affiliation-details">
      <a href="https://logic.kastel.kit.edu/" target="_blank" rel="noopener">Logic of Autonomous Dynamical Systems</a><br />
      Supervised by Prof. Dr. André Platzer<br />
      KASTEL – Institute of Information Security and Dependability<br />
      Karlsruhe Institute of Technology (KIT)
    </p>
  </div>
</div>

<div class="academic-section">
  <h2>Research Interests</h2>
  <p>
    I am a first-year doctoral researcher at the Karlsruhe Institute of Technology (KIT) in the <a href="https://logic.kastel.kit.edu/" target="_blank" rel="noopener">Logic of Autonomous Dynamical Systems</a> group under the supervision of Prof. Dr. André Platzer. Previously, I graduated in Mathematics at KIT, where I specialized in Differential Geometry.
  </p>
  <p>
    I am interested in bridging the gap between mathematics and logic. In particular, my research lies at the interface of <strong>Differential Dynamic Logic</strong> and <strong>Differential Geometry</strong>.
  </p>
  <div class="interest-tags">
    <span class="interest-tag">Differential Dynamic Logic</span>
    <span class="interest-tag">Differential Geometry</span>
    <span class="interest-tag">Formal Verification</span>
    <span class="interest-tag">Hybrid &amp; Dynamical Systems</span>
  </div>
</div>

<div class="academic-section">
  <h2>Contact</h2>
  <div class="contact-card">
    <div class="contact-grid">
      <div class="contact-label">Email:</div>
      <div><a href="mailto:vivien.ebert@kit.edu">vivien.ebert@kit.edu</a></div>
      <div class="contact-label">Office:</div>
      <div>Room 158, Building 50.34</div>
      <div class="contact-label">Address:</div>
      <div>Am Fasanengarten 5, 76131 Karlsruhe, Germany</div>
    </div>
  </div>
</div>

<div class="bottom-links-section">
  <a href="{{ '/assets/master_thesis.pdf' | relative_url }}" class="btn-academic btn-primary" target="_blank" rel="noopener">
    📄 Master's Thesis (PDF)
  </a>
  <a href="https://www.linkedin.com/in/vivien-ebert-6543411b8" class="btn-academic btn-outline" target="_blank" rel="noopener">
    🔗 LinkedIn Profile
  </a>
</div>

</div>