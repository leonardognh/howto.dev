# Seletores

## Multiplos Seletores

Para tornar o CSS mais conciso, é possível adicionar estilos CSS a vários seletores CSS de uma só vez. Isso evita escrever código repetitivo.

Por exemplo, o código a seguir tem atributos de estilo repetitivos:

```
h1 {
  font-family: Georgia;
}

.menu {
  font-family: Georgia;
}
```

Em vez de escrever `font-family: Georgia` duas vezes para dois seletores, podemos separar os seletores por uma vírgula para aplicar o mesmo estilo a ambos, assim:

```
h1,
.menu {
  font-family: Georgia;
}
```

Ao separar os seletores CSS com uma vírgula, tanto os elementos `<h1>` quanto os elementos com a classe menu receberão o estilo `font-family: Georgia`.
