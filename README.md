# Flappy Byrd — Sky Quest

Uma versão moderna e personalizável do clássico jogo de voo e obstáculos. Em **Flappy Byrd — Sky Quest**, o jogador controla um personagem, atravessa os espaços entre os obstáculos, completa missões e acumula moedas e experiência.

O jogo funciona diretamente no navegador e foi desenvolvido com HTML, CSS e JavaScript puro.

## Funcionalidades

- Jogabilidade inspirada no clássico Flappy Bird.
- Sistema de pontuação e recorde pessoal.
- Progressão por níveis e experiência (XP).
- Recompensas em moedas.
- Missões com objetivos e recompensas.
- Progresso salvo automaticamente no navegador.
- Interface responsiva para computadores e dispositivos móveis.
- Efeitos sonoros para salto, pontuação e fim de partida.

## Skins disponíveis

O personagem pode ser personalizado antes de cada partida. A skin original do jogo continua disponível como opção padrão.

- Byrd Clássico
- Papagaio
- Morcego
- Super-Gato
- Super-Cão
- Abelhinha

A skin escolhida fica salva e será utilizada nas próximas partidas.

## Cenários disponíveis

O jogador também pode escolher o ambiente da partida:

- Amanhecer
- Dia Tropical
- Noite Lunar
- Aurora Mágica

Cada cenário possui cores, iluminação, efeitos atmosféricos e obstáculos visualmente adaptados ao tema selecionado.

## Como jogar

O objetivo é atravessar o maior número possível de obstáculos sem tocar nos canos, no chão ou no limite superior da tela.

### Controles

| Ação | Computador | Celular ou tablet |
| --- | --- | --- |
| Voar | `Espaço`, `W` ou `Seta para cima` | Toque na tela |
| Iniciar partida | Botão **Começar voo** | Botão **Começar voo** |
| Reiniciar | Botão **Voar novamente** | Botão **Voar novamente** |

## Como executar localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/iago-duarte99/Flappy-Byrd.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd Flappy-Byrd
   ```

3. Abra o arquivo `index.html` no navegador.

Para executar por meio de um servidor local, você também pode usar:

```bash
python -m http.server 8000
```

Depois, acesse `http://localhost:8000` no navegador.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Canvas API
- Web Audio
- Local Storage

## Estrutura do projeto

```text
Flappy-Byrd/
├── assets/
│   └── skins/          # Imagens das skins personalizadas
├── background.png      # Imagem de apoio dos cenários
├── bird.png            # Skin clássica original
├── game.js             # Jogabilidade, física e personalização
├── style.css           # Interface e responsividade
├── index.html          # Estrutura principal do jogo
├── jump.mp3            # Som do salto
├── score.mp3           # Som de pontuação
└── game-over.wav       # Som de fim da partida
```

## Salvamento do progresso

O jogo utiliza o Local Storage do navegador para guardar automaticamente:

- Recorde pessoal
- Moedas
- Experiência e nível
- Progresso das missões
- Skin selecionada
- Cenário selecionado

Ao limpar os dados do navegador ou selecionar **Reiniciar progresso**, essas informações serão removidas.

## Autor

Desenvolvido por [Iago Duarte](https://github.com/iago-duarte99).

## Licença

Este projeto é destinado a estudos e demonstração. Antes de reutilizar ou distribuir imagens e efeitos sonoros, verifique as licenças dos respectivos assets.
