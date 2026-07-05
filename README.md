# Hook Generator — OpenClaw Agency Skill

## O que é

Skill de geração de hooks virais para redes sociais, marketing, emails e conteúdo. Projetada para a OpenClaw Agency, combinando os melhores frameworks de copywriting com adaptação para cada plataforma.

## Como usar

### No OpenClaw
Copie a pasta `hook-generator/` para `~/.openclaw/workspace/skills/` e use naturalmente:

```
"Generate 5 Instagram hooks for a post about AI in marketing"
"Write 3 email subject lines for a product launch"
"Create a thread hook for X about social media strategy"
"Give me a contrarian hook for LinkedIn about content creation"
```

### Formatos suportados
- 📱 Instagram (captions, Reels, carousels)
- 🎵 TikTok (vídeos, trends)
- 🐦 X/Twitter (tweets, threads)
- 💼 LinkedIn (posts, artigos)
- 📺 YouTube (vídeos, shorts)
- 📧 Email (subject lines, preview text)
- 📢 Ads (Meta, Google, TikTok Ads)

## Frameworks inclusos

### Hooks Fundamentais (10)
1. **PAS** (Problem → Agitate → Solve)
2. **AIDA** (Attention → Interest → Desire → Action)
3. **Curiosity Gap** (tease sem revelar)
4. **Contrarian** (vai contra o consenso)
5. **Story** (drop em momento específico)
6. **List/Number** (N + promessa específica)
7. **Before/After** (transformação)
8. **"Stop Doing This"** (comando + alternativa)
9. **Question** (pergunta que não dá pra não responder)
10. **Shocking Stat** (dado surpreendente)

### Hook Engineering (7 Power Angles) — v1.1.0
1. **Concrete Numbers** — dados, métricas, resultados mensuráveis
2. **Challenge the Status Quo** — contrariar crença comum
3. **Secret/Revelation** — "o que ninguém te conta"
4. **"Wait, what?" Moment** — surpresa ou dissonância cognitiva
5. **Promised Transformation** — do estado A ao B de forma específica
6. **Revenue Impact** — conexão direta com dinheiro
7. **Time Saved** — resultado mais rápido que o esperado

### Pré-análise (12 dimensões) — v1.1.0
Análise silenciosa do conteúdo antes de gerar hooks, cobrindo: oportunidade do leitor, processo replicável, dor compartilhada, win rápido, vantagem estratégica, potencial de crescimento, resultado mais impressionante, insight contrarian, erro comum, framework acionável, expertise única, sistema pouco conhecido.

### Trigger Words (4 categorias) — v1.2.0
Palavras de gatilho que amplificam o impacto emocional (~10x mais engajamento):
- **Insider:** secretly, revealed, hidden, uncovered, leaked
- **Helper:** losing, wasting, costing, bleeding, hemorrhaging
- **Thinker:** backwards, paradox, myth, counterintuitive
- **Amplifiers:** every, zero, literally, completely, exactly
- Arquivo: `references/trigger_words.md`

### 19 Padrões de Hook Virais — v1.2.0
Padrões comprovados com templates e exemplos:
- Proxy Learning, Popular Name, Authority Credibility, Tools/Resources
- Cautionary Tale, Analysis-Based, Achievement with Constraint
- Steal My Process, Myth-Busting, Reset Expectations
- Opposite/Contrarian, Data-Driven, The Unexpected, You're Losing
- Tiny Change Big Impact, Everything Wrong, Less Beats More
- Behind-the-Scenes Testing
- Arquivo: `references/hook-patterns.md`

## Dependências

Nenhuma. Skill pura baseada em prompts.

## Adaptação

Originalmente criada para Claude Code. Adaptada para OpenClaw mantendo o padrão SKILL.md com YAML frontmatter.

## Licença

MIT — use como quiser.

---

## Changelog

### v1.2.0 (2026-07-05)
- Adicionado **Trigger Words** (4 categorias de palavras de gatilho viral)
  - Insider, Helper, Thinker, Amplifiers
  - Arquivo de referência: `references/trigger_words.md`
- Adicionado **19 padrões de hook virais** (Viral Hook Creator)
  - Proxy Learning, Authority Credibility, Myth-Busting, Opposite/Contrarian, etc.
  - Arquivo de referência: `references/hook-patterns.md`
- Atualizado workflow: leitura obrigatória dos arquivos de referência
- Atualizado scoring: inclui verificação de integração de trigger words
- Atualizado output: mostra padrão viral e trigger words usados
- **Fonte:** `ognjengt/founder-skills` (87 GitHub stars)

### v1.1.0 (2026-07-05)
- Adicionado **Step 0 — Value Extraction** (pré-análise com 12 dimensões)
- Adicionado **Hook Engineering** (7 power angles com exemplos)
- Adicionado **Quality Benchmark** (19 exemplos de hooks eficazes)
- Adicionado capacidade de **segunda rodada** (sem repetição de ângulos)
- Adicionadas regras específicas para **LinkedIn** (20 hooks por rodada)
- Mescladas melhores práticas de `aiskilloftheweek/claude-ai-skill-of-the-week`

### v1.0.0 (2026-07-05)
- Criação inicial com 10 frameworks de hooks
- Adaptações por plataforma
- Anti-patterns e detecção de AI slop
- Sistema de scoring de hooks
