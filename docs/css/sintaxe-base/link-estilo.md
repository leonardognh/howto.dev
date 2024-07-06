# Sintaxe Basica

## Linkar Estilo

Separamos com sucesso a estrutura (HTML) do estilo (CSS), mas a página da web ainda parece sem graça. Por quê?

Quando os códigos HTML e CSS estão em arquivos separados, os arquivos devem ser vinculados. Caso contrário, o arquivo HTML não conseguirá localizar o código CSS e o estilo não será aplicado.

Você pode usar o elemento `<link>` para vincular arquivos HTML e CSS. O elemento `<link>` deve ser colocado dentro do cabeçalho do arquivo HTML. É uma tag de fechamento automático e requer os seguintes atributos:

href — como o elemento âncora, o valor deste atributo deve ser o endereço, ou caminho, para o arquivo CSS.
rel — este atributo descreve o relacionamento entre o arquivo HTML e o arquivo CSS. Como você está vinculando a uma folha de estilo, o valor deve ser definido como folha de estilo.
Ao vincular um arquivo HTML e um arquivo CSS, o elemento `<link>` ficará assim:

`<link href='./style.css' rel='stylesheet'>`

Usar um caminho relativo é uma maneira muito comum de vincular uma folha de estilo.
