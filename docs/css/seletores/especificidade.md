# Seletores

## Especificidade

Especificidade é a ordem pela qual o navegador decide quais estilos CSS serão exibidos. Uma prática recomendada em CSS é estilizar elementos usando o menor grau de especificidade para que, se um elemento precisar de um novo estilo, seja fácil substituí-lo.

IDs são o seletor mais específico em CSS, seguidos por classes e, finalmente, tipo. Por exemplo, considere o seguinte HTML e CSS:

`<h1 class='headline'>Notícias de última hora</h1>`

```
h1 {
  color: red;
}

.headline {
  color: firebrick;
}
```

No código de exemplo acima, a cor do título seria definida como firebrick, pois o seletor de classe é mais específico do que o seletor de tipo. Se um atributo de ID (e seletor) fosse adicionado ao código acima, os estilos dentro do corpo do seletor de ID substituiriam todos os outros estilos para o título.

Com o tempo, conforme os arquivos crescem com o código, muitos elementos podem ter IDs, o que pode tornar o CSS difícil de editar, já que um estilo novo e mais específico deve ser criado para alterar o estilo de um elemento.

Para tornar os estilos fáceis de editar, é melhor estilizar com um seletor de tipo, se possível. Caso contrário, adicione um seletor de classe. Se isso não for específico o suficiente, considere usar um seletor de ID.
