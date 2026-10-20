---
layout: default
title: Home
permalink: /
---

<style>
  header, .page-header, .site-header { display: none !important; }
  body { background: #fff !important; max-width: 1173px; margin: 0 auto; padding: 12px 40px 50px; color: #202020; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; line-height: 1.65; }
  .custom-nav { display: flex; justify-content: space-between; align-items: baseline; gap: 16px; border-bottom: 1px solid #eee; padding-bottom: 8px; margin-bottom: 30px; }
  .nav-name { font-size: 1.35em; font-weight: 400; color: #111; }
  .nav-links { display: flex; gap: 28px; font-size: .95em; white-space: nowrap; }
  .nav-links a { color: #444; text-decoration: none; }
  .nav-links a:hover { color: #2e6cb2; }
  .profile-container { margin: 10px 0 35px; text-align: center; }
  .profile-container img { display: block; width: min(310px, 80vw); height: auto; margin: 0 auto; border-radius: 2px; box-shadow: 0 5px 25px rgba(0,0,0,.04); }
  .caption { color: #777; font-size: .88em; margin-top: 12px; }
  h3 { margin-top: 38px; font-size: 1.25em; font-weight: 600; color: #111; }
  hr { border: 0; border-top: 1px solid #f2f2f2; margin: 32px 0; }
  @media (max-width: 650px) { body { padding: 10px 18px 36px; } .custom-nav { flex-wrap: wrap; } .nav-links { gap: 18px; } }
</style>

<nav class="custom-nav" aria-label="Main navigation">
  <span class="nav-name">马先德 (Xiande Ma)</span>
  <span class="nav-links">
    <a href="{{ '/' | relative_url }}" aria-current="page">Home</a>
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
    <a href="{{ '/cv/' | relative_url }}">CV</a>
  </span>
</nav>

<div class="profile-container">
  <img src="{{ '/child.jpg' | relative_url }}" alt="A childhood photograph of Xiande Ma with a telephone" loading="lazy">
  <p class="caption">A long-standing curiosity about how things work.</p>
</div>

### Hello! 👋

I am **Xiande Ma**, a Ph.D. candidate in Materials Science and Engineering at **Northeastern University, China**. I study how rare-earth solutes and atomic-scale defects affect the structure and mechanical response of magnesium alloys.

My work combines **alloy experiments and HAADF-STEM characterization** with **density functional theory, molecular dynamics, and high-throughput structure screening**. I use VASP, LAMMPS, Slurm-based HPC workflows, and Python data analysis to connect observations at grain boundaries with their underlying energetics and deformation behavior.

### Research interests

- Rare-earth magnesium alloys (Mg–Nd, Mg–Sm), grain-boundary segregation, and interface design
- Atomic-scale characterization of defects, dislocations, and phase structures
- DFT and molecular-dynamics simulations; high-throughput structure screening and research computing

### Recent news 📰

- **September 2026:** Our paper on periodic Nd segregation and grain-boundary weakening appeared in *Nano Letters*. [Read the paper](https://doi.org/10.1021/acs.nanolett.6c03381).
- **April 2026:** Our work on a confined two-dimensional Laves tiling in a magnesium alloy appeared in *Nature Communications*. I contributed atomistic simulations and first-principles calculations as a co-corresponding author. [Read the paper](https://doi.org/10.1038/s41467-026-71932-9).
- **December 2024:** Awarded the National Scholarship for Doctoral Students.

See my [selected publications]({{ '/publications/' | relative_url }}) and [curriculum vitae]({{ '/cv/' | relative_url }}).

### Contact {#contact}

**Email:** [maxiande@hotmail.com](mailto:maxiande@hotmail.com)  
**Research group:** Prof. Yuping Ren's group, Northeastern University  
**ORCID:** [0000-0003-0922-0811](https://orcid.org/0000-0003-0922-0811)
