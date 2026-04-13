---
layout: about
title: about
permalink: /
subtitle: Postdoctoral researcher in theoretical physics at <a href='https://quantumghent.github.io/'>Ghent University</a>.

profile:
  align: right
  image: FOTOau.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Department of Physics and Astronomy</p>
    <p>Gent, Belgium</p>

news: false # rendered manually in the page body
selected_papers: false # rendered manually in the page body
social: true # includes social icons at the bottom of the page
---

<div class="landing-page">
  <section class="hero-panel">
    <p class="hero-kicker">Tensor networks, critical phenomena, and field theory</p>
    <h2 class="hero-lead">I work on analytical and numerical approaches to strongly correlated and field-theoretic systems.</h2>
    <p class="hero-summary">
      My research focuses on tensor-network methods for critical phenomena, renormalization group flows, and quantum many-body
      physics. Recent work spans finite-entanglement scaling, lattice and gauge-theory problems, and practical tensor-network
      algorithms.
    </p>
    <div class="hero-actions">
      <a class="landing-button primary" href="{{ '/publications/' | relative_url }}">Browse papers</a>
      <a
        class="landing-button"
        href="https://scholar.google.com/citations?user=l2mt3nEAAAAJ"
        target="_blank"
        rel="noopener noreferrer"
      >
        Google Scholar
      </a>
      <a class="landing-button" href="mailto:Atsushi.Ueda@ugent.be">Email</a>
    </div>
  </section>

  <section class="highlight-strip">
    <article class="highlight-card">
      <p class="highlight-label">Current</p>
      <p>Postdoctoral research at Ghent University on tensor-network methods and universal physics.</p>
    </article>
    <article class="highlight-card">
      <p class="highlight-label">Research Themes</p>
      <p>Renormalization group flows, conformal data, finite-size effects, and topological or boundary phenomena.</p>
    </article>
    <article class="highlight-card">
      <p class="highlight-label">Methods</p>
      <p>Tensor network renormalization, matrix-product methods, and practical computational tools for many-body problems.</p>
    </article>
  </section>

  <section class="section-card">
    <h2 class="section-heading">Research directions</h2>
    <p class="section-intro">A few topics that currently shape the work on this site.</p>
    <div class="research-grid">
      <article class="research-card">
        <h3>Tensor network renormalization</h3>
        <p>Algorithms and fixed-point structures that make universal data accessible from lattice models and thermal states.</p>
      </article>
      <article class="research-card">
        <h3>Critical phenomena</h3>
        <p>Finite-size and finite-entanglement effects, conformal signatures, and precision studies of phase transitions.</p>
      </article>
      <article class="research-card">
        <h3>Lattice, gauge, and topological systems</h3>
        <p>Applications to chiral modes, anyon networks, non-orientable geometries, and gauge-theory observables.</p>
      </article>
    </div>
  </section>

  <section class="section-card">
    <div class="section-header-inline">
      <div>
        <h2 class="section-heading"><a href="{{ '/news/' | relative_url }}">Recent papers</a></h2>
        <p class="section-intro">Latest preprints and publication updates from the bibliography.</p>
      </div>
    </div>
    {% include news.liquid limit=true %}
  </section>

  <section class="section-card selected-section">
    <div class="section-header-inline">
      <div>
        <h2 class="section-heading"><a href="{{ '/publications/' | relative_url }}">Selected publications</a></h2>
        <p class="section-intro">A short curated list of papers across tensor network methods, critical systems, and field theory.</p>
      </div>
    </div>
    {% include selected_papers.liquid %}
  </section>
</div>
