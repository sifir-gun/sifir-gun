# Guney Tasdelen

**Architecte IA · Systèmes multi-agents / LLM / GenAI**
· Missions France et Suisse · [Agence Wengraf](lien)

Je conçois des systèmes multi-agents et des pipelines LLM menés jusqu'en production :
orchestration, RAG, guardrails, traçabilité et évaluation embarqués dès la conception.

## Ce que je construis

- **Orchestration multi-agents** : superviseur, fan-out / fan-in, évaluateur / critique,
  tool calling, MCP, human-in-the-loop
- **RAG adapté au problème** : RAG correctif (CRAG), recherche hybride, reranking, juge de pertinence
- **LLMOps** : jeux d'évaluation versionnés, observabilité, FinOps LLM, tiering de modèles
- **Gouvernance IA** : piste d'audit SHA-256, anonymisation RGPD avant appel LLM, préparation AI Act

## Stack

| Domaine | Outils |
|---|---|
| IA | LangGraph, LangChain, n8n, Claude, OpenAI, Mistral, Gemini, GLM |
| Backend | Python, FastAPI, TypeScript, NestJS |
| Données | PostgreSQL / pgvector, Supabase, Redis |
| Frontend | Next.js, React, Vue.js 3 |
| Infra | Docker, Kubernetes (Helm), GitHub Actions, Nginx, Linux, auto-hébergé / on-premise |

## Projet public

**[contract-decision-graph](lien)** : analyse de contrats fournisseurs en graphe d'agents.
LangGraph, architecture hexagonale (ports et adaptateurs), validation humaine,
Mistral par défaut, embeddings locaux. CLI et interface web.
Journal de décisions scellé et rejouable, déploiement Kubernetes via Helm,
images multi-architecture scannées en CI, couverture de tests supérieure à 98 %.

## En production (code client non public)

- **Aide à la décision auditable, finance** : 1 agents master, 4 sous-agents en parallèle, verdict rendu par un moteur
  déterministe, LLM cantonnés à l'explication, CRAG, empreinte SHA-256 de chaque décision
- **Plateforme d'investigation OSINT** : orchestrateur + 8 agents métier, 90+ sources,
  évaluation industrialisée, de 4 h à moins de 2 min par dossier
- **SaaS GenAI B2B** : Next.js / NestJS en BFF, couche serveur unique, anonymisation RGPD
- **Trading algorithmique** (projet personnel, privé) : FastAPI asynchrone, WebSocket,
  Redis, intégrations Binance, Coinbase, Bitget, Polygon.io

## Contact

[LinkedIn](https://linkedin.com/in/guney-tasdelen) · guney.t@agence-wengraf.com


### Contributions GitHub
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
</picture>
