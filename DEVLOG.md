# DEVLOG

## 07/10/2026 — Aula 08

- Fiz a vila vista de cima: grama, rua em cruz, seis casas, árvores, arbustos, poço, placa, uma horta cercada e o muro em volta, em duas camadas (`chao` e `objetos`) com o mesmo TileSet.
- O personagem anda nas quatro direções com `Input.get_vector`, troca a animação pelo eixo que pesa mais e para olhando para o último lado.
- Travou: a casa saía em pedaços. Resolvi apagando as peças pequenas antes de criar a peça grande de 4 × 3 no TileSet.
- A peça grande fica centrada na célula clicada, então as casas foram colocadas clicando no meio delas, e não no canto.
- Colisão só nos pés (10 × 6) e Motion Mode Floating: o personagem desliza ao longo das casas em vez de grudar.
