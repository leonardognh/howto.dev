# Seletores

## Encadeamento

Ao escrever regras CSS, é possível exigir que um elemento HTML tenha dois ou mais seletores CSS ao mesmo tempo.

Isso é feito combinando vários seletores, o que chamaremos de encadeamento. Por exemplo, se houvesse uma classe especial para elementos `<h1>`, o CSS ficaria assim:

```
h1.special {

}
```

O código acima selecionaria apenas os elementos `<h1>` com uma classe especial. Se um elemento `<p>` também tivesse uma classe especial, a regra no exemplo não estilizaria o parágrafo.
