---
layout: page
title: 
permalink: /research/
---

<!-- 🔗 Jump Links -->
<div style="text-align:center; font-size:1.3em; margin: 1.5em 0;">
  <a href="#my-motivation"> Research Topics</a> | <a href="#publications"> Publications</a> | <a href="#thesis-topics"> Thesis Topics</a> | <a href="#misc">  Misc</a>
</div>


---

<div style="text-align:center;">
  <h2 id="my-motivation">🧠 Research Topics </h2>
</div>
<div style="display:flex; align-items:flex-start; gap:20px; margin-top:1em;">
  <div style="flex:2;">
<p>
  My research focuses on improving and understanding the 
  <strong>trustworthiness of AI architectures</strong>. I am particularly interested in the interplay between 
  <strong>robustness, security, and efficiency</strong>, exploring how we can design AI systems 
  that are both powerful and reliable under real-world constraints. Some of the central questions driving my work include:
  </p>
    <ul>
      <li>🛡️ <strong>safety and security AI threats and countermeasures</strong>, with a focus on adversarial robustness and out of distribution samples in computer vision and natural language processing.</li>
      <li>🔍 <strong>Explainability and uncertainty estimation</strong> as tools to strengthen trust in AI decisions and to better interpret feature patterns in large and complex vision and NLP models.</li>
      <li>🚦 <strong>Risk-aware metrics</strong> to evaluate failures of AI in safety-critical domains such as autonomous driving or healthcare.</li>
    </ul>
</div>
</div>

<!--  <li>🤝 <strong>Secure AI collaboration</strong>, both between humans and AI, and among distributed AI models that must remain trustworthy.</li> -->
<!-- <li>⚡ <strong>Computational efficiency and sustainability</strong> of large models, including offloading strategies and early-exit paradigms.</li> -->
<!-- Quote Box -->
<div style="text-align:center; margin: 2em auto; font-style: italic; max-width:1000px; border:2px solid #ccc; padding:1.5em; border-radius:8px; background-color:#fafafa;">
  <p>
    “Any technological advance can be dangerous. Fire was dangerous from the start, and so (even more so) was speech — 
    and both are still dangerous to this day — but human beings would not be human without them.”
  </p>
  <p style="margin-top:1em; font-weight:bold;">— Isaac Asimov, The Caves of Steel</p>
</div>




---


<div style="text-align:center;">
  <h2 id="publications">📄 Publications</h2>
</div>


For a complete and updated list of my publications, please visit:
[Google Scholar](https://scholar.google.com/citations?user=1NwO40wAAAAJ&hl=it) ·
[Semantic Scholar](https://www.semanticscholar.org/author/Giulio-Rossolini/2047404065)

<!-- =========================
     OPTION A — NO PLUGINS
     Uses _data/publications.yml
     ========================= -->

<!-- =========================
     OPTION A — NO PLUGINS
     Uses _data/publications.yml
     ========================= -->
{% comment %} Remove this block if you use Option B {% endcomment %}
{% assign pubs = site.data.publications | sort: "year" | reverse %}
{% assign pubs_by_year = pubs | group_by: "year" %}


<ul class="pub-list">
  {% for year_group in pubs_by_year %}
  <li>
    <h3>{{ year_group.name }}</h3>
    <ol>
      {% for p in year_group.items %}
      <li class="pub-item">
        <span class="pub-title"><strong>{{ p.title }}</strong></span><br/>
        <span class="pub-authors">{{ p.authors }}</span><br/>
        <span class="pub-venue"><em>{{ p.venue }}</em></span>
        {% if p.extra %} <span class="pub-extra">{{ p.extra }}</span>{% endif %}
        {% if p.doi %} · <a href="https://doi.org/{{ p.doi }}" target="_blank" rel="noopener">DOI</a>{% endif %}
        {% if p.arxiv %} · <a href="https://arxiv.org/abs/{{ p.arxiv }}" target="_blank" rel="noopener">Link</a>{% endif %}
        {% if p.link %} · <a href="{{ p.link }}" target="_blank" rel="noopener">Link</a>{% endif %}
        {% if p.bibtex %} · <a href="{{ p.bibtex }}" target="_blank" rel="noopener">BibTeX</a>{% endif %}
      </li>
      {% endfor %}
    </ol>
  </li>
  {% endfor %}
</ul>


---


<div style="text-align:center;">
  <h2 id="thesis-topics">🎓 Thesis Topics</h2>
</div>



For available master's and doctoral thesis projects, please contact me.  
Projects span a range of research areas, including (but not limited to) the following:

<!-- From _data/thesis_topics.yml -->
<ul>
{% for t in site.data.thesis_topics %}
  <li>
    <strong>{{ t.name }}</strong>
    {% if t.description %}<br/><span class="text-sm">{{ t.description }}</span>{% endif %}
  </li>
{% endfor %}
</ul>

<style>
  .pub-list { list-style: none; padding-left: 0; }
  .pub-item { margin-bottom: 0.8rem; }
  .text-sm { font-size: 0.95rem; color: #444; }
</style>

---

<div style="text-align:center;">
  <h2 id="misc">📌 Misc (Awards, Career & Services)</h2>
</div>

<ul style="padding-left:0.5; line-height:1.7;">
  <li> Awarded the national “Premio Giovani Ricercatrici e Ricercatori 2025” in Cybersecurity by Gruppo 2003. </li>
  <li> PhD Dissertation Prize — Carlo Mosca Award, Società Italiana di Intelligence (<a href="https://www.santannapisa.it/it/news/premio-mosca-2025-riconoscimento-giulio-rossolini-della-scuola-superiore-santanna-una-ricerca" target="_blank">link</a>)</li>
  <li> Project Coordinator — “On the Safety and Security of Distributed AI-based Autonomous Multi-Agent Systems,” financed by the Department of Excellence in Robotics & AI, Scuola Superiore Sant’Anna, Pisa.</li>
  <li> Associate Editor for the <em>The Visual Computer</em> journal (since 2024).</li>
  <li> Consulting Associate Editor for the <em>IEEE Transactions on Information Forensics and Security</em> journal (since 2024).</li>
  <li> Reviewer / Program Committee Member for several AI conferences and journals — IEEE T-PAMI, IEEE T-IFS, IEEE T-ITS, IEEE T-NNLS, ICCV 2023, ECCV 2024, CVPR 2025, NeurIPS 2025, AAAI 2023–2026, and others.</li>
  <li> Session Chair — DSD-HSTIEC 2024 and 2025.</li>
</ul>



## 📬 Contact
[giulio.rossolini@santannapisa.it](mailto:giulio.rossolini@santannapisa.it)

### Last update
July, 2025