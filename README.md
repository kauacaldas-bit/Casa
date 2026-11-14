# Casa 3D — simulador de decoração

Simulador 3D da casa, montado a partir da planta baixa, para testar móveis, cores e decoração antes de comprar.

## O que tem

- **Vistas:** maquete, planta (de cima), por dentro e fachada.
- **Catálogo:** 128 peças em tamanho real (sala, cozinha, quartos, banheiro, serviço, decoração e área externa).
- **Edição:** arrastar, girar, trocar cor, ajustar altura, duplicar e remover. Os móveis encostam nas paredes ao chegar perto.
- **Pintura:** cada lado de cada parede pode ter uma cor; cinco opções de piso.
- **Exterior:** calçada da planta, terreno, muro com portões e telhado (liga/desliga).
- O projeto fica salvo no navegador (`localStorage`).

## Como rodar

Site estático, sem build. Abra `index.html` por um servidor local:

```bash
npx serve .
```

## Medidas

Casa de 5,99 × 8,58 m (externo), paredes de 12 cm, calçada de 0,60 m (esquerda e frente) e 0,63 m (fundos), conforme a planta.
São estimativas: profundidade do banheiro (1,50 m), posição das janelas e da porta da frente, pé-direito (2,60 m), tamanho do terreno, muro e telhado.

## Tecnologia

HTML + JavaScript puro com [three.js](https://threejs.org/) r160 (incluído em `three.min.js`).
