# Semântica

## Header e Nav

Vamos dar uma olhada em alguns elementos semânticos que auxiliam na estrutura de uma página da web. Um `<header>` é um contêiner geralmente para links de navegação ou conteúdo introdutório contendo títulos de `<h1>` a `<h6>`.

O exemplo abaixo mostra `<header>` em ação:

```
<header>
  <h1>
    Tudo o que você precisa saber sobre pizza!
  </h1>
</header>
```

<fieldset>
  <header>
    <h1>
      Tudo o que você precisa saber sobre pizza!
    </h1>
  </header>
</fieldset>

Isso pode ser comparado ao código abaixo que usa uma tag `<div>` em vez de uma tag `<header>`:

```
<div id="header">
  <h1>
    Tudo o que você precisa saber sobre pizza!
  </h1>
</div>
```

<fieldset>
  <div id="header">
    <h1>
      Tudo o que você precisa saber sobre pizza!
    </h1>
  </div>
</fieldset>

Ao usar uma tag `<header>`, nosso código se torna mais fácil de ler. É muito mais fácil identificar o que está dentro das tags pai do `<h1>`, em oposição a uma tag `<div>` que não forneceria detalhes sobre o que estava dentro da tag.

Um `<nav>` é usado para definir um bloco de links de navegação, como menus e tabelas de conteúdo. É importante notar que `<nav>` pode ser usado dentro do elemento `<header>`, mas também pode ser usado sozinho.

Vamos dar uma olhada no exemplo abaixo:

```
<header>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </nav>
</header>
```

<fieldset>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
      </ul>
    </nav>
  </header>
</fieldset>

Ao usar `<nav>` como uma forma de rotular nossos links de navegação, será mais fácil não apenas para nós, mas também para navegadores da web e leitores de tela lerem o código.
