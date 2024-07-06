# Seletores

## Descendentes

Além de encadear seletores para selecionar elementos, o CSS também suporta a seleção de elementos aninhados em outros elementos HTML, também conhecidos como descendentes. Por exemplo, considere o seguinte HTML:

```
<ul class='main-list'>
  <li> ... </li>
  <li> ... </li>
  <li> ... </li>
</ul>
```

Os elementos `<li>` aninhados são descendentes do elemento `<ul>` e podem ser selecionados com o combinador descendente como:

```
.main-list li {

}
```

No exemplo acima, `.main-list` seleciona o elemento com a classe `.main-list` (o elemento `<ul>`). Os `<li>` descendentes são selecionados adicionando li ao seletor, separados por um espaço. Isso resulta em `.main-list li` como o seletor final.

Selecionar elementos dessa forma pode tornar nossos seletores ainda mais específicos, garantindo que eles apareçam no contexto que esperamos.
