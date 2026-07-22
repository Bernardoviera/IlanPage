# Prompt de Imagem — Hero "Saindo do Zero"

> Calibrado com `docs/brand-guidelines.md` (paleta vinho/dourado/creme, iluminação quente, estética "wine bar europeu", nunca fast-casual).

## Prompt principal (colar no ChatGPT/DALL·E)

```
A close-up, ultra-realistic 4K photograph of an elegant hand gently swirling a glass of red wine. Shot in the style of luxury editorial food and wine photography. Warm, low-key lighting like a European wine bar at dusk — a single soft key light from the upper left, golden hour warmth, deep shadows. The wine is caught mid-swirl, visible motion and legs on the glass, deep wine-red color (like a Bordeaux), rich reflections of the warm light through the liquid. The glass is a fine crystal wine glass, stem held delicately between thumb and fingers, hand well-groomed and elegant, skin tone warm under the lighting. Shallow depth of field, background is a dark, blurred restaurant interior with warm bokeh lights, out of focus. Muted warm color grade — deep burgundy, warm gold, cream tones. Shot on a full-frame camera, 85mm lens, f/2.0, natural film grain, no harsh flash, no studio-white lighting. Sophisticated, intimate, unhurried mood. No text, no logos, no other people, no visible face.
```

## Variação vertical (para mobile / thumbnail 9:16)

```
Same shot, reframed as a vertical 9:16 composition: the hand and wine glass centered in the lower two-thirds of the frame, generous negative space above for headline text overlay, same warm low-key lighting and deep wine-red tones, shallow depth of field, blurred dark wine-bar background.
```

## Parâmetros sugeridos
- Proporção: 16:9 para hero de desktop, 9:16 para versão mobile
- Resolução: máxima disponível (upscale para 4K se a ferramenta permitir)
- Se a ferramenta pedir estilo: "photorealistic", "editorial photography", não "illustration" nem "3D render"

## O que evitar (reforçar se a IA errar)
- Sem iluminação branca/fria de estúdio (contraria a diretriz de "iluminação quente")
- Sem pose de propaganda genérica (mão muito rígida, sorriso, "brindando para a câmera")
- Sem excesso de saturação — o vinho deve parecer profundo, não neon
- Sem logo, texto ou marca d'água gerados pela IA

---

## Prompt de animação (imagem → vídeo)

A imagem gerada tem o vinho num respingo dramático, congelado no meio do movimento. Para a animação, o pedido é diferente do respingo: um giro circular contínuo e bem suave, como se a mão estivesse girando a taça devagar num movimento de decantação — não uma onda batendo.

```
Animate the wine inside the glass with a slow, smooth, continuous circular swirling motion, as if the hand is gently rotating the glass — the wine flows around the inside wall of the bowl in a steady circular current, like swirling a glass to release aroma. Motion should be gentle and fluid, not splashing or crashing. The hand, fingers, glass shape, and background stay completely static and unchanged — zero distortion. Camera is locked, no zoom, no pan, no shake. The animation should loop seamlessly, with the wine's circular motion continuing smoothly from the last frame back to the first with no visible jump or reset. Slow, elegant, minimal motion — cinemagraph style, not a fast or dramatic pour.
```

**Se a ferramenta permitir "negative prompt" ou "avoid":**
```
No splashing, no spilling, no liquid rising above the rim, no hand movement, no finger distortion, no glass warping, no camera movement, no flickering lights, no abrupt loop reset.
```

**Se a ferramenta pedir duração/velocidade:** peça a mais longa disponível (geralmente 4–10s) e a velocidade mais lenta — "slow motion, 0.5x speed" se houver essa opção. Giro rápido quebra o clima sofisticado que a marca pede.

**Ponto de atenção:** ferramentas de imagem→vídeo costumam distorcer mãos e dedos, e também tendem a interpretar "movimento no líquido" como um novo respingo em vez de um giro circular contínuo. Se sair errado, refaça a geração reforçando: "circular swirling motion only, like gently rotating the glass — not a splash or wave. Hand and fingers must remain completely frozen and unchanged."

## Depois de ter a imagem/vídeo final

Me envie o arquivo (`SendUserFile` do seu lado, ou só me diga o caminho) que eu:
1. Otimizo o arquivo para web (compressão, formato WebP/MP4 conforme o caso)
2. Substituo a ilustração SVG atual no hero por essa imagem/vídeo
3. Ajusto o layout ao redor dela se necessário
