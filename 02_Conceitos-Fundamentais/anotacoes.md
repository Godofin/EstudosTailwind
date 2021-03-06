## Conceitos Iniciais

## Tudo é classe
- Estilizamos nosso projeto por meio de classes;
- Temos classes desde cor de fote até pseudo seletores(hover);
- Podemos adicionar classe para determinados break points(responsivo);
- Podemos também criar as nossas classes com base em classes;

## Utility First

- A premissa do Tailwind é contruir componentes complexos com um conjunto de **utilitários**
- Ou seja, em vez de pegar um componente ou codas muitas linhas de CSS, utilizamos um **conjunto de classes**;
- E desta maneira podemos criar diversas varições de componentes, de forma simples;
- Ou **componentes únicos** para projetos

## Reponsivo - Mobile First

- Todas as classes podem ser aplicadas a um **determinado breakpoint**;
- Os que vem com framework são: **sm(small), md(medium), lg(large) e xl(extra large)**;
- Lembrando que é **mobile first**, ou seja, as classes são aplicadas para resoluções acima destes breakpoints;
- Então, **não utilizamos nenhum breakpoint** para atingir o mobile;

## Pseudo-Classes

- Podemos atingir **pseudo classes** com Tailwind também;
- Um exemplo seria o **hover**, quando passamos o ponteiro do mouse em cima de um elemento;
- Desta maneira basta adicionar: **hover:classe**;
- E então ela **só será executada** quando preencher os requisitos;

## Componentização

- Em tailwind somos encorajados a **não utilizar** componente prontos;
- Primeiramente desenvolvemos o que precisamos e depois podemos **transformar em um componente**(via apply);
- Essa abordagem é interessante pois nem sempre tudo é definido no CSS, talvez precisamos de uma estrutura de HTML diferenciada;