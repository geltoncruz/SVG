# SVG
Svg é uma linguagem xml usado para desenhar gráficos.

## Pré-requisitos

Antes de inicarmos o estudo isolado sobre SVG, é importante ressaltar a a necessidade de conhecermos um pouco de XML.


### Exemplo simples

```html
    <svg version="1.1"
    baseProfile="full" 
    width="300" height="300"
    xmlns="http://www.w3.org/2000/svg">
        <rect width="100%" height="100%" fill="red" />
        <circle cx="150" cy="150" r="80" fill="green" />
        <text X="150" Y="125" font-size="60" text-anchor="middle" fill="white">SVG</text>
    </svg>
```
