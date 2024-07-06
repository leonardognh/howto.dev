# Seletores

## Atributos

Você pode se lembrar de que alguns elementos HTML usam atributos para adicionar detalhes ou funcionalidades extras ao elemento. Alguns atributos familiares podem ser href e src, mas há muitos mais, incluindo class e id!

O seletor de atributos pode ser usado para direcionar elementos HTML que já contêm atributos. Elementos do mesmo tipo podem ser direcionados de forma diferente por seu atributo ou valor de atributo. Isso alivia a necessidade de adicionar novo código, como os atributos class ou id.

Os atributos podem ser selecionados de forma semelhante a tipos, classes e IDs.

```
[href]{
  color: magenta;
}
```

A sintaxe mais básica é um atributo cercado por colchetes. No exemplo acima: `[href]` direcionaria todos os elementos com um atributo href e definiria a cor como magenta.

E pode ficar mais granular a partir daí adicionando valores de tipo e/ou atributo. Uma maneira é usando `type[attribute*=value]`. Em resumo, este código seleciona um elemento onde o atributo contém qualquer instância do valor especificado. Vamos dar uma olhada em um exemplo.

```
<img src='/images/seasons/cold/winter.jpg'>
<img src='/images/seasons/warm/summer.jpg'>
```

O código HTML acima renderiza dois elementos `<img>`, cada um contendo um atributo src com um valor que equivale a um link para um arquivo de imagem.

```
img[src*='winter'] {
  height: 50px;
}

img[src*='summer'] {
  height: 100px;
}
```

Agora dê uma olhada no código CSS acima. O seletor de atributos é usado para direcionar cada imagem individualmente.

O primeiro conjunto de regras procura um elemento img com um atributo src que contém a string 'winter' e define a altura para 50px.

O segundo conjunto de regras procura um elemento img com um atributo src que contém a string 'summer' e define a altura para 100px.

Observe como nenhuma nova marcação HTML (como uma classe ou id) precisou ser adicionada, e ainda conseguimos modificar os estilos de cada imagem independentemente. Essa é uma vantagem de usar o seletor de atributos!
