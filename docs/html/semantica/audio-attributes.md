# Semantica

## Audio e Atributos

Agora que aprendemos sobre conteúdo baseado em texto, vamos nos aprofundar em `<audio>`! Certamente todo mundo precisa de `<audio>` — de que outra forma você ouviria seu hip hop coreano?

O elemento `<audio>` é usado para incorporar conteúdo de áudio em um documento. Como `<video>`, `<audio>` usa `src` para vincular a fonte de áudio.

```
<audio>
  <source src="audioFile.mp3" type="audio/mp3">
</audio>
```

Neste exemplo, criamos um elemento `<audio>`. Em seguida, criamos um elemento `<source>` para encapsular nosso link de áudio. Neste caso, iAmAnAudioFile.mp3 é nosso arquivo de áudio. Em seguida, especificamos o tipo usando type e nomeamos que tipo de áudio é. Embora nem sempre seja necessário, é recomendável que declaremos o tipo de áudio, pois isso ajuda o navegador a identificá-lo mais facilmente e determinar se esse tipo de arquivo de áudio é suportado pelo navegador.

Vinculamos nosso arquivo de áudio ao navegador, mas agora precisamos dar a ele controles. É aqui que os atributos entram. Os atributos fornecem informações adicionais sobre um elemento.

Os atributos nos permitem fazer muitas coisas diferentes com nosso arquivo de áudio. Existem muitos atributos para `<audio>`, mas hoje vamos nos concentrar em controles e `src`.

controls: exibe automaticamente os controles de áudio no navegador, como reproduzir e silenciar.

`src`: especifica a URL do arquivo de áudio.

Como você deve ter notado, já usamos o atributo `src` no código de exemplo acima. A maioria dos atributos vai na tag de abertura de `<audio>`. Por exemplo, aqui está como poderíamos adicionar a funcionalidade de reprodução automática e controles de áudio:

```
<audio autoplay controls>
```

<audio autoplay controls>

Você pode encontrar outros atributos aqui:
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio#attributes" target="_blank">Atributos úteis</a>
