# Sintaxe Basica

## Folha de Estilo

Conforme dito anteriormente, estilos inline não são a melhor maneira de estilizar elementos HTML. Se você quisesse estilizar, por exemplo, vários elementos `<h1>`, você teria que adicionar estilo inline a cada elemento manualmente. Além disso, você também teria que manter o código HTML quando elementos `<h1>` adicionais fossem adicionados.

Felizmente, o HTML permite que você escreva código CSS em sua própria seção dedicada com um elemento `<style>` aninhado dentro do elemento `<head>`. O código CSS dentro do elemento `<style>` é frequentemente chamado de folha de estilo interna.

Uma folha de estilo interna tem certos benefícios e casos de uso sobre estilos inlines, mas, mais uma vez, não é uma prática recomendada (chegaremos lá, prometemos). Entender como usar folhas de estilo internas é, no entanto, um conhecimento útil a se ter.

Para criar uma folha de estilo interna, um elemento `<style>` deve ser colocado dentro do elemento `<head>`.

```
<head>
  <style>

  </style>
</head>
```

Após adicionar tags `<style>` de abertura e fechamento na seção head, você pode começar a escrever código CSS.

```
<head>
  <style>
    p {
      color: red;
      font-size: 20px;
    }
  </style>
</head>
```

O código CSS no exemplo acima altera a cor de todo o texto do parágrafo para vermelho e também altera o tamanho do texto para 20 pixels. Observe como a sintaxe do código CSS corresponde (na maior parte) à sintaxe que você usou para o estilo inline. A principal diferença é que você pode especificar quais elementos aplicar o estilo.
