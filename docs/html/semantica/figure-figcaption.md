# Semantica

## Figure e Figcaption

Com `<aside>`, aprendemos que podemos colocar informações adicionais ao lado de uma parte principal do conteúdo, mas e se quiséssemos adicionar uma imagem ou ilustração? É aí que `<figure>` e `<figcaption>` entram.

`<figure>` é um elemento usado para encapsular mídia, como uma imagem, ilustração, diagrama, trecho de código, etc., que é referenciado no fluxo principal do documento.

```
<figure>
  <img src="overwatch.png">
</figure>
```

<fieldset>
  <figure>
    <img src="./overwatch.png">
  </figure>
</fieldset>

Neste código, criamos um elemento `<figure>` para que possamos encapsular nossa tag `<img>`. Em `<figure>`, usamos a tag `<img>` para inserir uma imagem na página da web. Usamos o atributo src dentro da tag `<img>` para que possamos vincular a fonte da imagem.

É possível adicionar uma legenda à imagem usando `<figcaption>`.

`<figcaption>` é um elemento usado para descrever a mídia na tag `<figure>`. Normalmente, `<figcaption>` ficará dentro de `<figure>`. Isso é diferente de usar um elemento `<p>` para descrever o conteúdo; se decidirmos alterar a localização de `<figure>`, a tag de parágrafo pode ser deslocada da figura enquanto um `<figcaption>` se moverá com a figura. Isso é útil para agrupar uma imagem com uma legenda.

```
<figure>
  <img src="overwatch.png">
  <figcaption>
    Esta imagem mostra personagens de Overwatch.
  </figcaption>
</figure>
```

<fieldset>
  <figure>
  <img src="./overwatch.png">
  <figcaption>
    Esta imagem mostra personagens de Overwatch.
  </figcaption>
  </figure>
</fieldset>

No exemplo acima, adicionamos um `<figcaption>` ao elemento `<figure>` para descrever a imagem do exemplo anterior. Isso ajuda a agrupar o conteúdo `<figure>` com o conteúdo `<figcaption>`.

Embora o conteúdo em `<figure>` esteja relacionado ao fluxo principal do documento, sua posição é independente. Isso significa que você pode removê-lo ou movê-lo para outro lugar sem afetar o fluxo do documento.
