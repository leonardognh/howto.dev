# Seletores

## Multiplas Classes

Podemos usar CSS para selecionar o atributo de classe de um elemento HTML pelo nome. E até agora, selecionamos elementos usando apenas um nome de classe por elemento. Se cada elemento HTML tivesse uma única classe, todas as informações de estilo para cada elemento exigiriam uma nova classe.

Felizmente, é possível adicionar mais de um nome de classe ao atributo de classe de um elemento HTML.

Por exemplo, talvez haja um elemento de título que precise ser verde e em negrito. Você pode escrever dois conjuntos de regras CSS assim:

```
.verde {
  color: green;
}

.negrito {
  font-weight: bold;
}
```

Então, você pode incluir ambas as classes em um elemento HTML assim:

`<h1 class="verde negrito"> ... </h1>`

<h1 style="color: green; font-weight: bold;"> Olá </h1>

Podemos adicionar várias classes ao atributo de classe de um elemento HTML separando-as com um espaço. Isso nos permite misturar e combinar classes CSS para criar muitos estilos exclusivos sem escrever uma classe personalizada para cada combinação de estilo necessária.
