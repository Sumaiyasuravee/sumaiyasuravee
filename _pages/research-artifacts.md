---
permalink: /research-artifacts/
title: "Research Artifacts"
layout: single
author_profile: true
---

Ontologies and knowledge graphs developed as part of my research on dementia-related agitation and informal caregiver support.

<div class="list__item">
  <article class="archive__item">
    <h2 class="archive__item-title" id="edem-connectonto"><a href="https://bioportal.bioontology.org/ontologies/EDEM-CONNECTONTO">eDEM-CONNECTONTO</a></h2>
    <p class="page__meta"><i class="fas fa-fw fa-diagram-project" aria-hidden="true"></i> Ontology &middot; OWL &middot; published on NCBO BioPortal</p>
    <p>eDEM-Connect: an ontology of dementia-related agitation and the relationship between informal caregivers and persons with dementia. It encodes validated, expert- and literature-derived knowledge about agitation so it can be reused by downstream machine learning systems &mdash; from entity recognition and relation extraction to chatbot-based support tools.</p>
    <ul>
      <li>252 concepts, 16 relations, and 241 individuals, implemented in OWL and validated with Prot&eacute;g&eacute;.</li>
      <li>Built around five top-level concepts: <em>Person</em>, <em>Agitation</em>, <em>Causes</em>, <em>Consequences</em>, and <em>Interventions</em>.</li>
      <li>Developed through a systematic literature review, analysis of existing ontologies, expert workshops, and interviews with informal caregivers.</li>
    </ul>
    <p><a href="https://bioportal.bioontology.org/ontologies/EDEM-CONNECTONTO">View on BioPortal</a> &middot; described in <a href="https://www.frontiersin.org/journals/aging/articles/10.3389/fragi.2026.1780260/full">Suravee et al., Frontiers in Aging (2026)</a></p>
  </article>
</div>

<div class="list__item">
  <article class="archive__item">
    <h2 class="archive__item-title"><a href="https://datasetcatalog.nlm.nih.gov/dataset?q=0002163028">eDEM-KG</a></h2>
    <p class="page__meta"><i class="fas fa-fw fa-diagram-project" aria-hidden="true"></i> Knowledge graph &middot; derived from eDEM-CONNECTONTO &middot; Zenodo</p>
    <p>An ontology-driven knowledge graph for dementia-related agitation events, built on eDEM-CONNECTONTO. It incorporates manually annotated entities and relations from a BRAT-annotated dementia dataset sourced from real-world dementia forum texts, intended for training named entity recognition and relation extraction models.</p>
    <ul>
      <li>122 ontology classes, 6 object relationships, and 58 individuals.</li>
      <li>Created by Sumaiya Suravee and Kristina Yordanova, University of Greifswald &middot; published December 2025.</li>
      <li>Licensed under CC BY 4.0. DOI: <a href="https://doi.org/10.5281/zenodo.17966383">10.5281/zenodo.17966383</a>.</li>
    </ul>
    <p><a href="https://datasetcatalog.nlm.nih.gov/dataset?q=0002163028">View on NLM Data Discovery</a> &middot; <a href="https://doi.org/10.5281/zenodo.17966383">View on Zenodo</a></p>
  </article>
</div>

<div class="list__item">
  <article class="archive__item">
    <h2 class="archive__item-title"><a href="https://datascience.uni-greifswald.de/forschung/research-artefacts/loc-demcare-chatbot/">Loc-DemCare Chatbot</a></h2>
    <p class="page__meta"><i class="fas fa-fw fa-diagram-project" aria-hidden="true"></i> Local, privacy-preserving LLM chatbot &middot; TinyLlama-1.1B + LoRA</p>
    <div class="archive__item-teaser">
      <img src="/images/loc-demcare-chatbot-overview.png" alt="Diagram of the Loc-DemCare chatbot: a local general-purpose LLM fine-tuned on a dementia corpus, providing explainable, private, and secure answers to the user">
    </div>
    <p>An AI assistant developed to support dementia care communication and caregiver decision-making. It runs on a fine-tuned TinyLlama-1.1B model (via LoRA) trained on 1,393 dementia-care examples from the Informal Dementia Forum Corpus, and is converted to GGUF format so it can run entirely locally &mdash; without internet access &mdash; to keep caregiver data private. It offers guidance on agitation-related situations and non-pharmacological intervention strategies.</p>
    <ul>
      <li>Fine-tuned with LoRA on 775 question&ndash;answer pairs from an online dementia forum; evaluated on 35 held-out test question&ndash;answer pairs (~1,500 sentences).</li>
      <li>Runs fully offline via GGUF conversion, so caregiver conversations never leave the device.</li>
      <li>Built on the <a href="/research-artifacts/#edem-connectonto">eDEM-CONNECTONTO</a> ontology and the Informal Dementia Forum Corpus (IDFC).</li>
      <li>Publicly available within the University of Greifswald via AppHub.</li>
      <li>Suravee, S., Ghods, M.R. and Yordanova, K. (2026, March). &quot;Loc-DemCare: Supporting Informal Dementia Caregivers with a Local, Intelligent Chatbot.&quot; In <i>2026 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops)</i>. pp. 551&ndash;555. IEEE.</li>
    </ul>
    <p><a href="https://datascience.uni-greifswald.de/forschung/research-artefacts/loc-demcare-chatbot/">View on Institute of Data Science</a></p>
  </article>
</div>
