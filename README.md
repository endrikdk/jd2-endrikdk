# jd2-endrikdk

Jogos Digitais II — Endrik Perin (802.524)

## Aula 08 — A vila vista de cima

Vila de 40 × 24 peças (640 × 384 px) feita com dois `TileMapLayer` (`chao` e `objetos`) que
compartilham o mesmo TileSet (`tiles/vila.tres`), com peças grandes para as casas (4 × 3) e as
árvores altas (1 × 2). O personagem anda nas quatro direções (setas ou WASD), vira para o lado em
que anda e não atravessa casas, árvores, cerca, poço, placa nem o muro. A câmera acompanha com
zoom 3 e limites na borda da vila.

- Cena principal: `scenes/vila.tscn`
- Personagem: `entities/jogador.tscn` + `scripts/jogador.gd`
- Godot 4.7, renderer Compatibility

## Créditos

- Tileset: Tiny Town, de Kenney — https://kenney.nl/assets/tiny-town — licença CC0
- Personagem: Prof. Ezefferth, para a Aula 08 de Jogos Digitais II
