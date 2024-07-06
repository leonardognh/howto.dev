# Seletores

## Classe

CSS não se limita a selecionar elementos por seu tipo. Como você sabe, elementos HTML também podem ter atributos. Ao trabalhar com HTML e CSS, um atributo de classe é uma das maneiras mais comuns de selecionar um elemento.

Por exemplo, considere o seguinte HTML:

`<p class='marca'>Nike</p>`

O elemento de parágrafo no exemplo acima tem um atributo de classe dentro da tag de abertura do elemento `<p>`. O atributo de `class` é definido como `'marca'`. Para selecionar este elemento usando CSS, podemos criar um conjunto de regras com um seletor de classe de `.marca`.

```
.marca {

}
```

Para selecionar um elemento HTML por sua classe usando CSS, um ponto (.) deve ser prefixado ao nome da classe. No exemplo acima, a classe é `marca`, então o seletor CSS para ela é `.marca`.
