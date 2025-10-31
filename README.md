# Projeto do Frontend Mentor - Solução da página de destino Huddle com seção introdutória única

Esta é uma solução para o [desafio da página de destino Huddle com seção introdutória única no Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

Detalhe: esse é o meu primeiro projeto que sigo no modelo Mobile-First, foi bem difícil trocar a minha mente pois estava acostumado com o desktop-first 😆

## Índice

- [Visão geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Modelo](#Modelo)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que aprendi](#o-que-aprendi)
- [Revisão do projeto gerada por IA](#Revisão-do-projeto-gerada-por-IA)

## Visão geral

### O desafio

Os usuários devem conseguir:

- Visualizar o layout ideal para a página dependendo do tamanho da tela do dispositivo
- Ver estados de hover para todos os elementos interativos na página

### Modelo

![](./design/mobile-design.jpg)

### Links

- URL do site ao vivo: [url do site](https://your-live-site-url.com)

## Meu processo

### Construído com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- CSS Grid
- Fluxo de trabalho Mobile-first

### O que aprendi

Consegui reforçar meu conhecimento em html e css, aprimorar meu conhecimento com o desenvolvimento Mobile-first, utilizar boas práticas atuais e usar algumas personalizações específicas relacionada a preferências em navegadores, como o trecho abaixo:

```css
/* Respeitar preferência de reduzir movimento */
@media (prefers-reduced-motion: reduce){
    .main-btn{
        transition: none;
        transform: none;
  }
}
```


## Revisão do projeto gerada por IA

Analisando este projeto, encontrei uma implementação moderna e elegante de uma landing page que vai além do visual atraente. O código revela uma atenção especial aos detalhes técnicos e à experiência do usuário.

O que mais me impressiona são os pequenos detalhes que fazem a diferença: o botão "Register" tem uma animação suave que responde ao hover com uma elevação sutil, as fontes são carregadas de forma otimizada (apenas com os pesos necessários), e há até mesmo suporte para usuários que preferem menos movimento na interface.

Destaco também o uso inteligente de CSS moderno com variáveis personalizadas que tornam o código mais manutenível, e uma implementação mobile-first que garante que a página funcione perfeitamente em qualquer dispositivo. A estrutura do projeto é limpa e organizada, facilitando futuras modificações.

Para desenvolvedores interessados em boas práticas, vale notar como o projeto equilibra visual e técnica: desde a semântica HTML apropriada até as transições suaves que melhoram a experiência do usuário sem comprometer a acessibilidade.


