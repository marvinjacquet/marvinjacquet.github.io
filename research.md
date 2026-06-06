---
layout: default
title: Research
slug: /research
---

<style>
  .pub-section {
    max-width: 720px;
    margin: 0 auto;
    padding-bottom: 60px;
    font-family: Charter, Georgia, Helvetica, Arial, sans-serif;
  }

  .filter-bar {
    display: flex;
    gap: 8px;
    margin-bottom: 40px;
    flex-wrap: wrap;
  }

  .filter-btn {
    font-family: inherit;
    font-size: 0.8em;
    font-weight: 400;
    letter-spacing: 0.05em;
    color: #aaa;
    background: none;
    border: 1px solid #e0e0e0;
    border-radius: 3px;
    padding: 2px 6px;
    white-space: nowrap;
    cursor: pointer;
    transition: all 0.15s;
    text-transform: uppercase;
  }

  .filter-btn:hover {
    border-color: #aaa;
    color: #555;
  }

  .filter-btn.active {
    border-color: #555;
    color: #111;
  }

  .pub-year-group {
    margin-bottom: 36px;
  }

  .pub-year-group.hidden {
    display: none;
  }

  .pub-year {
    font-size: 0.8em;
    font-weight: 400;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #aaa;
    margin-bottom: 8px;
    padding-bottom: 6px;
    border-bottom: 1px solid #aaa;
  }

  .pub-card {
    padding: 12px 0;
    border-bottom: 1px solid #f0f0f0;
  }

  .pub-card:last-child {
    border-bottom: none;
  }

  .pub-card.hidden {
    display: none;
  }

  .pub-card .pub-title {
    font-size: 1.1em;
    font-weight: 400;
    line-height: 1.45;
    margin-bottom: 6px;
    color: #111;
  }

  .pub-card .pub-authors {
    font-size: 0.95em;
    color: #aaa;
    margin-bottom: 6px;
    line-height: 1.5;
  }

  .pub-card .pub-authors .me {
    color: #555;
    font-weight: 400;
  }

  .pub-meta-row {
    display: flex;
    align-items: center;
    gap: 10px;
    flex-wrap: wrap;
  }

  .pub-type-badge {
    font-size: 0.8em;
    font-weight: 400;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #aaa;
    border: 1px solid #e0e0e0;
    border-radius: 3px;
    padding: 2px 6px;
    white-space: nowrap;
  }

  .pub-venue {
    font-size: 0.95em;
    font-style: italic;
    color: #aaa;
    flex: 1;
  }

  .pub-link {
    font-family: inherit;
    font-size: 0.8em;
    font-weight: 400;
    color: #555;
    text-decoration: none;
    border-bottom: 1px solid #555;
    margin-left: auto;
  }

  .pub-link:hover {
    background: #f5f5f5;
  }

  @media (max-width: 600px) {
    .pub-link { margin-left: 0; margin-top: 4px; }
    .pub-meta-row { gap: 6px; }
  }
</style>

<div class="pub-section">

  <div class="filter-bar">
    <button class="filter-btn active" data-filter="all">All</button>
    <button class="filter-btn" data-filter="article">Articles</button>
    <button class="filter-btn" data-filter="talk">Talks</button>
    <button class="filter-btn" data-filter="poster">Posters</button>
  </div>

  <!-- ═══ 2025 ═══ -->
  <div class="pub-year-group" data-year="2025">
    <div class="pub-year">2025</div>

    <div class="pub-card" data-type="article">
      <div class="pub-title">Vigilance and medical devices: from theory to the field, the example of electroporation in atrial fibrillation</div>
      <div class="pub-authors">Salomez-Ihl C, <span class="me">Jacquet M</span>, Quarteroni L, Defaye P, Schmitt D, Py P, Bedouch P</div>
      <div class="pub-meta-row">
        <span class="pub-type-badge">article</span>
        <span class="pub-venue">Expert Review of Medical Devices</span>
        <a class="pub-link" href="https://www.tandfonline.com/doi/full/10.1080/17434440.2025.2463340" target="_blank">link</a>
        <a class="pub-link" href="https://www.tandfonline.com/doi/full/10.1080/17434440.2025.2463340" target="_blank">pdf</a>
      </div>
    </div>
  </div>

  <!-- ═══ 2024 ═══ -->
  <div class="pub-year-group" data-year="2024">
    <div class="pub-year">2024</div>

    <div class="pub-card" data-type="talk">
      <div class="pub-title">Systèmes de fixation de dispositifs médicaux : de l'évaluation des besoins à l'uniformisation des pratiques </div>
      <div class="pub-authors"><span class="me">Jacquet M</span>, Liaigre L, Reymond F, Chapuis C, Chanoine S, Quarteroni L, Py P, Mandaroux S, Pois Pompee P, Le Guen Y, Petiot J, Senellart O, Thevenot M, Salomez-Ihl C, Bedouch P</div>
      <div class="pub-meta-row">
        <span class="pub-type-badge">talk</span>
        <span class="pub-venue">SNPHPU (Montpellier)</span>
        <a class="pub-link" href="https://www.em-consulte.com/article/1683258" target="_blank">pdf</a>
      </div>
    </div>

        <div class="pub-card" data-type="article">
      <div class="pub-title">Calcul de dose en pédiatrie</div>
      <div class="pub-authors">Convert M, <span class="me">Jacquet M</span>, Trochet C, Gibert P, Chanoine S</div>
      <div class="pub-meta-row">
        <span class="pub-type-badge">article</span>
        <span class="pub-venue">La Revue de l'Infirmière</span>
        <a class="pub-link" href="https://www.em-consulte.com/article/1683258" target="_blank">article</a>
      </div>
    </div>
  </div>

  <!-- ═══ 2023 ═══ -->
  <div class="pub-year-group" data-year="2023">
    <div class="pub-year">2023</div>

    <div class="pub-card" data-type="article">
      <div class="pub-title">Early Exposure of Kidney Transplant Recipients with Chronic Antibody-Mediated Rejection to Tocilizumab—A Preliminary Study</div>
      <div class="pub-authors">
        Arrive C, <span class="me">Jacquet M</span>,
        Gautier-Veyret E, Jouve T, Noble J, Lombardo D, Rostaing L, Stanke-Labesque F
      </div>
      <div class="pub-meta-row">
        <span class="pub-type-badge">article</span>
        <span class="pub-venue">Journal of Clinical Medicine</span>
        <a class="pub-link" href="https://www.mdpi.com/2077-0383/12/22/7141" target="_blank">article</a>
      </div>
    </div>
  </div>

  <!-- ═══ 2021 ═══ -->
  <div class="pub-year-group" data-year="2021">
    <div class="pub-year">2021</div>

    <div class="pub-card" data-type="article">
      <div class="pub-title">MALDI-TOF MS in a Medical Mycology Laboratory: On Stage and Backstage</div>
      <div class="pub-authors">Robert MG, Cornet M, Hennebique A, Rasamoelina T, Caspar Y, Ponderand L, Bidart M, Durand H, <span class="me">Jacquet M</span><sup>*</sup>, Garnaud C, Maubon D</div>
      <div class="pub-meta-row">
        <span class="pub-type-badge">article</span>
        <span class="pub-venue">Microorganisms</span>
        <a class="pub-link" href="https://www.mdpi.com/2076-2607/9/6/1283" target="_blank">article</a>
      </div>
    </div>
  </div>

</div>

<script>
  const buttons = document.querySelectorAll('.filter-btn');
  const cards = document.querySelectorAll('.pub-card');
  const groups = document.querySelectorAll('.pub-year-group');

  buttons.forEach(btn => {
    btn.addEventListener('click', () => {
      buttons.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');

      const filter = btn.dataset.filter;

      cards.forEach(card => {
        if (filter === 'all' || card.dataset.type === filter) {
          card.classList.remove('hidden');
        } else {
          card.classList.add('hidden');
        }
      });

      // hide year groups that have no visible cards
      groups.forEach(group => {
        const visible = group.querySelectorAll('.pub-card:not(.hidden)');
        group.classList.toggle('hidden', visible.length === 0);
      });
    });
  });
</script>