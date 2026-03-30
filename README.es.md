🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md)

# AI Rank

Un skill de Claude Code para optimizar contenido y que sea citado por motores de respuesta LLM (ChatGPT, Perplexity, Claude) y consumido por agentes de IA autónomos.

Dos audiencias, dos frameworks:
- **LLM Framework** — Haz que tu contenido sea citable por motores de respuesta
- **AGENT Framework** — Haz que tu producto sea accesible para agentes de IA autónomos

## Skill Complementario

Se combina con [seo-rank](https://github.com/entpnomad/seo-rank) para visibilidad completa en buscadores:
- **ai-rank** cubre motores de respuesta LLM + agentes de IA autónomos
- **seo-rank** cubre SEO tradicional y técnico en Google/Bing

Usa ambos juntos para cobertura total en búsqueda tradicional y búsqueda potenciada por IA.

## Qué Hace

- Audita páginas para descubribilidad LLM y preparación para agentes
- Reescribe contenido para que sea amigable con motores de respuesta
- Genera archivos de descubrimiento (llms.txt, agents.txt, API catalogs)
- Produce datos estructurados y recomendaciones de schema
- Cubre landing pages, documentación, posts de blog, páginas de precios y documentación de APIs

## Instalación

```bash
git clone https://github.com/entpnomad/ai-rank.git ~/.claude/skills/ai-rank
```

O para un proyecto específico:

```bash
git clone https://github.com/entpnomad/ai-rank.git .claude/skills/ai-rank
```

## Uso

```
/ai-rank              # Flujo completo
/ai-rank audit        # Solo auditoría dual
/ai-rank rewrite      # Reescritura con ambos frameworks
/ai-rank discovery    # Generar archivos de descubrimiento
/ai-rank agent        # Solo preparación para agentes
/ai-rank answer       # Solo motores de respuesta
/ai-rank checklist    # Checklists completos de página + sitio
/ai-rank schema       # Sugerencias de schema
```

## Licencia

MIT
