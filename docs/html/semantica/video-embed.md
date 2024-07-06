# Semantica

## Video e Embed

Conforme demonstrado no exercício anterior, o conteúdo de mídia pode ser uma adição útil a um site. Ao usar um elemento `<video>`, podemos adicionar vídeos ao nosso site. O elemento `<video>` deixa claro que um desenvolvedor está tentando exibir um vídeo para o usuário.

Alguns atributos que podem alterar a reprodução de um vídeo incluem:

- `controls`: quando adicionado, um botão de reprodução/pausa será adicionado ao vídeo junto com o controle de volume e uma opção de tela cheia.
- `autoplay`: o atributo que resulta na reprodução automática de um vídeo assim que a página é carregada.
- `loop`: este atributo resulta na reprodução contínua do vídeo em repetição.
  Abaixo está um exemplo de `<video>` sendo usado com o atributo controls:

```
<video src="coding.mp4" controls>Vídeo não suportado</video>
```

<video src="coding.mp4" controls>Vídeo não suportado</video>

No código acima, um arquivo de vídeo chamado coding.mp4 está sendo reproduzido. O "Vídeo não suportado" só será exibido se o navegador não conseguir exibir o vídeo.

Outra tag que pode ser usada para incorporar conteúdo de mídia em uma página é a tag `<embed>`, que pode incorporar qualquer conteúdo de mídia, incluindo vídeos, arquivos de áudio e gifs de uma fonte externa. Isso significa que sites que têm um botão de incorporação têm alguma forma de conteúdo de mídia que pode ser adicionado a outros sites. A tag `<embed>` é uma tag de fechamento automático, diferente do elemento `<video>`. Observe que `<embed>` é uma tag obsoleta e outras alternativas, como `<video>`, `<audio>` e `<img>`, devem ser usadas em seu lugar, mas estão sendo ensinadas para fins de legado.

Abaixo, daremos uma olhada em `<embed>` sendo usado em ação.

```
<embed src="download.gif"/>
```

<embed src="download.gif"/>

No exemplo acima, `<embed>` está sendo usado para adicionar um gif de um arquivo local conhecido como download.gif. Embed pode ser usado para adicionar arquivos locais, bem como conteúdo de mídia diretamente de alguns outros sites.
