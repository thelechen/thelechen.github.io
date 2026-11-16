---
layout: page
title: SC26
permalink: /sc26/
description: Audience instructions for the OpenCode exercises in SC26 Tutorial Section 6
nav: true
nav_order: 5
_styles: >
  .sc26-hub {
    --sc26-purple: #6f42c1;
    --sc26-cyan: #007f86;
    --sc26-soft-purple: rgba(111, 66, 193, 0.1);
    --sc26-soft-cyan: rgba(0, 127, 134, 0.1);
  }
  .post > .post-header {
    display: none;
  }
  .sc26-hub .sc26-hero {
    margin: 0 0 2.25rem;
    padding: clamp(1.5rem, 4vw, 2.75rem);
    border: 1px solid var(--global-divider-color);
    border-radius: 1rem;
    background: linear-gradient(135deg, var(--sc26-soft-purple), var(--sc26-soft-cyan));
  }
  .sc26-hub .sc26-eyebrow {
    margin: 0 0 0.65rem;
    color: var(--global-theme-color);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.11em;
    text-transform: uppercase;
  }
  .sc26-hub .sc26-hero h2 {
    margin: 0;
    max-width: 760px;
    font-size: clamp(1.7rem, 4vw, 2.65rem);
    line-height: 1.12;
  }
  .sc26-hub .sc26-lead {
    max-width: 720px;
    margin: 1rem 0 0;
    color: var(--global-text-color-light);
    font-size: 1.05rem;
  }
  .sc26-hub .sc26-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.7rem;
    margin-top: 1.35rem;
  }
  .sc26-hub .sc26-button {
    display: inline-flex;
    align-items: center;
    gap: 0.45rem;
    padding: 0.62rem 0.9rem;
    border: 1px solid var(--global-theme-color);
    border-radius: 0.55rem;
    font-weight: 600;
    text-decoration: none;
  }
  .sc26-hub .sc26-button-primary {
    color: var(--global-bg-color) !important;
    background: var(--global-theme-color);
  }
  .sc26-hub .sc26-button-secondary {
    color: var(--global-theme-color) !important;
    background: var(--global-bg-color);
  }
  .sc26-hub .sc26-route {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 0.6rem;
    margin: 0 0 2.75rem;
    padding: 0;
    list-style: none;
  }
  .sc26-hub .sc26-route a {
    display: block;
    height: 100%;
    padding: 0.85rem;
    border-top: 3px solid var(--global-theme-color);
    background: var(--global-card-bg-color);
    color: var(--global-text-color);
    font-size: 0.9rem;
    text-decoration: none;
  }
  .sc26-hub .sc26-route strong {
    display: block;
    margin-bottom: 0.2rem;
    color: var(--global-theme-color);
    font-size: 0.75rem;
    letter-spacing: 0.07em;
    text-transform: uppercase;
  }
  .sc26-hub .sc26-step {
    display: grid;
    grid-template-columns: 3.2rem minmax(0, 1fr);
    gap: 1rem;
    margin: 0 0 3.25rem;
    scroll-margin-top: 6rem;
  }
  .sc26-hub .sc26-step-number {
    display: flex;
    width: 3.2rem;
    height: 3.2rem;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    background: var(--global-theme-color);
    color: var(--global-bg-color);
    font-size: 1.1rem;
    font-weight: 800;
  }
  .sc26-hub .sc26-step h2 {
    margin-top: 0.25rem;
  }
  .sc26-hub .sc26-step > div,
  .sc26-hub .sc26-track {
    min-width: 0;
  }
  .sc26-hub pre {
    max-width: 100%;
    overflow-x: auto;
  }
  .sc26-hub code {
    overflow-wrap: anywhere;
  }
  .sc26-hub pre code {
    overflow-wrap: normal;
  }
  .sc26-hub .sc26-note {
    margin: 1.2rem 0;
    padding: 0.95rem 1.05rem;
    border-left: 4px solid var(--global-theme-color);
    background: var(--global-card-bg-color);
  }
  .sc26-hub .sc26-note p:last-child {
    margin-bottom: 0;
  }
  .sc26-hub .sc26-track-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    margin-top: 1.25rem;
  }
  .sc26-hub .sc26-track {
    padding: 1.15rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 0.8rem;
    background: var(--global-card-bg-color);
  }
  .sc26-hub .sc26-track-bcp {
    border-top: 4px solid var(--sc26-purple);
  }
  .sc26-hub .sc26-track-para {
    border-top: 4px solid var(--sc26-cyan);
  }
  .sc26-hub .sc26-track h3 {
    margin-top: 0;
  }
  .sc26-hub .sc26-command {
    display: inline-block;
    margin: 0.3rem 0 0.75rem;
    padding: 0.35rem 0.55rem;
    border-radius: 0.4rem;
    background: var(--global-code-bg-color);
    color: var(--global-theme-color);
    font-family: var(--font-mono, monospace);
    font-weight: 700;
  }
  .sc26-hub .sc26-result-list {
    margin-bottom: 0;
    padding-left: 1.15rem;
  }
  .sc26-hub .sc26-result-list li {
    margin-bottom: 0.55rem;
  }
  .sc26-hub .sc26-success {
    margin-top: 1rem;
    padding: 0.85rem 1rem;
    border-radius: 0.55rem;
    background: rgba(30, 138, 75, 0.11);
  }
  .sc26-hub .sc26-footer-checks {
    margin-top: 2.5rem;
    padding-top: 1.5rem;
    border-top: 1px solid var(--global-divider-color);
  }
  @media (max-width: 760px) {
    .sc26-hub .sc26-route,
    .sc26-hub .sc26-track-grid {
      grid-template-columns: 1fr;
    }
    .sc26-hub .sc26-step {
      grid-template-columns: 1fr;
      gap: 0.35rem;
    }
    .sc26-hub .sc26-step-number {
      width: 2.55rem;
      height: 2.55rem;
      font-size: 0.95rem;
    }
  }
---

<div class="sc26-hub">

<section class="sc26-hero" aria-labelledby="sc26-hero-title">
  <p class="sc26-eyebrow">SC26 Tutorial · Section 6</p>
  <h2 id="sc26-hero-title">OpenCode hands-on instructions</h2>
  <p class="sc26-lead">Set up OpenCode once, then run two small end-to-end exercises: verified Fortran-to-C++ translation with Beyond Code Pairs, and correctness-gated OpenMP parallelization with ParaCodex.</p>
  <div class="sc26-actions">
    <a class="sc26-button sc26-button-primary" href="#install"><i class="ti ti-rocket" aria-hidden="true"></i> Start setup</a>
    <a class="sc26-button sc26-button-secondary" href="https://opencode.ai/docs" target="_blank" rel="noopener"><i class="ti ti-external-link" aria-hidden="true"></i> OpenCode docs</a>
  </div>
</section>

<ol class="sc26-route" aria-label="Hands-on steps">
  <li><a href="#install"><strong>Step 1</strong>Install OpenCode and select a model</a></li>
  <li><a href="#clone"><strong>Step 2</strong>Clone both exercise repositories</a></li>
  <li><a href="#run"><strong>Step 3</strong>Run each command in OpenCode</a></li>
  <li><a href="#results"><strong>Step 4</strong>Read code, tests, and transcripts</a></li>
</ol>

<section class="sc26-step" id="install">
  <div class="sc26-step-number" aria-hidden="true">01</div>
  <div>
    <h2>Install OpenCode and select a model</h2>
    <p>Install the OpenCode CLI using the official installer, then confirm that the command is available:</p>

<pre><code class="language-bash">curl -fsSL https://opencode.ai/v2/install | bash
opencode --version</code></pre>

    <p>Homebrew, npm, desktop, and standalone installers are also listed in the <a href="https://opencode.ai/docs" target="_blank" rel="noopener">official installation guide</a>.</p>

    <p>Start OpenCode in a terminal. If a provider or sign-in is required, connect it first. Then open the model selector:</p>

<pre><code class="language-text">/connect
/models</code></pre>

    <p>Choose an available model marked <strong>Free</strong>, or another model supplied by your provider. Free-model availability can change, so select from the live list instead of using a model name from this page. The selection applies to the current session, and both exercises inherit it.</p>

    <div class="sc26-note">
      <p><strong>Local prerequisites</strong></p>
      <p>Beyond Code Pairs requires Python 3.9+, <code>gfortran</code>, and <code>g++</code>. ParaCodex requires Python 3 and a C++17 compiler with OpenMP support. On macOS, use Homebrew GCC for real OpenMP rather than Apple Clang.</p>
    </div>
  </div>
</section>

<section class="sc26-step" id="clone">
  <div class="sc26-step-number" aria-hidden="true">02</div>
  <div>
    <h2>Clone both repositories</h2>
    <p>Use a new working directory so the exercises stay separate from your own projects:</p>

<pre><code class="language-bash">mkdir sc26-hands-on
cd sc26-hands-on

git clone https://github.com/thelechen/beyond-code-pairs-translation.git
git clone https://github.com/thelechen/ParaCodex.git</code></pre>

    <p>Each repository contains a self-contained <code>SC26</code> directory. Start OpenCode from that directory so it can discover the project commands under <code>.opencode/commands/</code>.</p>

    <div class="sc26-actions">
      <a class="sc26-button sc26-button-secondary" href="https://github.com/thelechen/beyond-code-pairs-translation" target="_blank" rel="noopener">Beyond Code Pairs repository</a>
      <a class="sc26-button sc26-button-secondary" href="https://github.com/thelechen/ParaCodex" target="_blank" rel="noopener">ParaCodex repository</a>
    </div>
  </div>
</section>

<section class="sc26-step" id="run">
  <div class="sc26-step-number" aria-hidden="true">03</div>
  <div>
    <h2>Run the exercises in OpenCode</h2>
    <p>Run one exercise at a time. The normal command may pass on its first attempt; the optional repair command provides a clearly labelled, instructor-injected failure for observing the repair loop.</p>

    <div class="sc26-track-grid">
      <article class="sc26-track sc26-track-bcp">
        <h3>Beyond Code Pairs</h3>
        <p>A Questioner proposes tests, a Solver translates Fortran to C++, and an independent harness compiles and compares numerical output.</p>

<pre><code class="language-bash">cd sc26-hands-on/beyond-code-pairs-translation/SC26
make clean
opencode</code></pre>

        <p>At the OpenCode prompt, enter:</p>
        <span class="sc26-command">/bcp-demo</span>
        <p>After a successful run, optionally enter <code>/bcp-repair</code> to observe a guaranteed test failure and repair.</p>
      </article>

      <article class="sc26-track sc26-track-para">
        <h3>ParaCodex</h3>
        <p>An Analyzer plans the parallelization, a Solver writes OpenMP code, and an independent gate checks compilation, numerical equivalence, and active OpenMP.</p>

<pre><code class="language-bash">cd sc26-hands-on/ParaCodex/SC26
make clean
opencode</code></pre>

        <p>At the OpenCode prompt, enter:</p>
        <span class="sc26-command">/paracodex-demo</span>
        <p>Optionally enter <code>/paracodex-repair</code> to observe the seeded numerical failure, reviewer feedback, and repair.</p>
      </article>
    </div>

    <div class="sc26-note">
      <p><strong>Starting over</strong></p>
      <p>Exit OpenCode, run <code>make clean</code> from the relevant <code>SC26</code> directory, and reopen <code>opencode</code>. Copy the run directory elsewhere first if you want to keep an earlier result.</p>
    </div>
  </div>
</section>

<section class="sc26-step" id="results">
  <div class="sc26-step-number" aria-hidden="true">04</div>
  <div>
    <h2>Read the results</h2>
    <p>Do not judge success from the final code alone. Read the generated plan, exact candidate, independent test report, and repair history together.</p>

    <div class="sc26-track-grid">
      <article class="sc26-track sc26-track-bcp">
        <h3>Beyond Code Pairs results</h3>
        <p><code>tutorial_demo/opencode_e2e/runs/opencode_latest/</code></p>
        <ul class="sc26-result-list">
          <li><code>questioner_plan.md</code>: requested behavior and extra tests</li>
          <li><code>candidate_attempt_XX.cpp</code>: exact C++ submitted at each attempt</li>
          <li><code>test_attempt_XX.json</code>: compiler and case-by-case numerical evidence</li>
          <li><code>questioner_feedback_XX.md</code>: targeted feedback after a failure</li>
          <li><code>transcript.md</code> and <code>events.jsonl</code>: readable and structured run histories</li>
        </ul>
        <p class="sc26-success"><strong>Success:</strong> the latest test report contains <code>"overall_pass": true</code>.</p>
      </article>

      <article class="sc26-track sc26-track-para">
        <h3>ParaCodex results</h3>
        <p><code>tutorial_demo/paracodex_opencode/</code></p>
        <ul class="sc26-result-list">
          <li><code>work/analysis.md</code> and <code>work/data_plan.md</code>: dependency and data-movement reasoning</li>
          <li><code>work/candidate.cpp</code>: current generated OpenMP implementation</li>
          <li><code>runs/latest/attempt_XX.json</code>: compilation, numerical checks, and OpenMP status</li>
          <li><code>runs/latest/candidate_attempt_XX.cpp</code>: exact source tested at each gate</li>
          <li><code>runs/latest/performance.json</code> and <code>transcript.md</code>: timing evidence and run recap</li>
        </ul>
        <p class="sc26-success"><strong>Success:</strong> look for <code>PASS_NUMERICS</code> and <code>OPENMP_ACTIVE</code>. <code>NOT_PROVEN_PARALLEL</code> means the compiler fell back to serial execution or no active OpenMP loop was established.</p>
      </article>
    </div>

    <div class="sc26-footer-checks">
      <h3>Before leaving the session</h3>
      <ul>
        <li>Compare the first candidate with the final candidate.</li>
        <li>Identify which compiler or numerical evidence triggered each repair.</li>
        <li>For ParaCodex, distinguish correctness from performance: a correct parallel version can still be slower.</li>
      </ul>
    </div>
  </div>
</section>

</div>
