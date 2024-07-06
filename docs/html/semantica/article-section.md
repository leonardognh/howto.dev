# Semantica

## Article e Section

Agora que cobrimos o corpo do HTML semântico, vamos nos concentrar no que pode ir no corpo. Os dois elementos em que vamos nos concentrar agora são `<section>` e `<article>`.

`<section>` define elementos em um documento, como capítulos, títulos ou qualquer outra área do documento com o mesmo tema. Por exemplo, conteúdo com o mesmo tema, como artigos sobre críquete, pode ficar em uma única `<section>`. A página inicial de um site pode ser dividida em seções para introdução, notícias e informações de contato.

Aqui está um exemplo de como usar `<section>`:

```
<section>
  <h2>Curiosidades sobre críquete</h2>
</section>
```

<fieldset>
  <section>
    <h2>Curiosidades sobre críquete</h2>
  </section>
</fieldset>

No código acima, criamos um elemento `<section>` para encapsular o código. Em `<section>`, adicionamos um elemento `<h2>` como título.

O elemento `<article>` contém conteúdo que faz sentido por si só. `<article>` pode conter conteúdo como artigos, blogs, comentários, revistas, etc. Uma tag `<article>` ajudaria alguém usando um leitor de tela a entender onde o conteúdo do artigo (que pode conter uma combinação de texto, imagens, áudio, etc.) começa e termina.

Aqui está um exemplo de como usar `<article>`:

```
<section>
  <h2>Curiosidades sobre críquete</h2>
  <article>
    <p>Uma única partida de críquete pode durar até 5 dias.</p>
  </article>
</section>
```

<fieldset>
  <section>
    <h2>Curiosidades sobre críquete</h2>
    <article>
      <p>Uma única partida de críquete pode durar até 5 dias.</p>
    </article>
  </section>
</fieldset>

No código acima, o elemento `<article>` contendo um fato sobre críquete foi colocado dentro do elemento `<section>`. É importante observar que um elemento `<section>` também pode ser colocado em um elemento `<article>` dependendo do contexto.
