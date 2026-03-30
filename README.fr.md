🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

# AI Rank

Un skill Claude Code pour optimiser le contenu afin qu'il soit cité par les moteurs de réponse LLM (ChatGPT, Perplexity, Claude) et consommé par des agents IA autonomes.

Deux audiences, deux frameworks :
- **LLM Framework** — Rendez votre contenu citable par les moteurs de réponse
- **AGENT Framework** — Rendez votre produit accessible aux agents IA autonomes

## Skill Complémentaire

Se combine avec [seo-rank](https://github.com/entpnomad/seo-rank) pour une visibilité complète dans les moteurs de recherche :
- **ai-rank** couvre les moteurs de réponse LLM + les agents IA autonomes
- **seo-rank** couvre le SEO traditionnel et technique sur Google/Bing

Utilisez les deux ensemble pour une couverture totale sur la recherche traditionnelle et la recherche alimentée par l'IA.

## Ce Qu'il Fait

- Audite les pages pour la découvrabilité LLM et la compatibilité avec les agents
- Réécrit le contenu pour le rendre compatible avec les moteurs de réponse
- Génère des fichiers de découverte (llms.txt, agents.txt, API catalogs)
- Produit des données structurées et des recommandations de schema
- Couvre les landing pages, la documentation, les articles de blog, les pages de tarification et la documentation d'APIs

## Installation

```bash
git clone https://github.com/entpnomad/ai-rank.git ~/.claude/skills/ai-rank
```

Ou pour un projet spécifique :

```bash
git clone https://github.com/entpnomad/ai-rank.git .claude/skills/ai-rank
```

## Utilisation

```
/ai-rank              # Flux complet
/ai-rank audit        # Audit dual uniquement
/ai-rank rewrite      # Réécriture avec les deux frameworks
/ai-rank discovery    # Générer les fichiers de découverte
/ai-rank agent        # Compatibilité agents uniquement
/ai-rank answer       # Moteurs de réponse uniquement
/ai-rank checklist    # Checklists complètes page + site
/ai-rank schema       # Suggestions de schema
```

## Licence

MIT
