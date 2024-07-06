# Seletores

## ID

Muitas vezes é importante selecionar um único elemento com CSS para dar a ele seu próprio estilo único. Se um elemento HTML precisa ser estilizado de forma única, podemos dar a ele um ID usando o atributo id.

`<h1 id='titulo-grande'> ... </h1>`

Ao contrário da classe que aceita vários valores e pode ser usada amplamente em um documento HTML, o id de um elemento pode ter apenas um único valor e ser usado apenas uma vez por página.

Para selecionar o ID de um elemento com CSS, acrescentamos ao nome do id um sinal numérico (#). Por exemplo, se quiséssemos selecionar o elemento HTML no exemplo acima, ficaria assim:

```
#titulo-grande {

}
```

O nome do id é titulo-grande, portanto, o seletor CSS para ele é `#titulo-grande`.
