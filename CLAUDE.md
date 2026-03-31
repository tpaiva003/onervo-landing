# O Nervo — Landing Page

## Projeto
Landing page de teaser/waitlist para **O Nervo** — plataforma SaaS de controlo orcamental para PMEs portuguesas. Repositorio separado do produto principal (budget-tracker-simple).

- **URL:** onervo.pt
- **Hosting:** Vercel (projeto separado, HTML estatico)
- **Form backend:** Formspree (https://formspree.io/f/xnjodeda)
- **Stack:** HTML5 puro + CSS embebido + JS vanilla. Sem framework, sem build.

---

## Marca

### Nome & Dominio
- **Marca:** O Nervo
- **Dominio:** onervo.pt (ativo, Vercel DNS)
- **Dominio backup:** onervo.eu (registado)

### Handles
| Plataforma | Nome | Handle/URL |
|------------|------|------------|
| LinkedIn | O Nervo | linkedin.com/company/onervo-pt |
| Instagram | O Nervo | @onervo.pt |
| Website | O Nervo | onervo.pt |

### Tom & Voz — Insider-Provocateur
- **Persona:** Insider anonimo de finance ops que trabalhou com 50+ equipas financeiras de PMEs portuguesas. Partilha verdades desconfortaveis sobre gestao orcamental em Excel.
- **Tom:** Bold & Disruptivo. Direto, sem floreados. Provoca mas com substancia.
- **Nao e:** Arrogante, condescendente, generico, corporate-speak.

**Tracos de voz:**
- Confiante, nao arrogante
- Provocador, nao ofensivo
- Conhecedor (insider), nao academico
- Direto, nao vago

**Wordplay arsenal (usar no copy e redes sociais):**
- "Toca no nervo" — hits a nerve (provocativo)
- "Acalma o nervo" — calm your finance stress
- "O nervo central" — the nerve center of your finances
- "Tens nervo?" — do you have the nerve to change?

**Cliches PROIBIDOS:** "Elevate", "Seamless", "Unleash", "Next-Gen", "Revolucionario", "Inovador"

### Paleta de Cores
| Funcao | Cor | Hex | Uso |
|--------|-----|-----|-----|
| Base | Off-Black | #050505 | Fundo da pagina |
| Surface | Dark Surface | #111111 | Inputs, cards |
| Primaria | Dark Emerald | #036016 | Botoes, destaques, focus |
| Accent | Golden Glow | #ECD444 | Numeros-chave, enfase, headlines |
| Texto | Off-White | #f0f0f0 | Texto principal |
| Texto secundario | Muted | #8a8a8a | Descricoes |
| Texto terciario | Dim | #555555 | Labels, hints |

**Regra:** 70% preto, 20% emerald, 10% gold. O gold so aparece para chamar atencao.

### Tipografia
- **Headlines:** Space Grotesk Bold (tracking tight)
- **Body:** Space Grotesk Regular
- **Dados/Labels:** JetBrains Mono (monospace para numeros e metadata)
- **PROIBIDO:** Inter (banned pelos design skills — sem personalidade)

### Logo
- Placeholder atual: letra "N" em branco sobre fundo preto com border subtil
- Logo profissional: pendente

---

## Formulas de Copywriting Aplicadas

| Seccao | Formula | Aplicacao |
|--------|---------|-----------|
| Hero | Before-After-Bridge | Problema (Excel caos) → Desejo (controlo) → Ponte (O Nervo) |
| Stats | Cost of Inaction | "400h desperdicadas", "rezar para que as formulas estejam certas" |
| Pain Points | PAS (Problem-Agitate-Solution) | Agitar com detalhes especificos ("o autor saiu ha 2 anos") |
| CTA | AIDA | "Tens nervo para mudar?" — atencao + desejo + accao |

**Taglines:**
- Website: "Toca no nervo do teu orcamento."
- Social: "De Excel a decisao em 10 minutos."

---

## Conteudo & Redes Sociais

### Estrategia (8 semanas)
- **Semanas 1-4:** So problema. Pain posts, stats, hot takes. Sem produto.
- **Semanas 5-6:** Tease — "Estou a construir algo..."
- **Semanas 7-8:** Reveal O Nervo + waitlist.

### Cadencia
- LinkedIn: 3x/semana (so texto, sem imagem)
- Instagram: 2x/semana (templates visuais: Stat Bomb + Statement Post)

### Templates Canva
1. **Statement Post** (1080x1080): Fundo preto, texto branco grande, keyword em gold
2. **Stat Bomb** (1080x1080): Numero gold grande, frase branca, barra emerald no fundo

### Brand Kit Canva
- Cores: #000000, #036016, #ECD444
- Fonte: Inter Bold (Canva) / Space Grotesk (web)
- Logo: N branco sobre preto

---

## Design Principles (dos skills instalados)

- **Sem Inter** — usar Space Grotesk ou Outfit
- **Sem #000000 puro** — usar off-black (#050505)
- **Sem layout centrado** — assimetrico, left-aligned (DESIGN_VARIANCE=8)
- **Motion** — scroll reveals com IntersectionObserver, cubic-bezier custom
- **Grid sobre Flex** — CSS Grid para layouts robustos
- **Double-bezel** — containers nested (outer shell + inner core) para premium feel
- **Monospace para dados** — JetBrains Mono em numeros e labels
- **Noise overlay** — textura SVG subtil para profundidade fisica

---

## Audiencia-Alvo
- **Primaria:** PMEs portuguesas (1-500 empregados) que usam Excel para gestao orcamental
- **Secundaria:** Diretores financeiros, controllers, contabilistas, consultores de gestao
- **Geografia:** Portugal
