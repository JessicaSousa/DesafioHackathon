# Análise de partidas de League of Legends (LoL)

<a href="https://www.researchgate.net/figure/A-Map-of-the-League-of-Legends-game-play-in-the-classic-mode_fig1_319839481"><img src="https://www.researchgate.net/profile/Patrick-Shih-2/publication/319839481/figure/fig1/AS:539281729228800@1505586191613/A-Map-of-the-League-of-Legends-game-play-in-the-classic-mode.png" alt="A Map of the League of Legends game play in the classic mode."/></a>



League of Legends (LoL) é um jogo eletrônico online gratuito, do gênero batalha multijogador *,* desenvolvido e publicado pela **Riot Games** em 2009. Em League of Legends, os jogadores assumem o papel de "invocadores", que controlam campeões com habilidades únicas, que formam um time e lutam  contra o time adversário de outros invocadores ou controlados pelo  computador. No modo mais popular do jogo, o objetivo de cada time é  **destruir o Nexus da equipe adversária**, uma construção localizada na base e protegida por outras estruturas. Cada partida de League of Legends é  distinta, pois os **campeões sempre começam fracos** e progridem através da  **acumulação de ouro** e da **experiência ao longo do jogo** [[1](https://pt.wikipedia.org/wiki/League_of_Legends)].



## Conteúdo

Neste repositório utilizamos as informações contidas no *dataset* para realizar análises sobre o jogo LoL, com o propósito realizar uma tarefa de classificação.

### Sobre o dataset

- Contém dados de aproximadamente 25000 jogos ranqueados (SOLO QUEUE) do Elo platina
- A partir de 10 minutos, são extraídas características a cada 2 minutos de um *frame*
- São coletadas 55 características de ambos times (azul e vemelho), representando informações sobre: abates, mortes, ouro, experiência, nível do campeão.

## Requisitos

Para a resolução desta tarefa usamos as seguintes bibliotecas:

- Pré-processamento e leitura dos dados
  - zipfile 
  - pandas
  - numpy
- Visualização
  - matplotlib
  - seaborn
- Classificação
  - sklearn

O *jupyter notebook* e os dados utilizados estão identificados como [MarathonAI_vespertino.ipynb](MarathonAI_vespertino.ipynb) e [lol_ranked_games_red.zip](lol_ranked_games_red.zip) respectivamente.
