🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

# AI Rank

Ein Claude Code Skill zur Optimierung von Inhalten, damit sie von LLM-Antwortmaschinen (ChatGPT, Perplexity, Claude) zitiert und von autonomen KI-Agenten konsumiert werden.

Zwei Zielgruppen, zwei Frameworks:
- **LLM Framework** — Mach deinen Content zitierfaehig fuer Antwortmaschinen
- **AGENT Framework** — Mach dein Produkt zugaenglich fuer autonome KI-Agenten

## Begleit-Skill

Kombiniert sich mit [seo-rank](https://github.com/entpnomad/seo-rank) fuer vollstaendige Suchsichtbarkeit:
- **ai-rank** deckt LLM-Antwortmaschinen + autonome KI-Agenten ab
- **seo-rank** deckt klassisches + technisches SEO bei Google/Bing ab

Nutze beide zusammen fuer volle Abdeckung ueber traditionelle und KI-gestuetzte Suche.

## Was es macht

- Prueft Seiten auf LLM-Auffindbarkeit und Agenten-Bereitschaft
- Schreibt Inhalte um, damit sie antwortmaschinen-freundlich sind
- Generiert Discovery-Dateien (llms.txt, agents.txt, API catalogs)
- Erstellt strukturierte Daten und Schema-Empfehlungen
- Deckt Landing Pages, Dokumentation, Blogartikel, Preisseiten und API-Dokumentation ab

## Installation

```bash
git clone https://github.com/entpnomad/ai-rank.git ~/.claude/skills/ai-rank
```

Oder fuer ein bestimmtes Projekt:

```bash
git clone https://github.com/entpnomad/ai-rank.git .claude/skills/ai-rank
```

## Nutzung

```
/ai-rank              # Vollstaendiger Workflow
/ai-rank audit        # Nur Dual-Audit
/ai-rank rewrite      # Umschreiben mit beiden Frameworks
/ai-rank discovery    # Discovery-Dateien generieren
/ai-rank agent        # Nur Agenten-Bereitschaft
/ai-rank answer       # Nur Antwortmaschinen
/ai-rank checklist    # Vollstaendige Seiten- + Site-Checklisten
/ai-rank schema       # Schema-Vorschlaege
```

## Lizenz

MIT
