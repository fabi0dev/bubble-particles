# Bubble Particles

Primeiramente faça a importação

```js
import { bubbleParticles } from "./particles";
```

Depois use:

```js
useEffect(() => {
  //bubbleParticles(selector);
  const particles = bubbleParticles("#hero-particles");
  particles.start();
}, []);
```

####Métodos

`.start()` Inícia a animação.
`.play()` Retorma a animação caso foi pausada.
`.pause()` Pausa a animação.
`.remove()` Remove toda a animação do contexto
