## Yann Popat

Bachelor en mathématiques à l'Université de Montréal, passé par la CPGE MP2I.
J'apprends en construisant : la plupart des dépôts ci-dessous sont des outils
que j'utilise réellement, pas des exercices.

Ce qui m'intéresse en ce moment : concevoir des systèmes d'automatisation de
bout en bout — orchestration, intégration d'API, et emploi des LLM comme
composants mesurables plutôt que comme boîtes noires.

---

### Projets

**[analyse-annales-concours](https://github.com/Yanou10/analyse-annales-concours)** — Pipeline d'alignement d'un corpus d'épreuves sur un programme officiel, produisant un ordre de priorité de révision. Écosystème auto-hébergé sur VPS : n8n, PostgreSQL, Redis, MinIO et Caddy en Docker Compose ; un service FastAPI expose le pipeline Python, déclenché par événement MinIO via webhook. 2 199 questions étiquetées par LLM, avec sorties JSON strictes, cache de prompt, API Batch et reprise sur journal d'appels.
`n8n` · `Docker` · `FastAPI` · `PostgreSQL` · `MinIO` · `Redis` · `LLM`

**[pea-explorer](https://github.com/Yanou10/pea-explorer)** — Analyse quantitative des ETF éligibles au PEA : scraping Playwright, collecte par API, cache disque par actif, métriques de risque et de performance, matrices de corrélation, classeur Excel. Séparation stricte entre collecte et calcul — rien n'est retéléchargé deux fois, une interruption se reprend.
`Python` · `Playwright` · `scraping` · `pandas`

**[ETF-analysis-pipeline](https://github.com/Yanou10/ETF-analysis-pipeline)** — Suivi hebdomadaire d'un panier d'ETF, en local puis en serverless : Lambda déclenchée par EventBridge, lecture et écriture sur S3, infrastructure décrite en AWS SAM. Analyse des mouvements générée par Claude via Bedrock.
`AWS Lambda` · `EventBridge` · `S3` · `SAM` · `Bedrock`

**[ubicast-dl](https://github.com/Yanou10/ubicast-dl)** — Téléchargement et transcription des vidéos hébergées sur UbiCast/Nudgis. Rétro-ingénierie d'une API interne non documentée : pistes audio et vidéo séparées sur CDN, URLs signées éphémères, fusion FFmpeg sans réencodage, transcription Whisper.
`Python` · `FFmpeg` · `Whisper` · `rétro-ingénierie d'API`

**[MoodleAI](https://github.com/Yanou10/MoodleAI)** — Application web sur API LLM avec recherche documentaire (RAG) sur des supports de cours. Première place au hackathon Python de la Fournaise, de l'énoncé à une application fonctionnelle dans le temps du concours.
`Python` · `JavaScript` · `RAG`

**[m5-forecasting](https://github.com/Yanou10/m5-forecasting)** — Prévision de demande sur des millions de lignes de ventes : requêtes SQL, transformations, contrôles qualité, puis modélisation et résolution d'un problème d'allocation sous contrainte.
`Python` · `SQL` · `machine learning`

---

### Compétences

**Infrastructure** — Linux, Docker & Docker Compose, administration VPS, Caddy, Git
**Automatisation** — n8n auto-hébergé, webhooks, API REST, FastAPI, orchestration de tâches longues, idempotence et reprise sur incident
**Données** — PostgreSQL, SQL, Redis, MinIO, scraping (Playwright), FFmpeg, Whisper
**LLM** — prompt engineering, sorties structurées, cache de prompt, API Batch, RAG, évaluation et mesure des sorties
**Langages** — Python, SQL, JavaScript, C, C++, OCaml, R

[LinkedIn](https://www.linkedin.com/in/yann-p-658867274/) · yann.popat@gmail.com
