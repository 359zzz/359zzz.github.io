<article class="publication-card">
  <div class="publication-media">
    <a href="https://arxiv.org/abs/2608.15026" target="_blank" rel="noopener noreferrer" aria-label="Read PACE on arXiv">
      <img src="static/assets/img/pace.png" alt="PACE framework overview" loading="lazy">
    </a>
  </div>
  <div class="publication-content">
    <h3 class="publication-title">
      <a href="https://arxiv.org/abs/2608.15026" target="_blank" rel="noopener noreferrer">PACE: Phase-Progress-Aware Credit for Long-Horizon Embodied Manipulation</a>
    </h3>
    <p class="publication-authors">Chengye Song*, <strong>Jiawei Zhang</strong>*, Rui Song, Shengqi Wang, Xiangrong Zhang, Ziyi Wang, Huanbin Zhou, Hongzhou Wang</p>
    <p class="publication-venue">* Equal contribution.</p>
    <nav class="publication-links" aria-label="PACE publication links">
      <a href="https://arxiv.org/pdf/2608.15026" target="_blank" rel="noopener noreferrer">pdf</a>
      <span aria-hidden="true">|</span>
      <a class="publication-toggle" href="#pace-abstract" data-target="pace-abstract" aria-controls="pace-abstract" aria-expanded="false">abstract</a>
      <span aria-hidden="true">|</span>
      <a class="publication-toggle" href="#pace-bibtex" data-target="pace-bibtex" aria-controls="pace-bibtex" aria-expanded="false">bibtex</a>
      <span aria-hidden="true">|</span>
      <a href="https://arxiv.org/abs/2608.15026" target="_blank" rel="noopener noreferrer">arXiv</a>
    </nav>
    <div class="publication-detail" id="pace-abstract" hidden>
      <p>Post-training of vision-language-action (VLA) models typically relies on expert demonstrations and policy interaction trajectories. However, in long-horizon manipulation, a single episode often spans hundreds of control steps and multiple phases, while success or failure is only revealed at episode termination. Policy improvement therefore requires step-level credit signals to distinguish behaviors that advance the task from those that stall or regress. We present PACE, a credit-assignment framework for post-training on long-horizon manipulation, centered on a phase-progress-aware critic. PACE consists of two key modules: (1) the Global-Local Cooperative Value-Correction Critic (GLC-Critic) aggregates visual and motion-difference features within local temporal windows to infer the phase and intra-phase progress of each step, and applies residual correction to a discretized remaining-cost distribution accordingly, enabling step-level credit assignment; (2) Progressive Policy Distillation (PPD) converts credit into positive and negative conditions via task-wise thresholds and trains a credit-conditioned action generation policy: it first protects the pretrained policy with high-credit positive samples, then incorporates all positive and negative credits to learn the quality boundary, and at inference amplifies high-credit behaviors through the difference between conditional outputs. Extensive simulation experiments and diverse real-world robotic-arm experiments demonstrate that PACE consistently achieves significant improvements over the strongest baseline.</p>
    </div>
    <div class="publication-detail publication-bibtex" id="pace-bibtex" hidden>
      <pre><code>@article{song2026pace,
  title={PACE: Phase-Progress-Aware Credit for Long-Horizon Embodied Manipulation},
  author={Song, Chengye and Zhang, Jiawei and Song, Rui and Wang, Shengqi and Zhang, Xiangrong and Wang, Ziyi and Zhou, Huanbin and Wang, Hongzhou},
  journal={arXiv preprint arXiv:2608.15026},
  year={2026}
}</code></pre>
    </div>
  </div>
</article>
