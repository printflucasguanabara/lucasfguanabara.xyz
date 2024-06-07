---
title: "AUTOSALES - Página Inicial"
summary: "página inicial Landing page para um aplicativo de compra e venda de automóveis chamado AUTOSALES."
date: 2023-08-27
draft: false
tags: ["Desafio Técnico", "HTML", "CSS", "JavaScript"]

---

{{< keywordList >}}
{{< keyword icon="code" >}} **HTML** {{< /keyword >}}
{{< keyword icon="code" >}} **CSS**{{< /keyword >}}
{{< keyword icon="code" >}} **JavaScript**{{< /keyword >}}
{{< /keywordList >}}

> ORIGINALMENTE ESCRITO EM INGLÊS,
>
> TRADUÇÃO DESTE README [AUTOSALES-landing-page](https://github.com/printflucasguanabara/AUTOSALES-landing-page)

 [{{< icon "link" >}} Demonstração](https://autosales-landing-page.vercel.app/)



<BR><BR>

O projeto basicamented é página inicial Landing page para um aplicativo de compra e venda de automóveis chamado "AUTOSALES".


# Desafios Durante a Programação

Este foi o desafio em que tive mais dificuldade com JavaScript, mesmo sendo um código simples. Embora não tenha conseguido fazer a mudança do plano de fundo ou da cor de alguns textos em tempo real, adicionei um botão que simula o que deveria acontecer em tempo real. Centralizar objetos, usar divs para posicionamento e redimensionamento de imagens, trabalhar com planos de fundo e construir fielmente o layout foram os principais desafios durante esta codificação.

## Layout
Comecei desenvolvendo o wireframe no FIGMA.

<img src= "https://github.com/printflucasguanabara/AUTOSALES-landing-page/assets/110312548/a13f9e09-bc3a-461e-b79a-6c0ff7082e8a" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="500" height="400" />
<br>


{{< figure
    src="images1/wire.png"
    alt="Abstract purple artwork"
    caption="Photo by [Jr Korpa](https://unsplash.com/@jrkorpa) on [Unsplash](https://unsplash.com/)"
    >}}


Eu iria adicionar as cores e criar um layout detalhado, mas decidi ir para o código com HTML e CSS e detalhar as cores conforme avançava.

# Responsividade com Media Queries

Este aspecto proporciona uma experiência de usuário variada para diferentes dispositivos, o que exigiu muito de mim e do meu conhecimento. Aprendi muitas novas técnicas de posicionamento e outros conhecimentos valiosos.

# O JavaScript

É um código JavaScript simples, embora tenha lutado um pouco com ele. Ele muda a imagem de fundo e as cores do texto em uma página da web com o clique de um botão.

### Recursos:
- Altera a imagem de fundo da página.
- Altera as cores do texto para vários elementos, incluindo títulos, parágrafos, botões e links de navegação.

### Como Funciona

Quando o botão "Mudar Horário" é clicado, a função changeBackgroundAndTextColors() é chamada.
- Atualiza a imagem de fundo da página.
- Seleciona todos os elementos de texto desejados e atualiza suas cores de texto com base no índice atual.

# Acesso Detalhado aos Fusos Horários

Adicionei um botão no canto superior esquerdo que simula o que os usuários podem ver quando a aparência da página inicial muda durante períodos de tempo específicos:
- **05:00 às 12:00**
<img src="https://github.com/printflucasguanabara/AUTOSALES-landing-page/assets/110312548/abc85ed2-fdb3-4ffd-a8bc-6da2dec8f0ba" width="700" height="400" />

- **12:00 às 18:00**
<img src="https://github.com/printflucasguanabara/AUTOSALES-landing-page/assets/110312548/9afa7486-aa61-4465-9eb5-508ea2972ca9" width="700" height="400" />


- **18:00 às 05:00**
<img src="https://github.com/printflucasguanabara/AUTOSALES-landing-page/assets/110312548/c747d168-b6fe-493f-9f49-7d974406b0ee" width="700" height="400" />


Apesar de ser uma página inicial simples, aprendi com alguns erros e coloquei meus conhecimentos em prática.

