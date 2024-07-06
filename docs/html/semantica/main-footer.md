# Semântica

## Main e Footer

Mais dois elementos estruturais são `<main>` e `<footer>`. Esses elementos, juntamente com `<nav>` e `<header>`, ajudam a descrever onde um elemento está localizado com base nos padrões convencionais de desenvolvimento web.

O elemento `<main>` é usado para encapsular o conteúdo dominante dentro de uma página da web. Esta tag é separada do `<footer>` e do `<nav>` de uma página da web, pois esses elementos não contêm o conteúdo principal. Ao usar `<main>` em vez de um elemento `<div>`, os leitores de tela e navegadores da web são mais capazes de identificar que o que quer que esteja dentro da tag é a maior parte do conteúdo.

Então, como `<main>` fica quando incorporado ao nosso código? Essa é uma ótima pergunta.

```
<main>
  <header>
    <h1>Tipos de esportes</h1>
  </header>
  <article>
    <h3>Beisebol</h3>
    <p>
      O primeiro jogo de beisebol foi disputado em Cooperstown, Nova York, no verão de 1839.
    </p>
  </article>
</main>
```

<fieldset>
  <main>
    <header>
      <h1>Tipos de esportes</h1>
    </header>
    <article>
      <h3>Beisebol</h3>
      <p>
        O primeiro jogo de beisebol foi disputado em Cooperstown, Nova York, no verão de 1839.
      </p>
    </article>
  </main>
</fieldset>

Como vemos acima, `<main>` contém uma tag `<article>` e `<header>` com elementos filhos que contêm as informações mais importantes relacionadas à página.

O conteúdo na parte inferior das informações do assunto é conhecido como rodapé, indicado pelo elemento `<footer>`. O rodapé contém informações como:

- Informações de contato

- Informações de direitos autorais

- Termos de uso

- Mapa do site

- Referência aos links do topo da página

Por exemplo:

```
<footer>
  <p>Envie-me um e-mail...</p>
</footer>
```

<fieldset>
  <footer>
    <p>Envie-me um e-mail...</p>
  </footer>
</fieldset>

No exemplo acima, o rodapé é usado para conter informações de contato. A tag `<footer>` é separada do elemento `<main>` e normalmente está localizada na parte inferior do conteúdo.
