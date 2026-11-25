# Session Log — O Nervo Landing Page

## Sessao 1 — 2026-03-31

### O que foi feito

**Skills instalados:**
- Leonxlnx/taste-skill (7 skills de design)
- nextlevelbuilder/ui-ux-pro-max-skill (7 skills UI/UX)
- obra/superpowers (14 skills dev workflow)
- gsd-build/get-shit-done (CLI tool v1.30.0, instalado globalmente)

**Landing page redesenhada:**
- Substituido Inter por Space Grotesk + JetBrains Mono
- Off-black #050505 em vez de #000000 puro
- Layout assimetrico left-aligned (centered hero banned)
- Scroll reveal animations com IntersectionObserver
- Double-bezel card no CTA form
- CSS noise texture overlay
- Grid-based stats e pain points

**Copy reescrito com formulas de copywriting:**
- Hero: Before-After-Bridge — "vive num Excel que ninguem percebe..."
- Stats: Cost of Inaction — "desperdicadas", "rezar para que as formulas..."
- Pain points: PAS — "O autor saiu ha 2 anos", "Traducao: nunca"
- CTA: AIDA — "Tens nervo para mudar?"
- Botao: "Entrar na lista" (concreto vs generico "Quero saber")

**UX fixes:**
- Waitlist form movido para o hero (conversao above the fold)
- Logo invertido: fundo preto + N branco (alinhado com branding)
- Trust microcopy: "Sem spam. So o que interessa."
- "Estamos a acabar com isso." como frase de fecho bold

**Bug fix:**
- Email input invisivel — background era igual ao da pagina (#050505). Corrigido para #111111 com border mais visivel.

### Decisoes tomadas
- Marca definitiva: O Nervo
- Tom: Insider-Provocateur (bold & disruptivo)
- Paleta: Off-black + Dark Emerald (#036016) + Golden Glow (#ECD444)
- Tipografia: Space Grotesk + JetBrains Mono (Inter proibido)

### Pendente
- Verificar input de email no deploy de producao apos merge do PR #2
- Logo profissional (atualmente placeholder "N")
- Conteudo semana 2+ para redes sociais
- Melhorias continuas na landing page baseadas em feedback

## Sessao 2 — 2026-11-25

### O que foi feito
- Landing passou de waitlist para pagina comercial: todos os CTAs levam para `app.onervo.pt` (registo, login, precos).
- Redesign completo: nav fixa com Entrar / Comecar gratis, hero com ilustracao animada do painel (marcada "valores de exemplo"), "Como funciona" em 3 passos, grelha de funcionalidades, calculadora interativa "Quanto te custa o Excel?" (so com valores do visitante), precos reais com alternancia mensal/anual, FAQ, CTA final e CTA fixo no telemovel.
- SEO: title/description novos, canonical, Open Graph, JSON-LD SoftwareApplication com ofertas, robots.txt e sitemap.xml.
- Removidas estatisticas sem fonte (86%, 400h, "50+ equipas").
- Acessibilidade: conteudo visivel sem JS, prefers-reduced-motion respeitado, focus visivel.

### Pendente
- Imagem Open Graph (1200x630) para partilhas em LinkedIn/WhatsApp.
- Logo profissional.
