# Bubble Particles

Primeiramente faça a importação

```js
import { bubbleParticles } from "./particles";
```

Depois use:

```js
useEffect(() => {
  //bubbleParticles(selector);
  const particles = bubbleParticles("#hero-particles", {
    bubbleDensity: 15, //count bubbles
    rgbColors: [
      "85,107,139",
      "68,160,255",
      "76,175,80",
      "243, 244, 255",
      "96, 100, 131",
    ],
  });
  particles.start();
}, []);
```

#### Métodos

`.start()` Inícia a animação.
`.play()` Retorma a animação caso foi pausada.
`.pause()` Pausa a animação.
`.remove()` Remove toda a animação do contexto
