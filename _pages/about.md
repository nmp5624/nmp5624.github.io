---
layout: about
title: About
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic_true.jpg
  image_circular: false # crops the image to make it circular

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

Hello and welcome to my website! I'm a sixth-year PhD student in Economics at Penn State University. My research interests lie in the fields of **labor economics** and **theoretical econometrics**.

My recent research in **labor economics** focuses on structural modeling of children's human capital evolution and estimation of causal effects of parental inputs at different stages of child's development.

My recent work in **theoretical econometrics** focuses on the derivation of optimal statistical treatment assignment rules and empirical process theory.

Please see the [Research](/Research/) section of this website for more details.

<p class="job-market">I am on the 2026–2027 job market.</p>

<section class="latest-work" aria-labelledby="latest-work-title">
  <div class="latest-work-header">
    <span class="latest-work-kicker">What's new?</span>
    <span class="latest-work-label">Most recent work</span>
  </div>
  <h2 id="latest-work-title">Finite-Sample Minimax-Regret Treatment Choice with Interval-Observed Outcomes (2026)</h2>
  <p class="latest-work-meta">Working paper</p>
  <details class="latest-work-abstract">
    <summary>Read the abstract</summary>
    <p>Consider a setup where a decision maker has to choose whether to apply treatment to a population after observing a finite sample. Stoye (2009) characterises the solution to the minimax regret problem in this setup when a finite sample consists of actual outcome realizations. However, in many applied problems, instead of the realized outcomes, the decision maker observes only the intervals containing them. We study a finite-sample minimax regret problem in this setting. With no restriction on interval width, assigning treatment with probability 1/2 yields minimax regret. With widths bounded by h0 and h1 in the two arms, we first show that minimax regret converges to (h0+h1)/4 in the limiting experiment and derive a corresponding asymptotically optimal plug-in treatment rule. Then, for h0+h1≥1, we derive an explicit minimax regret rule which attains this value in finite samples. For h0+h1&lt;1, we establish the existence of an optimal treatment rule and characterize it implicitly through a well-behaved finite-dimensional optimization problem. A simulation experiment then shows that the derived analytic rule produces superior finite-sample minimax regret relative to several heuristic alternatives, with the plug-in rule coming very close when the sample size is sufficiently large.</p>
  </details>
  <div class="latest-work-actions">
    <a class="latest-work-primary" href="{{ '/assets/pdf/Minimax_Regret_Bracketed.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">Read the paper <span aria-hidden="true">↗</span></a>
  </div>
</section>

<style>
  .latest-work {
    clear: both;
    position: relative;
    margin: 2.25rem 0 1.75rem;
    padding: 1.55rem 1.65rem 1.45rem;
    overflow: hidden;
    border: 1px solid color-mix(in srgb, var(--global-theme-color) 35%, var(--global-divider-color));
    border-radius: 1rem;
    background:
      radial-gradient(circle at 100% 0, color-mix(in srgb, var(--global-theme-color) 13%, transparent) 0, transparent 44%),
      var(--global-card-bg-color);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.07);
  }

  .latest-work::before {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 4px;
    background: linear-gradient(90deg, var(--global-theme-color), color-mix(in srgb, var(--global-theme-color) 35%, transparent));
    content: "";
  }

  .latest-work-header {
    display: flex;
    align-items: center;
    gap: 0.65rem;
    margin-bottom: 0.75rem;
    font-size: 0.76rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .latest-work-kicker {
    padding: 0.25rem 0.55rem;
    border-radius: 999px;
    background: var(--global-theme-color);
    color: var(--global-bg-color);
  }

  .latest-work-label {
    color: var(--global-text-color-light);
  }

  .latest-work h2 {
    max-width: 780px;
    margin: 0 0 0.35rem;
    font-size: clamp(1.3rem, 2.6vw, 1.75rem);
    line-height: 1.25;
  }

  .latest-work-meta {
    margin: 0 0 1rem;
    color: var(--global-text-color-light);
    font-size: 0.92rem;
  }

  .latest-work-abstract {
    padding: 0.85rem 0;
    border-top: 1px solid var(--global-divider-color);
    border-bottom: 1px solid var(--global-divider-color);
  }

  .latest-work-abstract summary {
    width: max-content;
    cursor: pointer;
    color: var(--global-theme-color);
    font-weight: 650;
  }

  .latest-work-abstract summary:hover {
    text-decoration: underline;
  }

  .latest-work-abstract p {
    margin: 0.8rem 0 0;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
    line-height: 1.65;
  }

  .latest-work-actions {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 0.7rem 1.1rem;
    margin-top: 1.1rem;
  }

  .latest-work-primary {
    display: inline-flex;
    align-items: center;
    gap: 0.35rem;
    font-weight: 650;
  }

  .latest-work-primary {
    padding: 0.62rem 0.9rem;
    border-radius: 0.55rem;
    background: var(--global-theme-color);
    color: var(--global-bg-color);
  }

  .latest-work-primary:hover {
    color: var(--global-bg-color);
    text-decoration: none;
    filter: brightness(0.93);
  }

  @media (max-width: 575.98px) {
    .latest-work {
      padding: 1.35rem 1.15rem 1.25rem;
    }

    .latest-work-header {
      align-items: flex-start;
      flex-direction: column;
      gap: 0.45rem;
    }
  }
</style>
