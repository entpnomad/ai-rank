🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

# AI Rank

Um skill de Claude Code para otimizar conteudo para que seja citado por motores de resposta LLM (ChatGPT, Perplexity, Claude) e consumido por agentes de IA autonomos.

Dois publicos, dois frameworks:
- **LLM Framework** — Torna o teu conteudo citavel pelos motores de resposta
- **AGENT Framework** — Torna o teu produto acessivel a agentes de IA autonomos

## Skill Complementar

Combina com [seo-rank](https://github.com/entpnomad/seo-rank) para visibilidade completa nos motores de busca:
- **ai-rank** cobre motores de resposta LLM + agentes de IA autonomos
- **seo-rank** cobre SEO tradicional e tecnico no Google/Bing

Usa os dois juntos para cobertura total em busca tradicional e busca potenciada por IA.

## O Que Faz

- Audita paginas para descoberta LLM e prontidao para agentes
- Reescreve conteudo para ser compativel com motores de resposta
- Gera ficheiros de descoberta (llms.txt, agents.txt, API catalogs)
- Produz dados estruturados e recomendacoes de schema
- Cobre landing pages, documentacao, posts de blog, paginas de precos e documentacao de APIs

## Instalacao

```bash
git clone https://github.com/entpnomad/ai-rank.git ~/.claude/skills/ai-rank
```

Ou para um projeto especifico:

```bash
git clone https://github.com/entpnomad/ai-rank.git .claude/skills/ai-rank
```

## Utilizacao

```
/ai-rank              # Fluxo completo
/ai-rank audit        # Apenas auditoria dual
/ai-rank rewrite      # Reescrita com ambos os frameworks
/ai-rank discovery    # Gerar ficheiros de descoberta
/ai-rank agent        # Apenas prontidao para agentes
/ai-rank answer       # Apenas motores de resposta
/ai-rank checklist    # Checklists completas de pagina + site
/ai-rank schema       # Sugestoes de schema
```

## Licenca

MIT
