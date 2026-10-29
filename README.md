# curio3d · Estúdio 3D de curiosidades

Gera vídeos curtos de curiosidades em 3D só com código (Three.js): personagens, cenários, animações, câmera e renderização em `.webm`. Roda 100% no navegador.

- Roteiro em texto vira cenas automaticamente e pode ser ajustado cena a cena.
- Narrador definido por prompt (tipo, cor, óculos, chapéu, capa, voz, atmosfera, cenário) ou por modelo `.glb`/`.gltf` enviado.
- Exporta o projeto em `.json` para repetir o estilo com outros roteiros.

## Publicar no GitHub Pages (usuário iamyoungdev)

```bash
git init -b main
git add .
git commit -m "Estúdio 3D de curiosidades"
gh repo create iamyoungdev/stufffield --public --source=. --push
gh api -X POST repos/iamyoungdev/stufffield/pages -f "source[branch]=main" -f "source[path]=/"
```

Endereço final: https://iamyoungdev.github.io/stufffield/ (leva cerca de 1 minuto para ficar no ar).
