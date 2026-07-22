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

## Depois de gerar a imagem: prompt para a IA de animação

Ao mandar a imagem gerada para a ferramenta de animação (Runway, Pika, Kling, etc.), use algo como:

```
Animate this image as a subtle, seamless looping cinemagraph. Only the wine inside the glass should move — a slow, gentle swirl, as if the hand just started swirling it. The hand and glass stay completely still, no distortion of fingers or glass shape. Camera is static, no zoom, no pan. Loop should be smooth with no visible jump cut. Subtle, elegant, slow motion — not fast or dramatic.
```

**Ponto de atenção:** ferramentas de animação por IA costumam distorcer mãos e dedos. Se isso acontecer, peça explicitamente na re-geração: "keep the hand and fingers completely unchanged, animate only the liquid inside the glass."

## Depois de ter a imagem/vídeo final

Me envie o arquivo (`SendUserFile` do seu lado, ou só me diga o caminho) que eu:
1. Otimizo o arquivo para web (compressão, formato WebP/MP4 conforme o caso)
2. Substituo a ilustração SVG atual no hero por essa imagem/vídeo
3. Ajusto o layout ao redor dela se necessário
