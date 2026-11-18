# Última Vigília

Teste web independente baseado na Revisão 49 do jogo de Gustavo Zavon Pestana.

[Jogar no navegador](https://Pestana04.github.io/ultima-vigilia-web/)

Use um navegador de desktop com aceleração gráfica. Os controles podem ser alterados no menu do jogo. A campanha tem dez fases, combate, duas versões da Ultimate, loja, cutscenes narradas e dez slots de memória. Os saves e as configurações são armazenados no navegador usado para jogar.

## Arquivos

A lógica da Revisão 49 está em `scripts/`. `runtime.js` adapta os objetos, as camadas e a entrada. `renderer.js` desenha sprites e textos usando WebGL. `boot.js` carrega os arquivos de cada fase e inicia a campanha.

As imagens, músicas, vozes e efeitos estão em `midia-revisao-49.zip`, na release `revisao-49`. O workflow do Pages combina esse pacote com o código deste repositório e publica o site.

Para rodar localmente, baixe e extraia o pacote de mídia na raiz do repositório e inicie um servidor HTTP nessa pasta, por exemplo com `python -m http.server 8000`.

## Créditos

Última Vigília por Gustavo Zavon Pestana. Personagens e cenários creditados a Rosebud. Voz da protagonista gerada com ElevenLabs.

Trilhas do menu, das dez fases e do chefe final por [migfus20](https://opengameart.org/users/migfus20).

Escudos e lâminas por [StarNinjas](https://opengameart.org/users/starninjas), CC0. As atribuições dos demais efeitos estão em `files/creditos-efeitos.txt`, incluído no pacote de mídia.

Inspirações da personagem e do jogo incluem Acheron e Blade, de Honkai Star Rail.
