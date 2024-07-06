# Seletor

## Encadeamento e Especificidade

Na última seção, em vez de selecionar todos os elementos `<h5>`, selecionamos apenas os elementos `<h5>` aninhados dentro dos elementos `.description`. Este seletor CSS era mais específico do que escrever apenas `h5`. Adicionar mais de uma tag, classe ou ID a um seletor CSS aumenta a especificidade do seletor CSS.

Por exemplo, considere o seguinte CSS:

```
p {
  color: blue;
}

.main p {
  color: red;
}
```

Ambas as regras CSS definem como um elemento `<p>` deve se parecer. Como `.main p` tem uma classe e um tipo `p` como seu seletor, apenas os elementos `<p>` dentro do elemento `.main` aparecerão em vermelho. Isso ocorre apesar de haver outra regra mais geral que afirma que os elementos `<p>` devem ser azuis.
