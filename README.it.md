🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

# AI Rank

Uno skill di Claude Code per ottimizzare i contenuti affinché vengano citati dai motori di risposta LLM (ChatGPT, Perplexity, Claude) e consumati da agenti IA autonomi.

Due audience, due framework:
- **LLM Framework** — Rendi i tuoi contenuti citabili dai motori di risposta
- **AGENT Framework** — Rendi il tuo prodotto accessibile agli agenti IA autonomi

## Skill Complementare

Si combina con [seo-rank](https://github.com/entpnomad/seo-rank) per una visibilità completa nei motori di ricerca:
- **ai-rank** copre i motori di risposta LLM + agenti IA autonomi
- **seo-rank** copre il SEO tradizionale e tecnico su Google/Bing

Usali insieme per una copertura totale su ricerca tradizionale e ricerca potenziata dall'IA.

## Cosa Fa

- Audita le pagine per la scopribilità LLM e la compatibilità con gli agenti
- Riscrive i contenuti per renderli compatibili con i motori di risposta
- Genera file di scoperta (llms.txt, agents.txt, API catalogs)
- Produce dati strutturati e raccomandazioni di schema
- Copre landing pages, documentazione, post di blog, pagine di prezzi e documentazione delle API

## Installazione

```bash
git clone https://github.com/entpnomad/ai-rank.git ~/.claude/skills/ai-rank
```

O per un progetto specifico:

```bash
git clone https://github.com/entpnomad/ai-rank.git .claude/skills/ai-rank
```

## Utilizzo

```
/ai-rank              # Flusso completo
/ai-rank audit        # Solo audit duale
/ai-rank rewrite      # Riscrittura con entrambi i framework
/ai-rank discovery    # Generare file di scoperta
/ai-rank agent        # Solo compatibilità agenti
/ai-rank answer       # Solo motori di risposta
/ai-rank checklist    # Checklist complete pagina + sito
/ai-rank schema       # Suggerimenti di schema
```

## Licenza

MIT
