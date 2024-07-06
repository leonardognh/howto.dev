# Seletores

## Pseudo Classes

Você pode ter observado como a aparência de certos elementos pode mudar, ou estar em um estado diferente, após certas interações do usuário. Por exemplo:

Quando você clica em um elemento `<input>`, e uma borda azul é adicionada mostrando que ele está em foco.

Quando você clica em um link azul `<a>` para visitar outra página, mas quando você retorna o texto do link é roxo.

Quando você está preenchendo um formulário e o botão de envio está acinzentado e desabilitado. Mas quando todos os campos foram preenchidos, o botão tem uma cor mostrando que está ativo.

Esses são todos exemplos de seletores de pseudoclasse em ação! Na verdade, `:focus`, `:visited`, `:disabled` e `:active` são todos pseudo classes. Fatores como interação do usuário, navegação no site e posição na árvore de documentos podem dar aos elementos um estado diferente com pseudoclasse.

Uma pseudo classe pode ser anexada a qualquer seletor. É sempre escrito como dois pontos : seguido por um nome. Por exemplo, `p:hover`.

```
p:hover {
  background-color: lime;
}
```

No código acima, sempre que o mouse passar sobre um elemento de parágrafo, esse parágrafo terá um fundo cor de limão.
