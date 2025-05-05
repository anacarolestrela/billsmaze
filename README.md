#  Bills Maze

**Bills Maze** é uma simulação simples de um personagem (Bill) tentando encontrar um tesouro em um labirinto utilizando **heurísticas** para guiar seus movimentos. O objetivo do projeto é demonstrar uma abordagem baseada em heurísticas puras, sem busca exaustiva ou algoritmos clássicos como A* ou BFS. Contudo, encontrar um caminho até o tesouro, mesmo que aja um caminho possivel não é garantido dessa forma

##  Heurísticas Utilizadas

1. **Distância Euclidiana até o Tesouro**  
   Bill calcula a distância direta (em linha reta) entre sua posição atual e o tesouro, e se move na direção que mais reduz essa distância.

2. **Proximidade de Paredes (Heurística de Aleatoriedade)**  
   Quando Bill está muito próximo de paredes, ele pode fazer movimentos **aleatórios**. Isso impede que ele fique preso em cantos.

##  Requisitos

- Python 3.x
- `matplotlib` para visualização

```bash
pip install matplotlib

## Como executar
python bills_maze.py
