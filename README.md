# Página Sobre Hotel Fictício

## Descrição

Página de apresentação de um hotel fictício desenvolvida com HTML e CSS.

## Status do projeto

Aguardando novas orientações.

## O que aprendi?

Durante o desenvolvimento desse projeto pude aprender sobre HTML semântico, *aria-attributes*, como `role` e `aria-label`, práticas modernas de css com sass e responsividade.

## Tecnologias

- HTML
- CSS / Sass
- Flexbox
- Grid

## Destaques

Validação de campos do formulário com pseudo-elementos

```css
input {
    background-color: transparent;
    border: 0;
    border-bottom: 1px solid v.$clr-neutral-700;
    outline: none;
    padding-block: 0.5rem;
    width: 100%;

    &:focus {
        border-bottom-color: v.$clr-accent;
    }

    &:not(:placeholder-shown):invalid:not(:focus) {
        color: v.$clr-accent;
        border-bottom-color: v.$clr-accent;
    }

    &:not(:placeholder-shown):invalid:not(:focus) + span {
        display: block;
    }
}
```

## Sites de referência

- [Modern Fluid Typography Using CSS Clamp, Adrian Bece](https://www.smashingmagazine.com/2022/01/modern-fluid-typography-css-clamp/)
- [:not, Sara Cope](https://css-tricks.com/almanac/selectors/n/not/)
- [Phosphor Icons](https://phosphoricons.com/)