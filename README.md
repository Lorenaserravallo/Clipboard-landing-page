# Frontend Mentor - Clipboard landing page

Este é o desafio [Clipboard landing page challenge](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9) do Frontend Mentor.

![Design preview for the Clipboard landing page coding challenge](preview.jpg)

## Visão geral 🔍

### O desafio

Os usuarios devem ser capazes de:

- Ver o design adaptado ao tamanho de suas respectivas telas
- Ver os efeitos de hover em todos os elementos dinâmicos da página.

A escolha deste projeto foi feita para o meu desenvolvimento nos aspectos de responsividade e HTML semântico.

## Meu processo 🧠

### Construido com

- HTML Semantico
- CSS
- Flexbox
- Responsividade

### O que eu aprendi

Nessa desafio procurei prestar atenção nos meus conhecimentos relacionados à responsividade e organização do código, visando sempre seguir boas práticas.

Para criar uma Landing Page adaptável para telas maiores, utilizei media queries, ajustando estilos, tamanhos de fontes, espaçamentos e estruturas do layout.

A organização dos códigos me ajudou a criar elementos de forma que eu tivesse maior controle sobre o meu design. Essa boa prática facilita, futuramente, fazer melhorias, pois consigo encontrar partes específicas do código rapidamente.

**Uso de classes específicas para controle de estilo**

```css
.btn {
  display: block;
  gap: 1.2rem;
  flex-wrap: wrap;
}
.iOS {
  background-color: hsl(171, 66%, 44%);
}
.Mac {
  background-color: hsl(233, 100%, 69%);
}
```

**Uso de Media Queries para responsividade:**

```css
@media (max-width: 1024px) {
  h1 {
    font-size: 30px;
  }
  .txt2 {
    width: 70%;
  }
  .container-3 {
    flex-direction: column;
    align-items: center;
  }
  .computer {
    width: 90%;
  }
}
```

### Continuarei desenvolvendo💻

Apesar de conseguir aplicar media queries para responsividade, ainda assim tive dificuldades com a adaptação dos elementos. Pretendo estudar mais esse aspecto, assim como a nomeação de elementos e o HTML semântico, para melhorar a organização do meu código.

## Autores

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
