# Brand Guidelines — Empório Dýnami v1.0

> Last updated: 2026-07-22
> Status: Draft — derivado da Fundação Estratégica Unificada (Bloco 1) e do Briefing "Saindo do Zero"

## Quick Reference

| Element | Value |
|---------|-------|
| Primary Color | #5C1A21 (Vinho Dýnami) |
| Secondary Color | #C9A227 (Dourado Quente) |
| Accent Color | #3A4A34 (Verde Serra) |
| Primary Font (headings) | Fraunces |
| Secondary Font (body/UI) | Inter |
| Voice | Formal, clara, contemporânea — sofisticação sem afetação |

---

## 1. Color Palette

Paleta derivada da diretriz de estética da Fundação Estratégica: *"minimalismo sofisticado, tons sóbrios, iluminação quente, referências a wine bars europeus e restaurantes contemporâneos — nunca estética de fast-casual ou de rede."*

### Primary Colors

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| Vinho Dýnami | #5C1A21 | rgb(92,26,33) | CTAs primários, headers, elementos de destaque — cor-âncora ligada ao vinho e à experiência core |
| Vinho Profundo | #3D1116 | rgb(61,17,22) | Hover states, fundos escuros, seções de imersão (hero, rodapé) |

### Secondary Colors

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| Dourado Quente | #C9A227 | rgb(201,162,39) | Acentos, ícones, divisores, iluminação quente evocada em detalhes (referência a wine bar europeu) |
| Dourado Claro | #E4C766 | rgb(228,199,102) | Hover/estado ativo sobre fundo escuro, pequenos destaques |

### Accent (uso pontual)

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| Verde Serra | #3A4A34 | rgb(58,74,52) | Referência à Serra do Japi/território; uso pontual em selos, tags de categoria (ex. "clube", "curso") |

### Neutral Palette

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| Fundo Creme | #F5F1E8 | rgb(245,241,232) | Fundo de página — tom sóbrio e quente, nunca branco puro |
| Superfície | #EAE3D3 | rgb(234,227,211) | Cards, seções alternadas |
| Texto Primário | #211A16 | rgb(33,26,22) | Títulos e corpo de texto — preto quente, não neutro frio |
| Texto Secundário | #6B6055 | rgb(107,96,85) | Legendas, texto de apoio |
| Borda | #DCD3C0 | rgb(220,211,192) | Divisores, bordas de input |

### Semantic Colors

| State | Hex | Usage |
|-------|-----|-------|
| Success | #4C6B4F | Confirmações (reserva feita, assinatura ativa) |
| Warning | #B5842A | Avisos (vagas limitadas, prazo) — reforça senso de escassez real, nunca artificial |
| Error | #8C2F26 | Erros de formulário |
| Info | #5C1A21 | Mensagens informativas — usa a própria cor primária |

### Accessibility

- Texto Primário (#211A16) sobre Fundo Creme (#F5F1E8): contraste ~14.8:1 (AAA)
- Vinho Dýnami (#5C1A21) sobre Fundo Creme: contraste ~8.9:1 (AAA)
- Dourado Quente (#C9A227) só deve ser usado para texto grande (≥18px/bold) sobre fundo escuro — contraste insuficiente para corpo de texto pequeno
- Todos os elementos interativos devem atender WCAG 2.1 AA

---

## 2. Typography

### Font Stack

```css
--font-heading: 'Fraunces', Georgia, serif;
--font-body: 'Inter', system-ui, -apple-system, sans-serif;
--font-mono: 'JetBrains Mono', 'Fira Code', monospace;
```

**Racional:** Fraunces é uma serifada editorial e quente (evoca papel de carta de vinhos e restaurantes contemporâneos) sem cair em clichê clássico/rígido. Inter garante legibilidade limpa no corpo — "clareza, objetividade sofisticada" (tom de voz, Bloco 1).

### Type Scale

| Element | Size (Desktop) | Size (Mobile) | Weight | Line Height |
|---------|----------------|---------------|--------|-------------|
| H1 | 56px | 34px | 600 (Fraunces) | 1.15 |
| H2 | 40px | 28px | 600 (Fraunces) | 1.2 |
| H3 | 28px | 22px | 500 (Fraunces) | 1.3 |
| H4 | 22px | 18px | 600 (Inter) | 1.35 |
| Body | 16px | 16px | 400 (Inter) | 1.6 |
| Body Large | 19px | 18px | 400 (Inter) | 1.6 |
| Small | 14px | 14px | 400 (Inter) | 1.5 |
| Caption | 12px | 12px | 500 (Inter, uppercase, tracking+) | 1.4 |

### Font Loading

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
```

---

## 3. Logo Usage

*A definir — nenhum arquivo de logo foi fornecido ainda.* Enquanto não houver logo, usar wordmark tipográfico: "EMPÓRIO DÝNAMI" em Fraunces 600, letter-spacing ampliado, sempre em Vinho Dýnami ou branco/creme sobre fundo escuro.

| Variant | Status | Use Case |
|---------|--------|----------|
| Wordmark horizontal | A criar | Header, documentos |
| Símbolo/monograma | A criar | Favicon, redes sociais |
| Monocromático | A criar | Contextos de baixo contraste |

### Don'ts (aplicável ao wordmark provisório)

- Não usar cores fora da paleta aprovada
- Não aplicar sombras, gradientes decorativos ou efeitos 3D
- Não usar sobre fundos com padrão/imagem sem overlay de contraste
- Não distorcer proporções ou usar itálico decorativo fora do Fraunces

---

## 4. Voice & Tone

Base: seção "Tom de Voz" da Fundação Estratégica Unificada (Bloco 1) + Briefing "Saindo do Zero".

### Brand Personality

| Trait | Description |
|-------|--------------|
| **Disciplinado** | Fala com rigor e método, nunca de forma improvisada ou apressada |
| **Preciso** | Prioriza clareza e construção lógica antes de qualquer apelo emocional |
| **Sofisticado sem afetação** | Elegância que nasce de domínio técnico real, nunca de encenação |
| **Íntegro** | Mostra bastidores, erros e aprendizados — transparência de processo |

### Voice Chart

| Trait | Somos | Não somos |
|-------|-------|-----------|
| Disciplinado | Estruturado, consistente | Rígido, burocrático |
| Preciso | Claro, objetivo | Seco, impessoal |
| Sofisticado | Refinado, com repertório real | Pomposo, performático |
| Íntegro | Transparente, autêntico | Confessional em excesso |

### Tom por contexto

| Contexto | Tom | Exemplo |
|----------|-----|---------|
| Marca Dýnami (core) | Executivo experiente, formal e contemporâneo | "A carta de vinhos reflete o mesmo rigor que rege um treino de triatlo." |
| Curso "Saindo do Zero" (entrada) | Educativo, acessível, envolvente, sem pedantismo | "Ninguém nasce sabendo ler uma carta de vinhos — e está tudo bem." |
| Clube / e-mail pós-compra | Consultivo, pessoal, direto | "Preparamos a curadoria deste mês pensando em quem já deu o primeiro passo com você." |
| Mensagens de erro / formulário | Calmo, resolutivo | "Não conseguimos confirmar sua reserva — tente novamente ou fale conosco no WhatsApp." |

### Termos proibidos / a evitar

| Evitar | Motivo |
|--------|--------|
| "Imperdível", "não pode ficar de fora" | Urgência artificial — contraria "escassez real, nunca artificial" |
| "Revolucionário", "único no mercado" | Clichê de marketing, sem prova concreta |
| Jargão técnico de vinho não explicado | Intimida o público de entrada (Saindo do Zero) |
| Emojis em excesso, tom "vendedor demais" | Contraria o tom formal/executivo da marca-mãe |
| Estética/linguagem de "infoproduto de massa" (setas amarelas, contadores agressivos) | Vetado explicitamente no briefing da agência |

---

## 5. Imagery Guidelines

### Fotografia

- **Iluminação:** Quente, natural, semelhante a wine bar europeu ao entardecer — nunca luz fria/clínica
- **Assuntos:** Pratos, taças e rótulos reais da Dýnami; o fundador em momentos de curadoria (degustação, harmonização); ambiente do salão — nunca banco de imagens genérico
- **Tratamento de cor:** Tons quentes e saturação moderada, mantendo a paleta de vinho/dourado/creme
- **Composição:** Limpa, com foco no prato/taça — respiro generoso (minimalismo sofisticado)

### Ilustrações e ícones

- Estilo: linear/outline, traço fino e consistente (1.5px), sem preenchimento sólido
- Cantos levemente arredondados (2px) — nunca geométrico "tech" ou infantilizado
- Paleta restrita: Vinho Dýnami, Dourado Quente, Texto Primário

### Visual Don'ts

| Evitar | Motivo |
|--------|--------|
| Cores vibrantes/neon, gradientes tipo app de delivery | Contraria "nunca estética fast-casual ou de rede" |
| Setas amarelas, contadores agressivos de urgência | Vetado no briefing "Saindo do Zero" |
| Fotos de banco de imagens genéricas de "casal brindando" | Quebra a autenticidade exigida pela narrativa do fundador |
| Fundo branco puro (#FFFFFF) | A marca usa creme quente (#F5F1E8), nunca branco clínico |

---

## 6. Design Components

### Buttons

| Type | Background | Text | Border Radius |
|------|------------|------|----------------|
| Primary | #5C1A21 | #F5F1E8 | 4px |
| Secondary | Transparent, borda #5C1A21 | #5C1A21 | 4px |
| Tertiary | Transparent | #6B6055 | 4px |

*Border radius baixo (4px) intencionalmente — reforça sobriedade em vez do arredondado "app-like" de infoproduto.*

### Spacing Scale

| Token | Value | Usage |
|-------|-------|-------|
| xs | 4px | Espaçamento apertado |
| sm | 8px | Elementos compactos |
| md | 16px | Espaçamento padrão |
| lg | 24px | Espaçamento entre blocos |
| xl | 40px | Grandes intervalos |
| 2xl | 80px | Divisores de seção (respiro editorial) |

### Border Radius

| Element | Radius |
|---------|--------|
| Botões | 4px |
| Cards | 8px |
| Inputs | 4px |
| Modais | 8px |
| Tags/selos | 9999px (única exceção, para selos tipo "vagas limitadas") |

---

## AI Image Generation

### Base Prompt Template

```
Warm, intimate lighting like a European wine bar at dusk. Sophisticated minimalism, muted warm tones (deep wine red #5C1A21, warm gold #C9A227, warm cream #F5F1E8). Real, unstaged moments — never stock-photo posed. Contemporary restaurant photography, shallow depth of field, natural textures (wood, linen, wine glass reflections).
```

### Style Keywords

| Category | Keywords |
|----------|----------|
| **Lighting** | warm, low-key, golden hour, candlelight-adjacent |
| **Mood** | sophisticated, disciplined, intimate, unhurried |
| **Composition** | minimal, generous negative space, off-center focal point |
| **Treatment** | muted saturation, warm color grade, subtle film grain |
| **Aesthetic** | contemporary European wine bar, editorial, never fast-casual |

### Visual Mood Descriptors

- Sofisticação sem afetação
- Precisão de atleta aplicada à mesa
- Território como refúgio (Serra do Japi, Eloy Chaves)

### Visual Don'ts

| Evitar | Motivo |
|--------|--------|
| Iluminação branca/fria de estúdio | Contraria "iluminação quente" da diretriz de marca |
| Composição lotada, muitos produtos na mesma imagem | Contraria minimalismo sofisticado |
| Pessoas posando de forma artificial para câmera | Contraria "transparência de processo" e autenticidade |

### Example Prompts

**Hero Banner (site Dýnami):**
```
Warm, intimate lighting like a European wine bar at dusk. A single glass of red wine on a wooden table, shallow depth of field, blurred warm bokeh of a restaurant interior in the background. Muted warm tones — deep wine red, warm gold, cream. Editorial, minimalist composition with generous negative space on the left for headline text. No people, no logos.
```

**Página do curso "Saindo do Zero":**
```
Warm, approachable lighting, softer and brighter than the core Dýnami hero but same warm palette. A person's hands casually reading a wine label, relaxed and unposed. Friendly, accessible mood — not intimidating, not corporate.
```

---

## Changelog

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2026-07-22 | Guia inicial derivado da Fundação Estratégica Unificada (Bloco 1) e do Briefing da Agência "Saindo do Zero". Paleta vinho/dourado/creme, tipografia Fraunces + Inter. |
